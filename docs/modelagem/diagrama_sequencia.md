# Diagrama de Sequência

## Histórico de Versões

| Data      | Versão | Modificação                         | Autor                       |
| :-------- | :----- | :---------------------------------- | :-------------------------- |
| 02/12/2022 | 0.1    | Criação e estruturação do documento | [Eduardo Maia Rezende](https://github.com/eduardomr) & [Kayro César Silva Machado](https://github.com/kayrocesar)|
| 04/12/2022 | 0.2    | Inclusão de diagrama do projeto | [Eduardo Maia Rezende](https://github.com/eduardomr) & [Kayro César Silva Machado](https://github.com/kayrocesar)|
| 04/12/2022 | 0.3    | Correção gramatical | [Thalisson Alves](https://github.com/Thalisson-Alves)|
| 29/01/2023 | 0.4   | Correção do diagrama | [Eduardo Maia](https://github.com/eduardomr) & [Herick Lima](https://github.com/hericklima22)|


## Introdução
 Um diagrama de sequência é um tipo de diagrama de interação que descreve a ordem e como um grupo de objetos trabalha em conjunto. Geralmente, é utilizado por desenvolvedores de software e profissionais de negócios para o entendimento de necessidades de um determinado sistema ou para documentação de um processo existente.


## Benefícios

- Representação de detalhes de um caso de uso UML

- Modelagem da lógica de um processo ou operação mais complexa

- Observação da interação de objetos e componentes uns com os outros

- Útil para o planejamento e compreensão de uma funcionalidade em um cenário existente ou futuro



## Componentes e Símbolos Básicos
 

| Simbolo |  Nome  |                                  Descrição                                     |
| :-----: | :----: | :------------------------------------------------------------------------------: |
|   <img src="https://raw.githubusercontent.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/master/docs/assets/diagrama_sequencia/object-symbol.PNG" alt="Objeto" width="150px"/>     | Objeto | Representa uma classe ou objetos em UML |
|   <img src="https://raw.githubusercontent.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/master/docs/assets/diagrama_sequencia/box-symbol.PNG" alt="Caixa de ativação" width="150px" height="200px"/>     | Caixa de ativação | Representa o tempo necessário para que um objeto conclua uma ação|
|   <img src="https://raw.githubusercontent.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/master/docs/assets/diagrama_sequencia/actor-symbol.PNG" alt="Ator" width="150px"/>     | Ator | Entidade que interage com o sistema |
|   <img src="https://raw.githubusercontent.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/master/docs/assets/diagrama_sequencia/package-symbol.PNG" alt="Pacote" width="150px"/>     | Pacote |Usada para conter elementos interativos do diagrama |
|   <img src="https://raw.githubusercontent.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/master/docs/assets/diagrama_sequencia/life-symbol.PNG" alt="Linha de vida" width="150px"/>     | Linha de vida |Representa a passagem do tempo, conforme segue para baixo  |
|   <img src="https://raw.githubusercontent.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/master/docs/assets/diagrama_sequencia/alternative-symbol.PNG" alt="Alternativo" width="150px"/>     | Alternativo | Simboliza uma escolha entre duas ou mais sequências de mensagens  |
|   <img src="https://raw.githubusercontent.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/master/docs/assets/diagrama_sequencia/synchronous-message-symbol.svg" alt=" Mensagem síncrona" width="150px"/>     | Mensagem síncrona |   Utilizado quando um remetente deve esperar por uma resposta a uma mensagem antes de poder continuar|
|   <img src="https://raw.githubusercontent.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/master/docs/assets/diagrama_sequencia/asynchronous-message-symbol.svg" alt=" Mensagem assíncrona" width="150px"/>     | Mensagem assíncrona |  Representa que o remetente pode continuar sem necessitar de uma resposta  |
|   <img src="https://raw.githubusercontent.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/master/docs/assets/diagrama_sequencia/uml-return-message-symbol.svg" alt=" Mensagem de retorno assíncrona" width="150px"/>     |  Mensagem de retorno assíncrona | Representa o retorno de mensagem  assíncrona|
|   <img src="https://raw.githubusercontent.com/UnBArqDsw2022-2/2022.2_G4_IdotPet/3458f394cfb51b22bfd7a6baab545a62b27ff0eb/docs/assets/diagrama_sequencia/uml-create-message-symbol.svg" alt="Assíncrono de criar mensagem" width="150px"/>     | Assíncrono de criar mensagem | Representa a criação de um novo objeto |
|   <img src="https://raw.githubusercontent.com/UnBArqDsw2022-2/2022.2_G4_IdotPet/3458f394cfb51b22bfd7a6baab545a62b27ff0eb/docs/assets/diagrama_sequencia/uml-return-message-symbol.svg" alt=" responder à mensagem" width="150px"/>     | Responder à mensagem | Representa respostas às chamadas  |
|   <img src="https://raw.githubusercontent.com/UnBArqDsw2022-2/2022.2_G4_IdotPet/3458f394cfb51b22bfd7a6baab545a62b27ff0eb/docs/assets/diagrama_sequencia/uml-deleted-message-symbol.svg" alt=" excluir mensagem" width="150px"/>     | Excluir mensagem | Representa a destruição de um objeto |



## Metodologia 
A partir de reuniões realizadas entre a equipe do projeto foram identificadas as interações entre os objetos do sistema. Após isto, o diagrama de sequência foi elaborado, com o intuito de mapear a jornada do usuário ao utilizar o produto que será desenvolvido, assim pudemos obter uma visão geral de alto nível das funcionalidades específicas do produto.
 

## Diagrama de Sequência

  ![Diagrama de Sequência](../assets/diagrama_sequencia/diag_sequencia_v2.png)
  <figcaption align="center" >Figura 1 - Diagrama de Sequência (Versão Atual). Fonte: Autores </figcaption>

  <details>
    <summary>Clique para apresentar versão anterior do diagrama</summary>
    <img src="https://raw.githubusercontent.com/UnBArqDsw2022-2/2022.2_G4_IdotPet/master/docs/assets/diagrama_sequencia/diag_sequencia_v1.png" alt="Diagrama de Sequência v1">
    <figcaption align="center" >Figura 1 - Diagrama de Sequência (Versão Anterior). Fonte: Autores </figcaption>
  </details>

## Referências



> LUCIDCHART. O que é um diagrama de sequência UML? Disponível em: https://www.lucidchart.com/pages/pt/o-que-e-diagrama-de-sequencia-uml. Acesso em: 02 de dez. de 2022.

> Modelo de Diagrama de Sequência UML Online | Exemplo editável. Disponível em: <https://miro.com/pt/modelos/diagrama-sequencia-uml/>. Acesso em: 4 dez. 2022.

> Tutorial do Diagrama de Sequência: Guia completo com exemplos. Disponível em: <https://creately.com/blog/pt/diagrama/tutorial-do-diagrama-de-sequencia/>.

‌
‌
