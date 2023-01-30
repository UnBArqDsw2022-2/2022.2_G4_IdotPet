## Histórico de Versão
| Versão | Data | Modificação | Autor(es) |
|:-:|:-:|:-:|:-:|
| 28/01/2023 | 0.1 | Criação do documento | [Victor Cabral](https://github.com/victordscabral) & [Herick Lima](https://github.com/hericklima22)|
| 29/01/2023 | 0.2 | Adição da reutilização no frontend | [Victor Cabral](https://github.com/victordscabral) & [Herick Lima](https://github.com/hericklima22)|
| 29/01/2023 | 0.3 | Adição das imagens | [Nicolas Roberto](https://github.com/Nicolas-Roberto) & [Thales Alves](https://github.com/Thalisson-Alves)|
| 29/01/2023 | 0.3 | Adição das imagens | Kayro, Pedro e Durso](https://github.com/Nicolas-Roberto) & [Thales Alves](https://github.com/Thalisson-Alves)|
| 30/01/2023 | 0.3 | Adição de reusabilidade do Flutter | [Luan Cavalcante](https://github.com/Luan-Cavalcante) |


# Documento de Reutilização de Software

## Introdução

A reutilização de software consiste na utilização de conceitos, produtos e soluções já pré-elaboradas ou adquiridas para evitar retrabalho, aumentando a qualidade e produtividade do processo e produto de software. Também reduz custos, padroniza os produtos de software e facilita a manutenção e testes.   

Essa reutilização leva em conta tanto o nível de código quanto de requisitos, projeto e outros. Bibliotecas, plugins, serviços, frameworks são alguns exemplos de ferramentas utilizadas para reutilização.

Dois conceitos importantes quanto a reutilização e frameworks são os de Hot-Spots e Frozen-Spots.

- Hot-Spots: flexíveis e projetados para serem genéricos e adaptáveis as necessidades, sendo normalmente representados por classes abstratas.

- Frozen-Spots: fixos nas instanciações do framework, definindo a arquitetura geral do sistema.

## Reutilização no Frontend

### Flutter

Criado pela Google, o Flutter é um dos principais frameworks focado em desenvolvimento mobile tanto Android quanto iOS. Ele possui a linguagem Dart como base sendo muito utilizado no mercado. Um grande diferencial dessa tecnologia é que o código acaba sendo compilado para a linguagem base do dispositivo mobile, não necessitando de terceiros para acessar direto aos recursos nativos do sistema.

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/flutter.png?raw=true" alt="image1"/>
  <figcaption align="center" >Figura 1 - Logo do Flutter. Fonte: Flutter </figcaption>
</figure>

Exemplos :

Definição de um Widget para um campo de formulário.

![Widget_code](https://user-images.githubusercontent.com/67024690/215378211-ffd7a52e-9e6f-4a3b-8665-13ec6a42ecf0.png)

Aqui é a utilização com vários campos usando a mesma função.

![Widget_usage](https://user-images.githubusercontent.com/67024690/215378224-f6687e27-5304-46e2-99d8-cc789e9bece1.png)


### Widgets

Os widgets são a hierarquia de classe central na estrutura do Flutter com linguagem Dart. Todo aplicativo Flutter é um widget, este composto de vários outros widgets combinados. São como pequenas peças que combinadas formam um aplicativo e constroem a interface. 

O Flutter fornece pacotes com diversos widgets úteis já prontos para uso, sendo então utilizados no frontend do IDotPet.

#### Material Design

Um dos principais e mais importantes pacotes disponíveis, sendo muito utilizado no projeto. Possui widgets com diversas funcionalidades que vão desde botões simples até alguns capazes de estruturar o projeto.

Para importar o pacote:

- import 'package:flutter/material.dart';

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/barra_navegacao.png?raw=true" alt="image2"/>
  <figcaption align="center" >Figura 2 - Widget: barra de navegação. Fonte: Autores </figcaption>
</figure>

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/nome_login.png?raw=true" alt="image3"/>
  <figcaption align="center" >Figura 3 - Widget: campo de nome no login. Fonte: Autores </figcaption>
</figure>

### GetX

package:get/get.dart

Conforme dito na documentação esse pacote combina um gerenciador de estado de alta performance, injeção de dependência inteligente e gerenciamento de rotas de uma forma rápida e prática. 

Boa parte dos utilizados no projeto se encaixam como Frozen-Spots.

Para importar o pacote:

- import 'package:get/get.dart';

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/app_bindings.png?raw=true" alt="image4"/>
  <figcaption align="center" >Figura 4 - App Bindings. Fonte: Autores </figcaption>
</figure>

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/app_routes.png?raw=true" alt="image5"/>
  <figcaption align="center" >Figura 5 - App Routes. Fonte: Autores </figcaption>
</figure>

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/use_case.png?raw=true" alt="image6"/>
  <figcaption align="center" >Figura 6 - User Use Case. Fonte: Autores </figcaption>
</figure>

### Dio

O pacote fornece um forte cliente HTTP para Dart, na qual oferece um suporte a interceptores, configuração global, FormData, cancelamento de solicitação, download de arquivos, tempo limite e outras funcionalidades. 

Para importar o pacote:

- import 'package:dio/dio.dart';

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/user_api.png?raw=true" alt="image7"/>
  <figcaption align="center" >Figura 7 - User API. Fonte: Autores </figcaption>
</figure>

## Reutilização no Backend

### FastAPI

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/fast_api.png?raw=true" alt="image8"/>
  <figcaption align="center" >Figura 8 - Utilização do FastAPI. Fonte: Autores </figcaption>
</figure>

### SQL Alchemy

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/sql_alchemy.png?raw=true" alt="image9"/>
  <figcaption align="center" >Figura 9 - Utilização do SQL Alchemy. Fonte: Autores </figcaption>
</figure>

### base_repository.py

Genérico para qualquer classe para acessar o banco.

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/base_repository.png?raw=true" alt="image10"/>
  <figcaption align="center" >Figura 10 - base_repository.py. Fonte: Autores </figcaption>
</figure>

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/repository_factory.png?raw=true" alt="image10"/>
  <figcaption align="center" >Figura 11 - repository_factory. Fonte: Autores </figcaption>
</figure>

### database.py

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/database.png?raw=true" alt="image11"/>
  <figcaption align="center" >Figura 12 - database.py. Fonte: Autores </figcaption>
</figure>

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/usando_database.png?raw=true" alt="image11"/>
  <figcaption align="center" >Figura 13 - Usando database.py. Fonte: Autores </figcaption>
</figure>

### Docker

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/dockerfile.png?raw=true" alt="image12"/>
  <figcaption align="center" >Figura 14 - Docker File. Fonte: Autores </figcaption>
</figure>

### docker-compose

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/dockercompose.png?raw=true" alt="image14"/>
  <figcaption align="center" >Figura 15 - docker-compose. Fonte: Autores </figcaption>
</figure>

## Referências

> Serrano, Milene. 2020. REUTILIZAÇÃO & FRAMEWORK. Disponível em: https://aprender3.unb.br/pluginfile.php/2277143/mod_label/intro/Arquitetura%20e%20Desenho%20de%20Software%20-%20Aula%20Reutiliza%C3%A7%C3%A3o%20%20Framework%20-%20Profa.%20Milene.pdf. Acesso em: 28 de jan. 2023.

> Devmedia. Reutilização de Sofware. DevMedia. Disponível em: https://www.devmedia.com.br/reutilizacao-de-software-revista-engenharia-de-software-magazine-39/21956. Acesso em: 28 de jan. 2023.

> https://api.flutter.dev/flutter/material/material-library.html

> https://pub.dev/packages/get

> https://pub.dev/packages/dio 

> https://blog.flutterando.com.br/consumindo-api-utilizando-o-dio-9ec72aeceeaa

> https://flutterparainiciantes.com.br/widgets/

> https://flutterparainiciantes.com.br/interface/material/ 
