## Histórico de Versão
| Versão | Data | Modificação | Autor(es) | Revisores |
|:-:|:-:|:-:|:-:|:-:|
| 0.1 | 03/11/2022 | Criação e elaboração do documento | [Vitor Kühl](https://github.com/vitorekr) & [João Durso](https://github.com/jvsdurso)| --- |
| 0.2 | 03/11/2022 | Adição da introdução e da metodologia | [Vitor Kühl](https://github.com/vitorekr) & [João Durso](https://github.com/jvsdurso)| --- |


# Diagrama de Componentes

## Introdução

O Diagrama de Componentes é uma visão estatíca dos componentes em um sistema e seus relacionamentos, e também são utilizados para desenvolver sistemas executáveis. Segundo a UML Reference Manual, um componente é "uma parte física e substituível de um sistema que empacota a implementação que está em conformidade e fornece a realização de um conjunto de interfaces. Os relacionamentos são destinados a especificar que um dos componentes utiliza os serviços de outro componente. Ademais, esse diagrama utiliza a linguagem UML, de forma a facilitar a compreensão da estrutura dos sistemas existentes e descrevê-los em qualquer linguagem de programação. Resumidamente, o principal objetivo de um Diagram de Componentes é demonstrar com clareza o relacionamento entre os componentes de um sistema.


## Metodologia 

## Metodologia 

Inicialmente, para a confecção do diagrama, entendeu-se o significado de cada unidade do desenho:

### Componentes Básicos
  Um diagrama de pacotes é representado por dois simbolos, que são apresentados e descritos abaixo: 

| Simbolo |  Nome  |                                  Descrição                                     |
| :-----: | :----: | :------------------------------------------------------------------------------: |
|   <img src="https://user-images.githubusercontent.com/69814362/205512779-5d39ba1d-b4ff-47f6-ad16-f29e7bec7587.png" alt="Component" width="150px"/>     | Componente | Bloco de unidade lógica do sistema, uma abstração ligeiramente maior que as classes |
|    <img src="https://user-images.githubusercontent.com/69814362/205514283-32677f8e-1d30-4b12-aa2d-aab27118ce02.png" alt="Required Interface" width="150px"/>     | Interface requerida | Conjunto de atributos públicos e operações que são requeridas pelas classes que dependem de uma determinada interface |
|    <img src="https://user-images.githubusercontent.com/69814362/205514282-0fb80413-1571-4d86-b891-a788e07c814c.png" alt="Provided Interface" width="150px"/>     | Interface fornecida | Conjunto de atributos públicos e operações que devem ser fornecidas pelas classes que implementam uma determinada interface |
|    <img src="https://raw.githubusercontent.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/master/docs/assets/diagrama_pacotes/dependency-symbol.svg" alt="Dependency" width="150px"/>     | Dependência | Dependência entre componentes |
|    <img src="https://user-images.githubusercontent.com/69814362/205513796-8bd8f5d3-1242-4f31-b197-4c40402d63eb.svg" alt="Port" width="150px"/>     | Porta | Indica que o próprio componente não fornece a interface requerida. Em vez disso, o componente delega a(s) interface(s) para uma classe interna |

Após a etapa supracitada, utilizou-se o [Diagrams](https://app.diagrams.net/) para concluir o artefato.


## Diagrama de Componentes

<figure>

  <img src="https://user-images.githubusercontent.com/67024690/204846313-a69788a6-009e-4914-9c89-172d1ade7449.png" alt="Diagrama de Componentes"/>
  <figcaption align="center" >Figura 1 - Diagrama de atividades. Fonte: Autor</figcaption>
</figure>

## Referências
> 
> 