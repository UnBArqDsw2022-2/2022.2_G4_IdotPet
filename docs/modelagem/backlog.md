# Backlog

## Histórico de Versões

| Data | Versão | Modificação | Autor |
| :- | :- | :- | :- |
|27/11/2022 | 0.1 | Criação e elaboração do documento | [Klyssmann Oliveira](https://github.com/klyssmannoliveira) & [Victor Cabral](https://github.com/victordscabral) |
|27/11/2022 | 0.2 | Atualização do documento | [Nicolas Roberto](https://github.com/Nicolas-Roberto)|
|30/11/2022 | 0.3 | Organização na ordem das Funcionalidades e Histórias | [Victor Cabral](https://github.com/victordscabral)|
|31/11/2022 | 0.4 | Correções gramaticais | [Victor Cabral](https://github.com/victordscabral)|
|01/12/2022 | 0.5 | Atualização nas Tarefas e História de Usuário | [Victor Cabral](https://github.com/victordscabral) & [Nicolas Roberto](https://github.com/Nicolas-Roberto) & [Klyssmann Oliveira](https://github.com/klyssmannoliveira) |
|03/12/2022 | 0.6 | Adição da prioridade | [Victor Cabral](https://github.com/victordscabral) & [Nicolas Roberto](https://github.com/Nicolas-Roberto) & [Klyssmann Oliveira](https://github.com/klyssmannoliveira) |
|03/12/2022 | 0.7 | Adição da rastreabilidade | [Victor Cabral](https://github.com/victordscabral) & [Nicolas Roberto](https://github.com/Nicolas-Roberto) & [Klyssmann Oliveira](https://github.com/klyssmannoliveira) |
|03/12/2022 | 0.8 | Adição dos requisitos não funcionais | [Victor Cabral](https://github.com/victordscabral) & [Nicolas Roberto](https://github.com/Nicolas-Roberto) & [Klyssmann Oliveira](https://github.com/klyssmannoliveira) |

## Introdução

Este backlog foi produzido de acordo com a abordagem ágil, na qual uma função geral é classificada como “Épico”. Desse épico derivam as “Funcionalidades”, que são como divisões de funcionalidades menores ainda, as "Histórias de usuário" que são partes mais detalhadas de uma funcionalidade, e por último teremos as "Tarefas" que terão uma descrição mais técnica.
  
## Metodologia

Esse documento foi elaborado a partir dos vários artefatos de elicitação de requisitos nas sprints anteriores. Como dito anteriormente, o Backlog do produto pode ser alterado durante a evolução do projeto.

No presente documento, o backlog do produto seguirá a hierarquia exposto na Fig. 1, onde será composto por uma coleção de histórias de usuário, possuindo de 1 até N histórias. Em muitos times não se utiliza épicos, desta maneira a hierarquia permite que o backlog possua 0 a N épicos. Cada épico pode ser relacionado com 0 ou N funcionalidade, que por sua vez, cada funcionalidade se relaciona com 0 ou mais Histórias de Usuário. Finalizando, cada história produz 0 a N tarefas técnicas.

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/backlog/backlog_hierarquia.jpeg?raw=true" alt="Hierarquia do Backlog"/>
  <figcaption align="center" >Figura 1 - Hierarquia do Backlog. Fonte: Autores </figcaption>
</figure>

**Épico** (*Epic*) = É uma história de usuário que ainda não foi detalhada, é muito grande ou ainda possui muita incerteza. É a categoria com maior granularidade no backlog.

**Funcionalidade** (Feature) - Verbos no infinitivo que descrevem melhor as responsabilidades da aplicação.

**História de usuário** (*User Story - US*) - É um formato sucinto para escrita dos requisitos necessários para construção de um produto. Assim, uma história de usuário deve ser compreensível para clientes e consumidores.

**Tarefas** (*Tasks*) - São as especificações dos itens técnicos necessários para que uma História de Usuário se transforme em um incremento do produto.

**Moscow** (*Priorização*) - É uma técnica onde você deverá atribuir um das quatro letras M,S,C ou W e cada uma delas tem um significado diferente. M de **MUST** (*TEM*),é um item que tem que ser feito, S de **SHOULD,** (*DEVE*) que é algo importante, C de **COULD** (*PODERIA*) que é algo desejável e W de **WONT** (*NÃO*) para itens que não agregam muito valor.

### Épicos

|ID | Descrição resumida | Épico
| :-: | :- | :- |
| E01 | Cadastro | Eu, enquanto usuário, desejo realizar um cadastro no aplicativo |
| E02 | Perfil | Eu, enquanto usuário, desejo configurar o meu perfil no aplicativo |
| E03 | Contato | Eu, enquanto usuário, desejo um meio de contato com outros usuários |
| E04 | Visualização | Eu, enquanto usuário, desejo visualizar informações sobre os animais disponíveis para adoção |
| E05 | Edição | Eu, enquanto usuário, desejo editar informações dos animais que disponibilizei para adoção |
| E06 | Interação | Eu, enquanto usuário, desejo interagir com o aplicativo |
| E07 | Gerenciamento | Eu, enquanto gerenciador do aplicativo, desejo ter controle do conteúdo do aplicativo |
| E08 | Doação | Eu, enquanto usuário, desejo realizar doações para a comunidade |

### Funcionalidades

| ID | Épico | Funcionalidade|
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
| F16 | E06 | Favoritar o anúncio de um pet |
| F17 | E08 | Doar para a comunidade |

### História de usuário

|  ID  | Épico | Funcionalidade | História de usuário | MoSCoW | Rastreabilidade |
| :--: | :---: | :------------: | :----- | :--: | :--: |
| US01 |  E01  | F01 | Eu, como usuário adodante, desejo me cadastrar no sistema com meu e-mail, para usurfruir do sistema | M | [BS06](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) |
| US02 |  E01  | F01 | Eu, como usuário anunciante, desejo me cadastrar no sistema com meu e-mail ou instituição, para me associar a conta  | M | [BS06](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) e [IN07](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/introspeccao)|
| US03 |  E01  | F01 | Eu, como usuário adotante, desejo me cadastrar no sistema com contas de redes sociais, para facilitar o cadastro  | C | [BS06](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm)|
| US04 |  E01  | F02 | Eu, como usuário adotante, desejo entrar (logar) no sistema com meu e-mail e senha, para manter minha conta privada  | M | [BS09](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm)|
| US05 |  E01  | F02 | Eu, como usuário anunciante, desejo entrar (logar) no sistema com meu e-mail e senha, para manter minha conta privada   | M | [BS09](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm)|
| US06 |  E01  | F02 | Eu, como usuário adotante, desejo entrar (logar) no sistema com contas de redes sociais, para facilitar o login    | C | [BS09](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm)|
| US07 |  E01  | F02 | Eu, como usuário anunciante, desejo entrar (logar) no sistema com contas de redes sociais, para facilitar o login   | C | [BS09](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm)|
| US08 |  E01  | F03 | Eu, como usuário adotante, desejo sair (deslogar) minha conta com um botão, facilitando minha saida do sistema    | M | [BS09](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm)|
| US09 |  E01  | F03 | Eu, como usuário anunciante, desejo sair (deslogar) minha conta com um botão, facilitando minha saida do sistema   | M | [BS09](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm)|
| US10 |  E02  | F04 | Eu, como usuário adotante, desejo visualizar meu perfil, para verificar meus dados    | S | [BS16](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) e [BS17](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm)|
| US11 |  E02  | F04 | Eu, como usuário anunciante, desejo visualizar meu perfil, verificar meus dados    | S | [BS16](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) e [BS17](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm)|
| US12 |  E02  | F05 | Eu, como usuário adotante, desejo alterar informações do meu perfil, para corrigir meus dados   | M | [BS18](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm)|
| US13 |  E02  | F05 | Eu, como usuário anunciante, desejo alterar informações do meu perfil, para corrigir meus dados   | M | [BS18](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm)|
| US14 |  E03  | F06 | Eu, como usuário adotante, desejo enviar uma mensagem para o usuário anunciante, para me comunicar com o anunciante   | M | [BS02](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm), [BS07](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) e [IN03](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/introspeccao)|
| US15 |  E03  | F07 | Eu, como usuário anunciante, desejo enviar uma mensagem para o usuário adotante, para me comunicar com o adotante  | M | [BS02](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm), [BS07](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) e [IN03](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/introspeccao)|
| US16 |  E04  | F08 | Eu, como usuário adotante, desejo visualizar o anúncio do pet, para escolher um pet  | M | [BS19](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm)|
| US17 |  E04  | F08 | Eu, como usuário adotante, desejo visualizar as perfil/informações do pet, para conhecer o pet   | S | [BS19](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm)|
| US18 |  E05  | F09 | Eu, como usuário anunciante, desejo adicionar ou editar o anúncio do pet, para adicionar um novo anúncio ou corrigir os dados  | M | [BS01](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm), [BS04](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm), [BS10](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) e [IN01](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/introspeccao)|
| US19 |  E05  | F09 | Eu, como usuário anunciante, desejo adicionar ou editar o perfil/informações do pet, para corrigir os dados do pet   | S | [BS04](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) e [BS10](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) |
| US20 |  E06  | F10 | Eu, como usuário adotante, desejo saber como realizar uma adoção, sobre como o aplicativo funciona e da importância de uma adoção, para entender como usar o aplicativo | C | [BS20](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm), [BS21](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) e [BS22](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm)|
| US21 |  E06  | F10 | Eu, como usuário anunciante, desejo saber como anunciar uma adoção, sobre como o aplicativo funciona e da importância de uma adoção, para entender como usar o aplicativo | C | [BS20](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm), [BS21](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) e [BS22](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm)|
| US22 |  E06  | F11 | Eu, como usuário adotante, desejo filtrar os anúncios de pets por tipo (cachorro, gato e etc), para para facilitar a escolha de um pet  | S | [BS08](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm), [IN02](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/introspeccao) e [IN05](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/introspeccao)|
| US23 |  E06  | F11 | Eu, como usuário adotante, desejo filtrar os anúncios de pets pelo localização do animal, para facilitar a escolha de um pet   | S | [BS08](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm), [IN02](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/introspeccao) e [IN05](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/introspeccao)|
| US24 |  E06  | F11 | Eu, como usuário adotante, desejo filtrar os anúncios de pets por data do anúncio, para facilitar a escolha de um pet   | S | [BS08](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm), [IN02](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/introspeccao) e [IN05](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/introspeccao)|
| US25 |  E06  | F12 | Eu, como usuário adotante, desejo compartilhar o anúncio do pet, para aumentar a visibilidade do aplicativo  | C | [BS23](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) e [IN06](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/introspeccao)|
| US26 |  E06  | F12 | Eu, como usuário anunciante, desejo compartilhar o anúncio do pet, para aumentar a visibilidade do aplicativo  | C | [BS23](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) e [IN06](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/introspeccao)|
| US27 |  E06  | F13 | Eu, como usuário adotante, desejo adotar um pet de um usuário anunciante, para realizar o propósito do aplicativo | M | [BS11](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) |
| US28 |  E07  | F14 | Eu, como mantenedor do sistema, devo ser capaz de gerenciar publicações que não estão de acordo com as regras da comunidade, para garantir que não tenham publicações que fogem dos valores da comunidade  | M | [BS24](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm)|
| US29 |  E07  | F15 | Eu, como mantenedor do sistema, devo ser capaz de gerenciar usuários que não estão seguindo as regras da comunidade, para garantir que não tenham usuários maliciosos  | M | [BS24](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm)|
| US30 |  E06  | F16 | Eu, como usuário adotante, desejo favoritar o anúncio de um pet, para ter acesso aos meus interesses rapidamente | C | [BS03](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) e [IN07](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/introspeccao)|
| US31 |  E08  | F17 | Eu, como usuário voluntário, desejo doar recursos para um usuário adotante, para fornecer condições necessárias para a adoção e apoio dos pets | C | [BS12](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) e [IN04](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/introspeccao)
| US32 |  E08  | F17 | Eu, como usuário voluntário, desejo doar recursos para um usuário anunciante, para fornecer condições necessárias para o pet até sua adoção | C | [BS12](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) e [IN04](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/introspeccao)|

### Tarefas

| Épico | Funcionalidade | História de Usuário | Tarefas |
| :-: | :-: | :-: | :- |
| E01 | F01 | US01, US02 e US03 | - Criar seção de cadastro <br> - Disponibilizar botão de cadastro na seção inicial <br> - Disponibilizar opção de cadastrar por contas de redes sociais <br> - Disponibilizar campos para informe do email e senha <br> - Disponibilizar campo para repetir a senha <br> - Disponibilizar campos para informe de nome, endereço e telefone <br> - Disponibilizar função para upload de foto do perfil <br> - Disponibilizar botão de confirmação do cadastro|
| E01 | F02 | US04, US05, US06 e US07 | - Criar seção de login <br> - Disponibilizar opção de logar por contas de redes sociais <br> - Disponibilizar campos para informe do email e senha <br> - Disponibilizar botão de confirmação do login|
| E01 | F03 | US08 e US09 | - Criar seção de configurações <br> - Disponibilizar botão para deslogar da conta na seção de configurações <br> - Perguntar se o usuário deseja realmente deslogar fornecendo botões para confirmar e cancelar a operação|
| E02 | F04 | US10 e US11 | - Criar seção de perfil <br> - Disponibilizar informações de foto, nome, endereço, telefone e e-mail do usuário na seção de perfil <br> - Disponibilizar o(s) pet(s) com suas informações na qual o usuário anunciou para adoção|
| E02 | F05 | US12 e US13 | - Criar seção de perfil <br> - Disponibilizar botão para editar informações de foto, nome, endereço, telefone e e-mail do usuário na seção de perfil <br> - Disponibilizar botão para editar informaçõe do(s) pet(s) que o usuário anunciou para adoção |
| E03 | F06 | US14 e US15 | - Criar seção com todos os chats iniciados <br> - Criar seção para o chat entre usuário adotante e anunciante <br> - Criar botão no anúncio do pet para iniciar conversa com o usuário anunciante <br> - Informar quando houver e a quantidade de novas mensagens recebidas pelo usuário na seção de chats iniciados<br> - Disponibilizar nome e foto do contato <br> - Disponibilizar função para expandir informações do contato quando na seção de chat <br> - Disponibilizar campo para enviar mensagens <br> - Disponibilizar histórico da conversa |
| E04 | F08 | US16, US17 e US30| - Criar seção de anúncio dos pets <br> - Disponibilizar os anúncios com o perfil resumido (foto, nome e características) do pet para o usuário <br> - Disponibilizar função para entrar no perfil do pet <br> - Disponibilizar função de favoritar o anúncio do pet<br> - Disponibilizar função de doação no anúncio<br> - Disponibilizar informações mais detalhadas do pet como fotos, nome, características, saúde, vacinas, situação, resumo e perfil do anunciante|
| E05 | F09 | US18 e US19 | - Criar seção para cadastrar o anúncio dos pets <br> - Disponibilizar campos para informar nome, características, saúde, vacinas, situação e resumo do pet <br> - Disponibilizar função para upload de fotos do pet <br> - Disponibilizar função para upload de fotos do cartão de vacina <br> - Disponibilizar opções de edição, personalização e remoção do perfil do pet|
| E06 | F10 | US20 e US21 | - Criar seção de explicação do aplicativo <br> - Informar sobre o processo de adotar <br> - Informar sobre o processo de anunciar uma adoção <br> - Informar sobre o aplicativo e seu funcionamento <br> - Informar sobre a importância de uma adoção|
| E06 | F11 | US22, US23 e US24 | - Disponibilizar campo para filtrar os pets na seção de anúncios <br> - Disponibilizar opção de filtragem por nome, tipo e/ou data de início|
| E06 | F12 | US25 e US26 | - Disponibilizar um botão para compartilhar um pet da seção de anúncio e perfil do pet <br> - Disponibilizar um botão para compartilhar o pet do anunciante que foi cadastrado para adoção|
| E06 | F13 | US27 | - Disponibilizar botão para informar interesse na adoção no perfil do pet <br> - Informar o interesse da adoção para o anunciante via mensagem autómatica no chat ao clicar no botão <br> - Criar seção de termo de responsibilidade ao adotar <br> - Redirecionar o adotante para a seção do termo de responsabilidade antes de confirmar a adoção|
| E07 | F14 e F15| US28 e US29 | - Criar seção de gerenciar publicações para o mantenedor do sistema <br> - Disponibilizar função de o mantenedor entrar em contato com o anunciante <br> - Disponibilizar a função para o mantenedor de excluir publicações <br> - Disponibilizar a função para o mantenedor de excluir usuários|
| E08 | F17 | US31 e US32 | - Criar seção de doações <br> - Disponibilizar função de doação para anunciantes <br> - Disponibilizar função de doação para a comunidade|

### Requisitos Não Funcionais

| ID | Descrição | Tipo de requisito | MoSCoW | Rastreabilidade |
|:-: | :- | :-: | :--: | :--: |
| BS13 | O app deve ser mobile | RNF |  M | [BS13](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) |
| BS14 | O usuário deve conseguir utilizar o app sem treinamento específico | RNF | C | [BS14](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) |
| BS15 | O sistema deverá rodar em Android | RNF | M | [BS15](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) |
| BS16 | O sistema deverá rodar em IOS | RNF | S | [BS15](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) |
| BS25 | O aplicativo deve proteger os dados dos usuários. | RNF | S |[BS25](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) | [BS15](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) |
| BS26 | O aplicativo deverá possuir uma cobertura de testes maior do que 70%.  | RNF | C |[BS26](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) |
| BS27 | O aplicativo deverá possuir documentação legivel e compreensivel sobre a instalação e as boas praticas de desenvolvimento.  | RNF | M |[BS27](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) |
| BS28 | O aplicativo deve ter uma interface coerente com padrão de cores e ícones. | RNF | C |[BS28](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) |
| BS29 | O aplicativo deve ser intuitivo e de fácil utilização. Com layouts semelhantes à aplicações de mídias sociais já estabelecidas.  | RNF | C |[BS29](https://unbarqdsw2022-2.github.io/2022.2_G4_IDotPet/#/base/brainstorm) |

### Referências

> ATLASSIAN. O backlog do produto: sua lista de tarefas definitiva. Disponível em:<https://www.atlassian.com/br/agile/scrum/backlogs>.  Acesso em: 28 nov. 2022.

> FERREIRA, Avelino. K21. Product Backlog: Épico, História de Usuário e Tarefas. Disponível em: <https://k21.global/br/blog/product-backlog-epico-historia-tarefas>.  Acesso em: 28 nov. 2022.
