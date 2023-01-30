## Histórico de Versão
| Versão | Data | Modificação | Autor(es) | Revisores |
|:-:|:-:|:-:|:-:|:-:|
| 28/01/2023 | 0.1 | Criação do documento | [Victor Cabral](https://github.com/victordscabral) & [Herick Lima](https://github.com/hericklima22)| [Pedro Cassiano](https://github.com/PedroLucasCM) & [João Durso](https://github.com/jvsdurso) & [Kayro César](https://github.com/kayrocesar)|
| 29/01/2023 | 0.2 | Adição da reutilização no frontend | [Victor Cabral](https://github.com/victordscabral) & [Herick Lima](https://github.com/hericklima22)| [Pedro Cassiano](https://github.com/PedroLucasCM) & [João Durso](https://github.com/jvsdurso) & [Kayro César](https://github.com/kayrocesar)|
| 29/01/2023 | 0.3 | Adição das imagens | [Nicolas Roberto](https://github.com/Nicolas-Roberto) & [Thalisson Alves](https://github.com/Thalisson-Alves)| [Pedro Cassiano](https://github.com/PedroLucasCM) & [João Durso](https://github.com/jvsdurso) & [Kayro César](https://github.com/kayrocesar)|
| 30/01/2023 | 0.4 | Adição de reusabilidade do Flutter | [Luan Cavalcante](https://github.com/Luan-Cavalcante) & [João Durso](https://github.com/jvsdurso) | [Pedro Cassiano](https://github.com/PedroLucasCM) & [Kayro César](https://github.com/kayrocesar)|
| 29/01/2023 | 0.5 | Adição texto na parte do backend | [Victor Cabral](https://github.com/victordscabral) & [Kayro César](https://github.com/kayrocesar)|[Pedro Cassiano](https://github.com/PedroLucasCM) |

# Documento de Reutilização de Software

## Introdução

A reutilização de software consiste na utilização de conceitos, produtos e soluções já pré-elaboradas ou adquiridas para evitar retrabalho, aumentando a qualidade e produtividade do processo e produto de software. Também reduz custos, padroniza os produtos de software e facilita a manutenção e testes.   

Essa reutilização leva em conta tanto o nível de código quanto de requisitos, projeto e outros. Bibliotecas, plugins, serviços, frameworks são alguns exemplos de ferramentas utilizadas para reutilização.

## Reutilização no Frontend

### Flutter

Criado pela Google, o Flutter é um dos principais frameworks focado em desenvolvimento mobile tanto Android quanto iOS. Ele possui a linguagem Dart como base sendo muito utilizado no mercado. Um grande diferencial dessa tecnologia é que o código acaba sendo compilado para a linguagem base do dispositivo mobile, não necessitando de terceiros para acessar direto aos recursos nativos do sistema.

Na figura 1 temos a definição de um Widget para um campo de formulário. Já na figura 2 temos a utilização do widget com vários campos usando a mesma função.

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/Widget_code.png?raw=true" alt="image1"/>
  <figcaption align="center" >Figura 1 - Widget para formulário. Fonte: Autores</figcaption>
</figure>

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/Widget_usage.png?raw=true" alt="image2"/>
  <figcaption align="center" >Figura 2 - Utilização do widget para formulário. Fonte: Autores</figcaption>
</figure>

### Widgets

Os widgets são a hierarquia de classe central na estrutura do Flutter com linguagem Dart. Todo aplicativo Flutter é um widget, este composto de vários outros widgets combinados. São como pequenas peças que combinadas formam um aplicativo e constroem a interface. 

O Flutter fornece pacotes com diversos widgets úteis já prontos para uso, sendo então utilizados no frontend do IDotPet.

#### Material Design

Um dos principais e mais importantes pacotes disponíveis, sendo muito utilizado no projeto. Possui widgets com diversas funcionalidades que vão desde botões simples até alguns capazes de estruturar o projeto.

Para importar o pacote:

- import 'package:flutter/material.dart';

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/barra_navegacao.png?raw=true" alt="image2"/>
  <figcaption align="center" >Figura 3 - Widget: barra de navegação. Fonte: Autores </figcaption>
</figure>

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/nome_login.png?raw=true" alt="image3"/>
  <figcaption align="center" >Figura 4 - Widget: campo de nome no login. Fonte: Autores </figcaption>
</figure>

### GetX

Conforme dito na documentação esse pacote combina um gerenciador de estado de alta performance, injeção de dependência inteligente e gerenciamento de rotas de uma forma rápida e prática. 

Boa parte dos utilizados no projeto se encaixam como Frozen-Spots.

Para importar o pacote:

- import 'package:get/get.dart';

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/app_bindings.png?raw=true" alt="image4"/>
  <figcaption align="center" >Figura 5 - App Bindings. Fonte: Autores </figcaption>
</figure>

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/app_routes.png?raw=true" alt="image5"/>
  <figcaption align="center" >Figura 6 - App Routes. Fonte: Autores </figcaption>
</figure>

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/use_case.png?raw=true" alt="image6"/>
  <figcaption align="center" >Figura 7 - User Use Case. Fonte: Autores </figcaption>
</figure>

### Dio

O pacote fornece um forte cliente HTTP para Dart, na qual oferece um suporte a interceptores, configuração global, FormData, cancelamento de solicitação, download de arquivos, tempo limite e outras funcionalidades. 

Para importar o pacote:

- import 'package:dio/dio.dart';

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/user_api.png?raw=true" alt="image7"/>
  <figcaption align="center" >Figura 8 - User API. Fonte: Autores </figcaption>
</figure>

## Reutilização no Backend

### FastAPI

O FastAPI é um framework Python focado no desenvolvimento de API’s, tem como principais características ser moderno, rápido e simples. É um framework relativamente novo, teve a sua primeira versão lançada no dia 15 de Novembro de 2018.

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/fast_api.png?raw=true" alt="image8"/>
  <figcaption align="center" >Figura 9 - Utilização do FastAPI. Fonte: Autores </figcaption>
</figure>

### SQL Alchemy
Desenvolvido para a linguagem de programação Python, o SQLAlchemy é um framework de mapeamento objeto-relacional SQL (ORM). O Mapeamento objeto-relacional ou simplesmente ORM é uma técnica de programação que auxilia na conversão de dados entre banco de dados relacionais e linguagens de programação que são orientadas à objetos.

A utilização deste Framework faz com que o programador reduza a programação de acesso ao banco de dados, desta forma, obtendo uma produtividade significativa no desenvolvimento de suas aplicações.

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/sql_alchemy.png?raw=true" alt="image9"/>
  <figcaption align="center" >Figura 10 - Utilização do SQL Alchemy. Fonte: Autores </figcaption>
</figure>

### base_repository.py

Genérico de uma classe para acessar o model do banco de dados. A figura 11 mostra o base repository e a figura 12 mostra ele sendo utilizado no repository factory.

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/base_repository.png?raw=true" alt="image10"/>
  <figcaption align="center" >Figura 11 - base_repository.py. Fonte: Autores </figcaption>
</figure>

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/repository_factory.png?raw=true" alt="image10"/>
  <figcaption align="center" >Figura 12 - repository_factory. Fonte: Autores </figcaption>
</figure>

### database.py

Foi criado com objetivo de ser um utilitário para facilitar o processo de se conectar ao banco dados. Possibilita abrir sessão para realizar funções como SELECT e CREATE por exemplo. No figura 13 temos o código do database.py e na 14 um exemplo do próprio sendo utilizado.

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/database.png?raw=true" alt="image11"/>
  <figcaption align="center" >Figura 13 - database.py. Fonte: Autores </figcaption>
</figure>

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/usando_database.png?raw=true" alt="image11"/>
  <figcaption align="center" >Figura 14 - Usando database.py. Fonte: Autores </figcaption>
</figure>

### Docker

O Docker foi utilizado como forma de reutilização pela equipe. Ele facilita a elaboração e administração de ambientes isolados através do empacotamento de uma aplicação ou ambiente dentro de um container. Condiz muito com a proposta de reutilização de software, simplificando e facilitando o fluxo de atividades dos desenvolvedores.

A seguir são apresentados o Dockerfile para gerar as imagens e o docker-compose para gerir os containers do Docker.

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/dockerfile.png?raw=true" alt="image12"/>
  <figcaption align="center" >Figura 15 - Dockerfile. Fonte: Autores </figcaption>
</figure>

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/reutilizacao/dockercompose.png?raw=true" alt="image14"/>
  <figcaption align="center" >Figura 16 - docker-compose. Fonte: Autores </figcaption>
</figure>

## Referências

> Serrano, Milene. 2020. REUTILIZAÇÃO & FRAMEWORK. Disponível em: https://aprender3.unb.br/pluginfile.php/2277143/mod_label/intro/Arquitetura%20e%20Desenho%20de%20Software%20-%20Aula%20Reutiliza%C3%A7%C3%A3o%20%20Framework%20-%20Profa.%20Milene.pdf. Acesso em: 28 de jan. 2023.

> Devmedia. Reutilização de Sofware. DevMedia. Disponível em: https://www.devmedia.com.br/reutilizacao-de-software-revista-engenharia-de-software-magazine-39/21956. Acesso em: 28 de jan. 2023.

> Api Flutter. Material Library. Api Flutter. Disponível em: https://api.flutter.dev/flutter/material/material-library.html. Acesso em: 29 de jan. 2023.

> Pub Dev. get 4.6.5. Pub Dev. Disponível em: https://pub.dev/packages/get. Acesso em: 29 de jan. 2023.

> Pub Dev. dio 4.0.6. Pub Dev. Disponível em: https://pub.dev/packages/dio. Acesso em: 29 de jan. 2023.

> OSSADA Toshi. Consumindo API utilizando o Dio. Flutterando. Disponível em: https://blog.flutterando.com.br/consumindo-api-utilizando-o-dio-9ec72aeceeaa. Acesso em: 29 de jan. 2023.

> Flutter para iniciantes. Widgets. Flutter para iniciantes. Disponível em: https://flutterparainiciantes.com.br/widgets/. Acesso em: 29 de jan. 2023.

> Flutter para iniciantes. Material. Flutter para iniciantes. Disponível em: https://flutterparainiciantes.com.br/interface/material/. Acesso em: 29 de jan. 2023.