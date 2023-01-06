# Padrões Emergentes

## Histórico de Versões

| Data | Versão | Modificação | Autor |
| :- | :- | :- | :- |
| 02/01/2023   | 0.1   | Criação da base do documento   | [Pedro Cassiano](https://github.com/PedroLucasCM) & [João Durso](https://github.com/jvsdurso) |

## Introdução




## Metodologia

Foi realizado uma reunião via ferramenta Discord, onde foi elencado os padrões emergentes utilizados em nosso projeto. Em primeiro momento foi realizado um estudo do padrão e a comparação em nosso projeto atual (se possível). Foi percebido o uso do padrão MVC em nosso código backend.

## Padrões Emergentes

### MVC

O Facade é um padrão de projeto estrutural que fornece uma interface simplificada para uma biblioteca, um framework, ou qualquer conjunto complexo de classes.

#### Aplicabilidade

- Tornar o código mais manutenível na medida em que as classes de visualização e negócio forem aumentando em quantidade.
- Esconder a complexidade de 03 objetos de negócio para inserir um único cliente.
- Diminuir o acoplamento entre camadas.

#### Implementação no IdotPet

Nenhuma implementação até o momento

## Possível implementação em código


## Referências

> DEV Community. Design Patterns - Flutter. Disponível em: <https://dev.to/blazebrain/design-patterns-flutter-9dh>.  Acesso em: 04 jan. 2023.

> GAMMA, Erich et al. Design patterns: elements of reusable object-oriented software. Pearson Deutschland GmbH, 1995.

> GURU, Refactoring. Refactoring.Guru. [S. l.], 2023. Disponível em: https://refactoring.guru/. Acesso em: 4 jan. 2023.