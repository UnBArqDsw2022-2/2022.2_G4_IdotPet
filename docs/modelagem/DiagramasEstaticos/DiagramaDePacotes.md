# Diagrama de Pacotes

## Histórico de Versões

| Data      | Versão | Modificação                         | Autor                       |
| :-------- | :----- | :---------------------------------- | :-------------------------- |
| 28/11/2022 | 0.1    | Criação e estruturação do documento | [Eduardo Maia Rezende](https://github.com/eduardomr) & [Kayro César Silva Machado](https://github.com/kayrocesar)|  |
| 29/11/2022 | 0.2    | Inclusão de diagramas | [Eduardo Maia Rezende](https://github.com/eduardomr) & [Kayro César Silva Machado](https://github.com/kayrocesar)|  |

## Introdução

Diagramas de pacotes são diagramas de formato estrutural utilizados para apresentar, em forma de pacotes, a forma de organização e disposição de elementos.Esses diagramas proporcionam uma organização visual acerca de uma arquitetura em camadas de um classificador UML. Um pacote possui um agrupamento de vários elementos UML como:

- Diagramas
- Classes
- Outros Pacotes

Geralmente, cada elemento é colocado dentro do pacote e é representado como uma espécie de pasta de arquivo no diagrama.

## Benefícios

- Visão clara da estrutura e hierarquia dos elementos UML
- Simplificam diagramas de classes

- Visão geral de projetos de grande escala

- Elementos podem ser atualizados conforme evolução do projeto

## Componentes Básicos
  Um diagrama de pacotes é representado por dois simbolos, que são apresentados e descritos  abaixo: 

| Simbolo |  Nome  |                                  Descrição                                     |
| :-----: | :----: | :------------------------------------------------------------------------------: |
|    ![simbolo](uml-package-symbol.svg)     | Pacote | Agrupa elementos comuns com base de dados, comportamento ou interação do usuário |
|    ![simbolo](uml-package-symbol.svg)     | Dependência |Representa a relação entre um elemento e outro |

Os diagramas de pacotes são utilizados também para mostrar as dependências de importação e acesso entre os pacotes, classes e componentes do sistema. Existem dois principais tipos de dependências: 
 
 - Acesso: um pacote requer assistência das funções de outro pacote

 - Importação: indica que a funcionalidade foi importada de um pacote para outro


 As dependencias também podem estar divididas nas categorias:

 - Uso: elemento requer outro para sua implementação correta

 - Abstração: relaciona dois elementos que representam o mesmo conceito em niveis de abstração distintos

 - Disponibilização: representa a implementação de um artefato em um alvo de implementação

## Metodologia 

  Os participantes realizaram um estudo acerca do diagrama de pacotes e fizeram uma reunião remota no aplicativo Discord visando discutir possibilidades na construção do diagrama. De inicio, os integrantes responsáveis pela escolha das tecnologias do aplicativo também participaram da reunião auxiliando na construção do diagrama de pacotes. Para a construção do diagrama de pacotes presente neste documento foi utilizada a ferramenta LucidChart.

## Diagrama de Pacotes

![Diagrama de Pacotes](../assets/diagrama_pacotes/diagrama_pacotes.png)

## Referências



> LUCIDCHART. Tudo sobre diagramas de pacotes UML.LucidChart. Disponível em: https://www.lucidchart.com/pages/pt/diagrama-de-pacotes-uml. Acesso em: 28 de nov. de 2022.