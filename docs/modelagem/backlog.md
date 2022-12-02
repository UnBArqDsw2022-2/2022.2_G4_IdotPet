# Backlog

## Histórico de Versões

| Data | Versão | Modificação | Autor |
| :- | :- | :- | :- |
|27/11/2022 | 0.1 | Criação e elaboração do documento | [Klyssmann Oliveira](https://github.com/klyssmannoliveira) & [Victor Cabral](https://github.com/victordscabral) |
|27/11/2022 | 0.2 | Atualização do documento | [Nicolas Roberto](https://github.com/Nicolas-Roberto)|
|30/11/2022 | 0.3 | Organização na ordem das Funcionalidades e Histórias | [Victor Cabral](https://github.com/victordscabral)|
|31/11/2022 | 0.4 | Correções gramaticais | [Victor Cabral](https://github.com/victordscabral)|
|01/12/2022 | 0.5 | Atualização nas Tarefas e História de Usuário | [Victor Cabral](https://github.com/victordscabral) & [Nicolas Roberto](https://github.com/Nicolas-Roberto) & [Klyssmann Oliveira](https://github.com/klyssmannoliveira) |

## Introdução 

Este backlog foi produzido de acordo com a abordagem ágil, na qual uma função geral é classificada como “Épico”. Desse épico derivam as “Funcionalidades”, que são como divisões de funcionalidades menores ainda, as "Histórias de usuário" que são partes mais detalhadas de uma funcionalidade, e por último teremos as "Tarefas" que terão uma descrição mais técnica.
  
## Metodologia

Esse documento foi elaborado a partir dos vários artefatos de elicitação de requisitos nas sprints anteriores. Como dito anteriormente, o Backlog do produto pode ser alterado durante a evolução do projeto. 

No presente documento, o backlog do produto seguirá a hierarquia exposto na Fig. 1, onde será composto por uma coleção de histórias de usuário, possuindo de 1 até N histórias. Em muitos times não se utiliza épicos, desta maneira a hierarquia permite que o backlog possua 0 a N épicos. Cada épico pode ser relacionado com 0 ou N funcionalidade, que por sua vez, cada funcionalidade se relaciona com 0 ou mais Histórias de Usuário. Finalizando, cada história produz 0 a N tarefas técnicas.

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/doc/%2362-Backlog-produto/docs/assets/backlog/backlog_hierarquia.png" alt="Hierarquia do Backlog"/>
  <figcaption align="center" >Figura 1 - Hierarquia do Backlog. Fonte: Autores </figcaption>
</figure>


**Épico** (*Epic*) = É uma história de usuário que ainda não foi detalhada, é muito grande ou ainda possui muita incerteza. É a categoria com maior granularidade no backlog.

**Funcionalidade** (Feature) - Verbos no infinitivo que descrevem melhor as responsabilidades da aplicação.

**História de usuário** (*User Story - US*) - É um formato sucinto para escrita dos requisitos necessários para construção de um produto. Assim, uma história de usuário deve ser compreensível para clientes e consumidores.

**Tarefas** (*Tasks*) - São as especificações dos itens técnicos necessários para que uma História de Usuário se transforme em um incremento do produto.

**Moscow** (*Priorização*) - É uma técnica onde você deverá atribuir um das quatro letras M,S,C ou W e cada uma delas tem um significado diferente. M de **MUST** (*TEM*),é um item que tem que ser feito, S de **SHOULD,** (*DEVE*) que é algo importante, C de **COULD** (*PODERIA*) que é algo desejável e W de **WONT** (*NÃO*) para itens que não agregam muito valor.

### Épicos

|ID | Descrição resumida | Descrição
| :-: | :- | :- |
| E01 | Cadastro | Eu, enquanto usuário, desejo realizar um cadastro no aplicativo |
| E02 | Perfil | Eu, enquanto usuário, desejo configurar o meu perfil no aplicativo |
| E03 | Contato | Eu, enquanto usuário, desejo um meio de contato com outros usuários |
| E04 | Visualização | Eu, enquanto usuário, desejo visualizar informações sobre os animais disponíveis para adoção |
| E05 | Edição | Eu, enquanto usuário, desejo editar informações dos animais que disponibilizei para adoção |
| E06 | Interação | Eu, enquanto usuário, desejo interagir com o aplicativo |
| E07 | Gerenciamento | Eu, enquanto gerenciador do aplicativo, desejo ter controle do conteúdo do aplicativo |


### Funcionalidades

| ID | Épico | Descrição |
| :-: | :-: | :-- |
| F01 | E01 | Cadastrar no sistema |
| F02 | E01 | Entrar no sistema (Login) |
| F03 | E01 | Sair do sistema (Logout) |
| F04 | E02 | Visualizar perfil |
| F05 | E02 | Editar informações do perfil |
| F06 | E03 | Enviar mensagem para anunciante |
| F07 | E03 | Enviar mensagem para adotante |
| F08 | E04 | Visualizar anúncio e informações dos pets disponíveis |
| F09 | E05 | Adicionar e editar anúncio e informações dos pets anunciados |
| F10 | E06 | Navegar pelo aplicativo com interação |
| F11 | E06 | Filtrar tipos de pets em um campo de busca |
| F12 | E06 | Compartilhar o card de um pet |
| F13 | E06 | Adotar ou anunciar um pet |
| F14 | E07 | Gerenciar conteúdo do aplicativo |
| F15 | E07 | Gerenciar usuários do aplicativo |

### História de usuário

|  ID  | Épico | Funcionalidade | Descrição                                                                                                                                                                 |
| :--: | :---: | :------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| US01 |  E01  |      F01       | Eu, como usuário adodante, desejo me cadastrar no sistema com meu e-mail, para usurfruir do sistema                                                                       |
| US02 |  E01  |      F01       | Eu, como usuário anunciante, desejo me cadastrar no sistema com meu e-mail ou instituição, para me associar a conta                                                       |
| US03 |  E01  |      F01       | Eu, como usuário adotante, desejo me cadastrar no sistema com contas de redes sociais, para facilitar o cadastro                                                          |
| US04 |  E01  |      F02       | Eu, como usuário adotante, desejo entrar no sistema com meu e-mail e senha, para manter minha conta privada                                                               |
| US05 |  E01  |      F02       | Eu, como usuário anunciante, desejo entrar no sistema com meu e-mail e senha, para manter minha conta privada                                                             |
| US06 |  E01  |      F02       | Eu, como usuário adotante, desejo entrar no sistema com contas de redes sociais, para facilitar o login                                                                   |
| US07 |  E01  |      F02       | Eu, como usuário anunciante, desejo entrar no sistema com contas de redes sociais, para facilitar o login                                                                 |
| US08 |  E01  |      F03       | Eu, como usuário adotante, desejo deslogar minha conta com um botão, facilitando minha saida do sistema                                                                   |
| US09 |  E01  |      F03       | Eu, como usuário anunciante, desejo deslogar minha conta com um botão, facilitando minha saida do sistema                                                                 |
| US10 |  E02  |      F04       | Eu, como usuário adotante, desejo visualizar meu perfil, para verificar meus dados                                                                                        |
| US11 |  E02  |      F04       | Eu, como usuário anunciante, desejo visualizar meu perfil, verificar meus dados                                                                                           |
| US12 |  E02  |      F05       | Eu, como usuário adotante, desejo alterar informações do meu perfil, para corrigir meus dados                                                                             |
| US13 |  E02  |      F05       | Eu, como usuário anunciante, desejo alterar informações do meu perfil, para corrigir meus dados                                                                           |
| US14 |  E03  |      F06       | Eu, como usuário adotante, desejo enviar uma mensagem para o usuário anunciante, para me comunicar com o anunciante                                                       |
| US15 |  E03  |      F07       | Eu, como usuário anunciante, desejo enviar uma mensagem para o usuário adotante, para me comunicar com o adotante                                                         |
| US16 |  E04  |      F08       | Eu, como usuário adotante, desejo visualizar o anúncio do pet, para escolher um pet                                                                                       |
| US17 |  E04  |      F08       | Eu, como usuário adotante, desejo visualizar as perfil/informações do pet, para conhecer o pet                                                                            |
| US18 |  E05  |      F09       | Eu, como usuário anunciante, desejo adicionar ou editar o anúncio do pet, para corrigir os dados do anúncio                                                               |
| US19 |  E05  |      F09       | Eu, como usuário anunciante, desejo adicionar ou editar o perfil/informações do pet, para corrigir os dados do pet                                                        |
| US20 |  E06  |      F10       | Eu, como usuário adotante, desejo saber como realizar uma adoção, sobre como o aplicativo funciona e da importância de uma adoção, para entender como usar o aplicativo   |
| US21 |  E06  |      F10       | Eu, como usuário anunciante, desejo saber como anunciar uma adoção, sobre como o aplicativo funciona e da importância de uma adoção, para entender como usar o aplicativo |
| US22 |  E06  |      F11       | Eu, como usuário adotante, desejo filtrar os anúncios de pets por nome, para para facilitar a escolha de um pet                                                           |
| US23 |  E06  |      F11       | Eu, como usuário adotante, desejo filtrar os anúncios de pets pelo tipo (cachorro, gato e etc), para facilitar a escolha de um pet                                        |
| US24 |  E06  |      F11       | Eu, como usuário adotante, desejo filtrar os anúncios de pets por data do anúncio,para facilitar a escolha de um pet                                                      |
| US25 |  E06  |      F12       | Eu, como usuário adotante, desejo compartilhar o anúncio do pet, para aumentar a visibilidade do aplicativo                                                               |
| US26 |  E06  |      F12       | Eu, como usuário anunciante, desejo compartilhar o anúncio do pet, para aumentar a visibilidade do aplicativo                                                             |
| US27 |  E06  |      F13       | Eu, como usuário adotante, desejo adotar um pet de um usuário anunciante, para realizar o propósito do aplicativo                                                         |
| US28 |  E07  |      F14       | Eu, como mantenedor do sistema, devo ser capaz de gerenciar publicações que não estão de acordo com as regras da comunidade, para garantir que não tenham publicações que fogem dos valores da comunidade       |
| US29 |  E07  |      F15       | Eu, como mantenedor do sistema, devo ser capaz de gerenciar usuários que não estão seguindo as regras da comunidade, para garantir que não tenham usuários maliciosos               |

