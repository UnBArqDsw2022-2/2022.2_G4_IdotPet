# Backlog

## Histórico de Versões

| Data | Versão | Modificação | Autor |
| :- | :- | :- | :- |
|27/11/2022 | 0.1 | Criação  e elaboração do documento | [Klyssmann Oliveira](https://github.com/klyssmannoliveira) & [Victor Cabral](https://github.com/victordscabral) |

## Introdução 

Introdução -> texto teórico
  
## Metodologia

Esse documento foi elaborado a partir dos vários artefatos de elicitação de requisitos nas sprints anteriores. Como dito anteriormente, o Backlog do produto pode ser alterado durante a evolução do projeto. 

No presente documento, o backlog do produto seguirá a hierarquia exposto na Fig. 1, onde será composto por uma coleção de histórias de usuário, possuindo de 1 até N histórias. Em muitos times não se utiliza épicos, desta maneira a hierarquia permite que o backlog possua 0 a N épicos. Cada épico pode ser relacionado com 0 ou N funcionalidade, que por sua vez, cada funcionalidade se relaciona com 0 ou mais Histórias de Usuário. Finalizando, cada história produz 0 a N tarefas técnicas.

COLOCAR A FIG: backlog_hierarquia <<<<<<<<<<<<<<<<<<<>>>>>>>>>>>>>>>>>>>
<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/brainstorm/tema_parte1.png?raw=true" alt="Hierarquia do Backlog"/>
  <figcaption align="center" >Figura 1 - Hierarquia do Backlog. Fonte: Autores </figcaption>
</figure>



**Épico** (*Epic*) = É uma história de usuário que ainda não foi detalhada, é muito grande ou ainda possui muita incerteza. É a categoria com maior granularidade no backlog.

**Funcionalidade** (Feature) - Verbos no infinitivo que descrevem melhor as responsabilidades da aplicação.

**História de usuário** (*User Story - US*) - É um formato sucinto para escrita dos requisitos necessários para construção de um produto. Assim, uma história de usuário deve ser compreensível para clientes e consumidores.

**Tarefas** (*Tasks*) - São as especificações dos itens técnicos necessários para que uma História de Usuário se transforme em um incremento do produto.


### Épicos

|ID | Descrição resumida | Descrição
| :-: | :- | :- |
| E01 | Cadastro | Eu, enquanto usuário, desejo realizar um cadastro no aplicativo |
| E02 | Perfil | Eu, enquanto usuário, desejo configurar o meu perfil no aplicativo |
| E03 | Contato | Eu, enquanto usuário, desejo um meio de contato com outros usuários |
| E04 | Visualização | Eu, enquanto usuário, desejo visualizar informações sobre os animais disponíveis para adoção |
| E05 | Interação | Eu, enquanto usuário, desejo interagir com o aplicativo |
| E06 | Gerenciamento | Eu, enquanto gerenciador do aplicativo, desejo ter controle do conteúdo do aplicativo |


### Funcionalidades

| ID | Épico | Descrição |
| :-: | :-: | :-- |
| F01 | E01 | Cadastrar no sistema |
| F02 | E01 | Entrar no sistema (Login) |
| F03 | E01 | Sair do sistema (Logout) |
| F04 | E02 | Visualizar perfil |
| F05 | E02 | Editar informações do perfil |
| F06 | E04 | Visualizar ou editar informações dos pets disponíveis |
| F07 | E03 | Enviar mensagem para anunciante |
| F08 | E03 | Enviar mensagem para adotante |
| F09 | E05 | Navegar pelo aplicativo com interação |
| F10 | E06 | Gerenciar conteúdo do aplicativo |
| F11 | E06 | Gerenciar usuários do aplicativo |
| F12 | E05 | Filtrar tipos de pets em um campo de busca |
| F13 | E05 | Compartilhar o card de um pet |
| F14 | E05 | Adotar ou anunciar um pet |



### História de usuário

| ID | Funcionalidade| Épico | Descrição |
| :-: | :-: | :-: | :- |
|  US01 | F01 | E01 | Eu, como usuário adodante, desejo me cadastar no sistema com meu e-mail|
|  US02 | F01 | E01 | Eu, como usuário anunciante, desejo me cadastar no sistema com meu e-mail ou instituição |
| US03 | F01 | E01 | Eu, como usuário adoante, desejo me cadastrar no sistema com contas de redes sociais |
| US04 | F02 | E01 | Eu, como usuário adotante, desejo entrar no sistema com meu e-mail e senha |
| US05 | F02 | E01 | Eu, como usuário anunciante, desejo entrar no sistema com meu e-mail e senha |
| US06 | F02 | E01 | Eu, como usuário adotante, desejo entrar no sistema com contas de redes sociais |
| US07 | F03 | E01 | Eu, como usuário adotante, desejo sair do sistema com um botão |
| US08 | F03 | E01 | Eu, como usuário anunciante, desejo sair do sistema com um botão |
| US09 | F04 | E02 | Eu, como usuário adotante, desejo visualizar meu perfil |
| US10 | F04 | E02 | Eu, como usuário anunciante, desejo visualizar meu perfil |
| US11 | F05 | E02 | Eu, como usuário adotante, desejo alterar a foto do meu perfil |
| US12 | F05 | E02 | Eu, como usuário adotante, desejo alterar o nome do meu perfil |
| US13 | F05 | E02 | Eu, como usuário adotante, desejo alterar o endereço do meu perfil |
| US14 | F05 | E02 | Eu, como usuário adotante, desejo alterar o telefone do meu perfil |
| US15 | F05 | E02 | Eu, como usuário adotante, desejo alterar o e-mail do meu perfil |
| US16 | F05 | E02 | Eu, como usuário anunciante, desejo alterar a foto do meu perfil |
| US17 | F05 | E02 | Eu, como usuário anunciante, desejo alterar o nome do meu perfil |
| US18 | F05 | E02 | Eu, como usuário anunciante, desejo alterar o endereço do meu perfil |
| US19 | F05 | E02 | Eu, como usuário anunciante, desejo alterar o telefone do meu perfil |
| US20 | F05 | E02 | Eu, como usuário anunciante, desejo alterar o e-mail do meu perfil |
| US21 | F06 | E04 | Eu, como usuário adotante, desejo visualizar as fotos do pet |
| US21 | F06 | E04 | Eu, como usuário adotante, desejo visualizar as informações de vacina/saúde do pet |
| US22 | F06 | E04 | Eu, como usuário anunciante, desejo adicionar ou editar as fotos do pet |
| US23 | F06 | E04 | Eu, como usuário anunciante, desejo adicionar ou editar as informações de vacina/saúde do pet |
| US24 | F07 | E03 | Eu, como usuário adotante, desejo enviar uma mensagem para o usuário anunciante |
| US25 | F08 | E03 | Eu, como usuário anunciante, desejo enviar uma mensagem para o usuário adotante |
| US26 | F09 | E05 | Eu, como usuário adotante, desejo navegar pelas páginas do aplicativo sem a necessidade de uma instrução |
| US27 | F09 | E05 | Eu, como usuário anunciante, desejo navegar pelas páginas do aplicativo sem a necessidade de uma instrução |
| US28 | F10 | E06 | Eu, como mantenedor do sistema, devo ser capaz de gerenciar publicações que não estão de acordo com as regras da comunidade |
| US29 | F11 | E06 | Eu, como mantenedor do sistema, devo ser capaz de gerenciar usuários que não estão seguindo as regras da comunidade |
| US30 | F12 | E05 | Eu, como usuário adotante, desejo filtrar os anúncios de pets pelo tipo (cachorro, gato e etc) |
| US31 | F12 | E05 | Eu, como usuário adotante, desejo filtrar os anúncios de pets por nome |
| US32 | F12 | E05 | Eu, como usuário adotante, desejo filtrar os anúncios de pets por idade do pet |
| US33 | F13 | E05 | Eu, como usuário adotante, desejo compartilhar o anúncio do pet |
| US34 | F13 | E05 | Eu, como usuário anunciante, desejo compartilhar o anúncio do pet |
| US35 | F14 | E05 | Eu, como usuário adotante, desejo adotar um pet de um usuário anunciante |

### Tarefas

| Épico | Funcionalidade | História de Usuário | Tarefas |
| :-: | :-: | :-: | :- |
| a | a | a | a |

