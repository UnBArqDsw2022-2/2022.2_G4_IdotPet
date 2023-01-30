# Diagrama de Comunicação 

## Histórico de Versões

| Data | Versão | Modificação | Autor |
| :- | :- | :- | :- |
| 30/11/2022 | 0.1 | Elaboração do Diagrama | [Thalisson Alves](https://github.com/Thalisson-Alves) & [Luan Cavalcante](https://github.com/Luan-Cavalcante)|
| 02/12/2022 | 0.2 | Elaboração da Introdução e Metodologia | [Thalisson Alves](https://github.com/Thalisson-Alves) & [Luan Cavalcante](https://github.com/Luan-Cavalcante)|
| 02/12/2022 | 0.2 | Elaboração da Conclusão e Referências | [Thalisson Alves](https://github.com/Thalisson-Alves) & [Luan Cavalcante](https://github.com/Luan-Cavalcante)|
| 03/12/2022 | 0.3 | Revisão do documento | [João Durso](https://github.com/jvsdurso) & [Vitor Kühl](https://github.com/vitorekr) |

## Introdução

O Diagrama de Comunicação, também conhecido como Diagrama de Colaboração em versões do UML anteriores a 2.0, define como os objetos interagem para executar um caso de uso ou parte de um caso de uso específico. Esse Diagrama fornece uma visão alternativa das mesmas informações dos Diagramas de Sequência, porém com o foco na estrutura das mensagens transmitidas entre os objetos que fazem parte da interação ao invés da ordem temporal das mensagens.

Os Diagramas de Comunicação são representados através de alguns elementos, são eles:

### Objetos

Os objetos geralmente são representados por retângulos que mostram seu nome e sua classe separados por dois-pontos.

É possível omitir a classe ou o nome do objeto, porém caso seja necessário diferenciar objetos de uma mesma classe é importante ter ambos.

### Atores

Os atores, ou agentes, geralmente representam o início da interação e são representados por um boneco-palito.

### Vínculos

Os vínculos são ligações entre objetos ou atores envolvidos no processo. São caracterizados pelo envio e/ou recebimento de mensagens. São representados por linhas contínuas que unem 2 objetos ou 2 atores ou 1 objeto e 1 ator.

### Mensagens

As mensagens são comunicações entre instâncias em uma interação. Elas possuem uma mensagem, geralmente representa chamada de métodos, e uma seta próxima a um *vínculo*. Significando que o *vínculo* será usado para entregar a mensagem de uma instância à outra, seguindo a direção da seta. A mensagem pode possuir um número indicando a sequência em que as mensagens são trafegadas na interação.

## Metodologia

Para a elaboração dos diagramas, foi utilizado a ferramenta *LucidChart*, pois ela possui suporte aos diferentes componentes que compõem a notação UML. Os diagramas foram escolhidos de forma a representar os principais fluxos do usuário dentro do aplicativo.

## Resultados

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/diagrama_comunicacao/diagrama_comunicacao1.png?raw=true" alt="Diagrama de Comunicação"/>
  <figcaption align="center" >Figura 1 - Diagrama de Comunicação. Fonte: Autores </figcaption>
</figure>

<!--- ## Conclusão 

Com os diagramas apresentados acima conseguimos sintetizar os fluxos principais do aplicativo e das comunicações entre os diferentes objetos, o que facilitará o desenvolvimento do software em questão.
--->

## Referências

> DIRETRIZ: Diagrama de Comunicação. [S. l.], 2006?. Disponível em: https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/guidances/guidelines/communication_diagram_FFFEA1B5.html. Acesso em: 2 dez. 2022.

> JUNIOR, Geraldo Braz. Diagrama de Comunicação. [S. l.], [20--]. Disponível em: http://www.deinf.ufma.br/~geraldo/dob/10.Comunicacao.pdf. Acesso em: 2 dez. 2022.
