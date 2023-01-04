# GoF - Criacionais

## Histórico de Versões

| Data | Versão | Modificação | Autor |
| :- | :- | :- | :- |
| 04/01/2023 | 0.1 | Criação da estrutura | [Klyssmann Oliveira](https://github.com/klyssmannoliveira)|
| 04/01/2023 | 0.2 | Introdução | [João Durso](https://github.com/jvsdurso) & [Klyssmann Oliveira](https://github.com/klyssmannoliveira) |
| 04/01/2023 | 0.3 | Metodologia | [Eduardo Maia Rezende](https://github.com/eduardomr), [Pedro Cassiano](https://github.com/PedroLucasCM) & [Victor Cabral](https://github.com/victordscabral)|
| 04/01/2023 | 0.4 | Melhoria na introdução | [João Durso](https://github.com/jvsdurso), [Klyssmann Oliveira](https://github.com/klyssmannoliveira), [Eduardo Maia Rezende](https://github.com/eduardomr), [Pedro Cassiano](https://github.com/PedroLucasCM) & [Victor Cabral](https://github.com/victordscabral) |
| 04/01/2023 | 0.5 | Builder | [Klyssmann Oliveira](https://github.com/klyssmannoliveira) & [Vitor Eduardo](https://github.com/vitorekr) |


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

Padrões de projeto criacional abstraem o processo de instanciação. Eles ajudam a tornar um sistema independente de como seus objetos são criados, compostos e representados. Um padrão de criação de classe usa herança para variar a classe que é instanciada, enquanto um padrão de criação de objeto delega a instanciação a outro objeto.

Os padrões de criação tornam-se importantes à medida que os sistemas evoluem para depender mais da composição de objetos do que da herança de classes. Quando isso acontece, a ênfase da codificação muda de um conjunto fixo de comportamentos para a definição de um conjunto menor de comportamentos fundamentais que podem ser compostos em qualquer número de comportamentos mais complexos. Desta maneira, criar objetos com comportamentos específicos requer mais do que simplesmente instanciar uma classe. 

Há dois temas recorrentes nesses padrões. Primeiro, todos eles encapsulam o conhecimento sobre quais classes concretas o sistema usa. Em segundo lugar, eles escondem como as instâncias dessas classes são criadas e reunidas. Tudo o que o sistema em geral sabe sobre os objetos são suas interfaces definidas por classes abstratas. Conseqüentemente, os padrões de criação oferecem muita flexibilidade no que é criado, quem o cria, como e quando. 

## Metodologia

Foi realizado uma reunião via ferramenta Discord, onde foi elencado os padrões mais adequados para o projeto. Em primeiro momento foi realizado um estudo do padrão e a implementação em código do projeto atual (se possível) ou de projetos similares.

## Criacional 1 - Builder

O livro da Gang of Four define o objetivo do builder como:

> "Separar a construção de um objeto complexo de sua representação para que o mesmo processo de construção possa criar diferentes representações."

O builder move o código de construção do objeto para fora de sua própria classe para objetos separados chamados construtores. Cada um desses construtores segue a mesma interface e implementa etapas separadas de construção de objetos. Ou seja, se o objetivo é ter uma representação diferente do objeto, basta criar uma classe construtora diferente e implementar essas etapas de construção correspondentemente. 

Além disso, há uma camada adicional no padrão de projeto Builder — Diretor. O Diretor é uma classe simples que conhece a interface do Construtor e define a ordem na qual executar as etapas de construção. Essa classe não é obrigatória, mas oculta os detalhes da construção do produto do código do cliente.

### Aplicação no Projeto

Desenhar diagrama explicando a aplicação

### Possível implementação em código

Código

## Criacional 2

### Aplicação no Projeto


### Possível implementação em código


## Referências

> DEV Community. Design Patterns - Flutter. Disponível em: <https://dev.to/blazebrain/design-patterns-flutter-9dh>.  Acesso em: 04 jan. 2023.

> GAMMA, Erich et al. Design patterns: elements of reusable object-oriented software. Pearson Deutschland GmbH, 1995.