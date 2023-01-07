# GRASP Polimorfismo

## Histórico de Versões

| Data | Versão | Modificação | Autor |
| :- | :- | :- | :- |
| 02/01/2023   | 0.1   | Criação da base do documento   | [Victor Cabral](https://github.com/victordscabral) |
| 03/01/2023   | 0.2   | Preenchimento inicial do documento   | [Victor Cabral](https://github.com/victordscabral) e [Klyssmann Oliveira](https://github.com/klyssmannoliveira) |
| 04/01/2023   | 0.3   | Preenchimento da metodologia   | [Victor Cabral](https://github.com/victordscabral) e [Pedro Cassiano](https://github.com/PedroLucasCMa) |
| 04/01/2023   | 0.4   | Aplicação dos GRASPs   | [Victor Cabral](https://github.com/victordscabral) e [Pedro Cassiano](https://github.com/PedroLucasCMa) |

## Introdução

Os padrões GRASPs (do inglês "General Responsibility Assignment Software Patterns") são padrões utilizados em um software orientado a objetos com objetivo de atribuir responsabilidades para diferentes módulos do código, como objetos e classes.

Essas responsabilidades são as obrigações de um objeto ou classe levando em conta o seu papel em um contexto.

Eles classificam tanto problemas quanto soluções como padrões e, após as definições destes, podem então ser aplicados em instâncias parecidas.

Os padrões GRASPs podem ser classificados em:

- **Criador**
- **Especialista**
- **Alta Coesão**
- **Baixo Acoplamento**
- **Controladora**
- **Polimorfismo**
- **Invenção Pura ou Fabricação Própria**
- **Indireção**
- **Variações Protegidas**

Foram utilizados os padrões Criador, Especialista, Polimorfismo e Controlador no projeto. A aplicação do polimorfismo no projeto será mais detalhada abaixo.

## Metodologia

Foi realizada uma reunião via ferramenta Discord, onde foi elencado os padrões mais adequados para o projeto. Em primeiro momento foi realizado um estudo do padrão e a implementação em código do projeto atual (se possível) ou de projetos similares.

## GRASP Polimorfismo

No polimorfismo temos que subclasses que se originam de uma superclasse podem invocar métodos da segunda e sobrescrevê-los, já que cada subclasse tem um comportamento diferente.

O padrão polimorfismo trabalha na organização das classes utilizando operações polimórficas, fazendo com que as responsabilidades sejam atribuídas a abstrações condizentes ao invés de objetos concretos. 
    
### Vantagens
	
- Apoia o princípio de baixo acoplamento;
- Útil em projetos com variações semelhantes;
- Facilidade em estender o projeto com novas funcionalidades;

### Implementação no iDotPet
O GRASP polimorfismo foi utilizado na herança do Usuario em UsuarioAnunciante e UsuarioAdotante, as duas especializações possuindo funcionalidades diferentes no projeto. A Figura 2 mostra as classes de nosso [Diagrama de Classe](docs/modelagem/diagrama_classe.md).

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/diagrama_classe/diagrama_classe(v3).png?raw=true" alt="Diagrama de Classe"/>
  <figcaption align="center" >Figura 1 - Diagrama de Classe (completo). Fonte: Autores </figcaption>
</figure>

### Referências

> Serrano, Milene. 2020. Aula GRASPs Parte I Conteúdo Complementar.  https://aprender3.unb.br/pluginfile.php/2277128/mod_label/intro/Arquitetura%20e%20Desenho%20de%20Software%20-%20Aula%20GRASP_A%20-%20Profa.%20Milene%20-%20Complementar.pdf. Acesso em 04/01/2023.

> Serrano, Milene. 2020. Aula GRASPs Parte II Conteúdo Complementar.  https://aprender3.unb.br/pluginfile.php/2277128/mod_label/intro/Arquitetura%20e%20Desenho%20de%20Software%20-%20Aula%20GRASP_B%20-%20Profa.%20Milene%20-%20Complementar.pdf. Acesso em 04/01/2023.

> BOAS, Leandro. Padrões GRASP — Padrões de Atribuir Responsabilidades. Medium, 2019. Disponível em: <https://medium.com/@leandrovboas/padr%C3%B5es-grasp-padr%C3%B5es-de-atribuir-responsabilidades-1ae4351eb204>. Acesso em: 04 jan. 2023.

> Renato. Desenvolvimento com qualidade com GRASP. Devmedia, 2013. Disponível em: <https://www.devmedia.com.br/desenvolvimento-com-qualidade-com-grasp/28704>. Acesso em: 04 jan. 2023.

> GRASP (padrão orientado a objetos). Wikipedia, 2020. Disponível em: <https://pt.wikipedia.org/wiki/GRASP_(padr%C3%A3o_orientado_a_objetos)>. Acesso em: 04 jan. 2023.
