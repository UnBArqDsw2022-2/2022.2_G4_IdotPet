# Diagrama de Componentes

## Histórico de Versão
| Versão | Data | Modificação | Autor(es) | Revisores |
|:-:|:-:|:-:|:-:|:-:|
| 0.1 | 03/12/2022 | Criação e elaboração do documento | [Vitor Kühl](https://github.com/vitorekr) & [João Durso](https://github.com/jvsdurso)| [Thalisson Alves](https://github.com/Thalisson-Alves) & [Luan Cavalcante](https://github.com/Luan-Cavalcante) |
| 0.2 | 03/12/2022 | Adição da introdução e da metodologia | [Vitor Kühl](https://github.com/vitorekr) & [João Durso](https://github.com/jvsdurso)| [Thalisson Alves](https://github.com/Thalisson-Alves) & [Luan Cavalcante](https://github.com/Luan-Cavalcante) |
| 0.3 | 03/12/2022 | Adição de referências | [Vitor Kühl](https://github.com/vitorekr) & [João Durso](https://github.com/jvsdurso)| [Thalisson Alves](https://github.com/Thalisson-Alves) & [Luan Cavalcante](https://github.com/Luan-Cavalcante) |
| 0.4 | 04/12/2022 | Adição do artefato | [Vitor Kühl](https://github.com/vitorekr) & [João Durso](https://github.com/jvsdurso)| [Thalisson Alves](https://github.com/Thalisson-Alves) & [Luan Cavalcante](https://github.com/Luan-Cavalcante) |

## Introdução

O Diagrama de Componentes é uma visão estatíca dos componentes em um sistema e seus relacionamentos, e também são utilizados para desenvolver sistemas executáveis. Segundo a UML Reference Manual, um componente é "uma parte física e substituível de um sistema que empacota a implementação que está em conformidade e fornece a realização de um conjunto de interfaces". Os relacionamentos são destinados a especificar que um dos componentes utiliza os serviços de outro componente. Ademais, esse diagrama utiliza a linguagem UML, de forma a facilitar a compreensão da estrutura dos sistemas existentes e descrevê-los em qualquer linguagem de programação. Resumidamente, o principal objetivo de um Diagram de Componentes é demonstrar com clareza o relacionamento entre os componentes de um sistema.

## Metodologia 

Inicialmente, para a confecção do diagrama, entendeu-se o significado de cada unidade do desenho:

### Componentes Básicos
  Um diagrama de pacotes é representado por dois simbolos, que são apresentados e descritos abaixo: 

| Simbolo |  Nome  |                                  Descrição                                     |
| :-----: | :----: | :------------------------------------------------------------------------------: |
|   <img src="https://user-images.githubusercontent.com/69814362/205512779-5d39ba1d-b4ff-47f6-ad16-f29e7bec7587.png" alt="Component" width="150px"/>     | Componente | Bloco de unidade lógica do sistema, uma abstração ligeiramente maior que as classes |
|    <img src="https://user-images.githubusercontent.com/69814362/205514283-32677f8e-1d30-4b12-aa2d-aab27118ce02.png" alt="Required Interface" width="150px"/>     | Interface requerida | Conjunto de atributos públicos e operações que são requeridas pelas classes que dependem de uma determinada interface |
|    <img src="https://user-images.githubusercontent.com/69814362/205576974-81d7bce7-5c37-4331-887a-edbb2fbb2fba.png" alt="Provided Interface" width="150px"/>     | Interface fornecida | Conjunto de atributos públicos e operações que devem ser fornecidas pelas classes que implementam uma determinada interface |
|    <img src="https://raw.githubusercontent.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/master/docs/assets/diagrama_pacotes/dependency-symbol.svg" alt="Dependency" width="150px"/>     | Dependência | Dependência entre componentes |
|    <img src="https://user-images.githubusercontent.com/69814362/205513796-8bd8f5d3-1242-4f31-b197-4c40402d63eb.svg" alt="Port" width="150px"/>     | Porta | Indica que o próprio componente não fornece a interface requerida. Em vez disso, o componente delega a(s) interface(s) para uma classe interna |

Após a etapa supracitada, utilizou-se o [Diagrams](https://app.diagrams.net/) para concluir o artefato.

## Diagrama de Componentes

<figure>
  <img src="https://user-images.githubusercontent.com/69814362/205569857-624814d5-9c24-491e-bb88-b1caa510383a.png" alt="Diagrama de Componentes"/>
  <figcaption align="center" >Figura 1 - Diagrama de Componentes. <br> Fonte: Autor</figcaption>
</figure>


## Referências
> RBOOCH, Grady; JACOBSON, Ivar; RUMBAUGH, James. The Unified Modeling Language Reference Manual. 2. ed. Massachusetts: Pearson Education, 2004. 752 p. ISBN 032171895X.

> Diagrama de componentes UML: o que é, como fazer e exemplos. Lucidchart. Disponível em: https://www.lucidchart.com/pages/pt/diagrama-de-componentes-uml. Acesso em: 3 dez. 2022.

> UML Tutorial: How to Draw UML Component Diagram. Disponível em: https://www.youtube.com/watch?v=_iiOOxIDrGA. Acesso em: 03 dez. 2022.