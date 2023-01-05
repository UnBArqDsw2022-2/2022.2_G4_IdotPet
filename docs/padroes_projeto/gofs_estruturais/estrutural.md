# GoFs Estruturais

## Histórico de Versões

| Data | Versão | Modificação | Autor |
| :- | :- | :- | :- |
| 02/01/2023   | 0.1   | Criação da base do documento   | [Klyssmann Oliveira](https://github.com/klyssmannoliveira) |
| 03/01/2023   | 0.2   | Preenchimento inicial do documento   | [Victor Cabral](https://github.com/victordscabral) |
| 04/01/2023   | 0.3   | Primeira parte da introdução        | [Herick Lima](https://github.com/hericklima22) & [Nicolas Roberto](https://github.com/Nicolas-Roberto) & [Kayro César](https://github.com/kayrocesar) |
| 04/01/2023   | 0.4   | Introdução completa        | [Herick Lima](https://github.com/hericklima22) & [Nicolas Roberto](https://github.com/Nicolas-Roberto) & [Kayro César](https://github.com/kayrocesar) |
| 04/01/2023   | 0.5   | Metodologia        | [Herick Lima](https://github.com/hericklima22) & [Nicolas Roberto](https://github.com/Nicolas-Roberto) & [Kayro César](https://github.com/kayrocesar) |
| 04/01/2023   | 0.6   | Terminados padrões Facade e Proxy        | [Herick Lima](https://github.com/hericklima22) & [Nicolas Roberto](https://github.com/Nicolas-Roberto) & [Kayro César](https://github.com/kayrocesar) |

## Introdução

Os padrões de projeto GoF (Gang of Four) são uma série de padrões que fornecem uma base, modelo ou descrição de como resolver problemas frequentes durante o desenvolvimento do software. Os padrões de projeto fornecem muitos benefícios, que podem incluir:

- Fornecer um padrão geral para comunicação entre desenvolvedores;
- Reduzir o tempo ou acelerar o processo de desenvolvimento;
- Fornecer soluções comprovadas para problemas recorrentes comuns; e
- Fornecer práticas recomendadas para obter uma base de código limpa, reutilizável e sem erros.

Existem 23 padrões de projeto e estão dividividas em três categorias:

- Criacional (Tema deste documento): dizem respeito ao processo de criação de objetos;
- Estrutural: lidam com a composição de classes ou objetos; e
- Comportamental: caracterizam as maneiras pelas quais classes ou objetos interagem e distribuem responsabilidades.

Os padrões estruturais estão preocupados com a forma como as classes e os objetos são compostos a partir de estruturas maiores. Padrões de classes estruturais usam herança para compor interfaces ou implementações. Como um exemplo simples, considere como a herança múltipla mistura duas ou mais classes em uma. O resultado é uma classe que combina as propriedades de suas classes pai. Esse padrão é particularmente útil para fazer com que bibliotecas de classes desenvolvidas independentemente funcionem juntas.


## Metodologia

Foi realizado uma reunião via ferramenta Discord, onde foi elencado os padrões mais adequados para o projeto. Em primeiro momento foi realizado um estudo do padrão e a implementação em código do projeto atual (se possível) ou de projetos similares.

## GoFs Estruturais

### 1. Estrutural - Facade

O Facade é um padrão de projeto estrutural que fornece uma interface simplificada para uma biblioteca, um framework, ou qualquer conjunto complexo de classes.

#### 1.1 Diagrama Estrutural

![Diagrama estrutural Facade](docs/assets/gofs-estruturais/diagrama/facade.png)

#### 1.2 Aplicabilidade

- Tornar o código mais manutenível na medida em que as classes de visualização e negócio forem aumentando em quantidade.
- Esconder a complexidade de 03 objetos de negócio para inserir um único cliente.
- Diminuir o acoplamento entre camadas.

#### 1.3 Implementação no IdotPet

Nenhuma implementação até o moment

### 2. Estrutural - Proxy

Proxy é um padrão de design estrutural que permite fornecer um substituto ou espaço reservado para outro objeto. Um proxy controla o acesso ao objeto original, permitindo que você execute algo antes ou depois que a solicitação chega ao objeto original.

#### 2.1 Diagrama Estrutural

![Diagrama estrutural Proxy](docs/assets/gofs-estruturais/diagrama/proxy.png)

#### 2.2 Aplicabilidade

O padrão Proxy sugere que você crie uma nova classe de proxy com a mesma interface que um objeto de serviço original. Em seguida, você atualiza seu aplicativo para que ele transmita o objeto proxy para todos os clientes do objeto original. Ao receber uma solicitação de um cliente, o proxy cria um objeto de serviço real e delega todo o trabalho para ele.

#### 2.3 Implementação no IdotPet

### 3. Estrutural - Bridge
#### 3.1 Diagrama Estrutural
O Bridge é um padrão de projeto estrutural que permite que seja dividida uma classe grande ou um conjunto de classes intimamente ligadas em duas hierarquias separadas—abstração e implementação—que podem ser desenvolvidas independentemente umas das outras.

#### 3.2 Aplicabilidade



#### 3.3 Implementação no IdotPet
##

### 4. Estrutural - FlyWeight
#### x.1. Diagrama Estrutural
#### x.2. Aplicabilidade
#### x.3. Implementação no IdotPet
### 5. Estrutural - Decorator
#### x.1. Diagrama Estrutural
#### x.2. Aplicabilidade
#### x.3. Implementação no IdotPet

### 6. Estrutural - Composite
#### x.1. Diagrama Estrutural
#### x.2. Aplicabilidade
#### x.3. Implementação no IdotPet

### 7. Estrutural - Adapter
O Adapter é um padrão de projeto estrutural que permite objetos com interfaces incompatíveis colaborarem entre si.
Um adaptador encobre um dos objetos para esconder a complexidade da conversão acontecendo nos bastidores. O objeto encobrido nem fica ciente do adaptador. Por exemplo, você pode encobrir um objeto que opera em metros e quilômetros com um adaptador que converte todos os dados para unidades imperiais tais como pés e milhas.

#### 7.1. Diagrama Estrutural
![Alt text](docs/assets/gofs-estruturais/diagrama/adapter.png)

#### 7.2. Aplicabilidade
#### 7.3. Implementação no IdotPet

## Aplicação no Projeto


## Possível implementação em código


## Referências