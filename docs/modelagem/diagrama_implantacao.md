# Diagrama de Implantação

## Histórico de Versões

| Data | Versão | Modificação | Autor |
| :- | :- | :- | :- |
| 30/11/2022 | 0.1 | Criação  e elaboração do documento | [Klyssmann Oliveira](https://github.com/klyssmannoliveira) & [Victor Cabral](https://github.com/victordscabral) & [Nicolas Roberto](https://github.com/Nicolas-Roberto)|
| 30/11/2022 | 0.2 | Introdução e Metodologia | [Klyssmann Oliveira](https://github.com/klyssmannoliveira) & [Victor Cabral](https://github.com/victordscabral) & [Nicolas Roberto](https://github.com/Nicolas-Roberto)|
| 30/11/2022 | 0.3 | Adição do diagrama de implementação | [Klyssmann Oliveira](https://github.com/klyssmannoliveira) & [Victor Cabral](https://github.com/victordscabral) & [Nicolas Roberto](https://github.com/Nicolas-Roberto)|
| 04/12/2022 | 0.4 | Correção ortográfica | [Pedro Cassiano](https://github.com/PedroLucasCMa)|

## Introdução

O diagrama de implantação descreve a implantação física das informações geradas pelo programa de software nos componentes de hardware. A informação que o software gera é chamada de artefato. Os diagramas de implantação são compostos de várias formas UML. As caixas tridimensionais, conhecidas como nós, representam os elementos básicos de software ou hardware, ou nós, no sistema. Linhas de nó a nó indicam relacionamentos e as formas menores contidas nas caixas representam os artefatos de software implantados.

Estes diagramas apresentam as seguintes vantagens:

- Mostrar os elementos de software são implantados por quais elementos de hardware.
- Ilustrar o processamento de tempo de execução para hardware.
- Fornecer uma visão da topologia do sistema de hardware.

## Componentes Básicos

**Artefato**: Produto desenvolvido pelo software, simbolizado por um retângulo com o nome e a palavra “artefato” delimitados por setas duplas.
**Associação**: Uma linha que indica uma mensagem ou outro tipo de comunicação entre nós.
**Componente**: Um retângulo com duas guias que indica um elemento de software.
**Dependência**: Uma linha tracejada que termina em uma seta, o que indica que um nó ou componente é dependente de outro.
**Interface**: Um círculo que indica uma relação contratual. Esses objetos que realizam a interface devem cumprir algum tipo de obrigação.
**Nó**: Um objeto de hardware ou software, mostrado por uma caixa tridimensional.
**Nó como contêiner**: um nó que contém outro nó dentro dele onde os nós contêm componentes.
**Estereótipo**: Um dispositivo contido no nó, apresentado na parte superior do nó, com o nome entre colchetes por setas duplas.

## Metodologia 

Foi realizado uma reunião via discord com a participação dos autores do documento. Assim, foi realizado um estudo dos artefatos de tecnologia e uma discussão com os membros mais experientes nas tecnologias escolhidas e nos requisitos do projeto. Para a construção do diagrama de implantação foi utilizada a ferramenta LucidChart.


## Diagrama de Implantação

<img src="https://raw.githubusercontent.com/UnBArqDsw2022-2/2022.2_G4_IdotPet/master/docs/assets/deployment_diagram.jpg" alt="Deployment Diagram" /> 
 <figcaption align="center" >Figura 1 - Diagrama de implementação. Fonte: Autores </figcaption>

## Referências

> LUCIDCHART. Deployment Diagram Tutorial.LucidChart. Disponível em: https://www.lucidchart.com/pages/uml-deployment-diagram. Acesso em: 30 de nov. de 2022.

> PLUTORA. Deployment Diagrams Explained in Detail, With Examples. Disponível em: https://www.plutora.com/blog/deployment-diagrams-explained-in-detail-with-examples. Acesso em: 30 de nov. de 2022.
