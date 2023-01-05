# GRASPs

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

Foram utilizados os padrões Criador, Especialista, Polimorfismo e Controlador no projeto. Suas aplicações no projeto serão mais detalhadas abaixo.

## Metodologia

Foi realizada uma reunião via ferramenta Discord, onde foi elencado os padrões mais adequados para o projeto. Em primeiro momento foi realizado um estudo do padrão e a implementação em código do projeto atual (se possível) ou de projetos similares.

## GRASP 1 - Criador

O padrão criador trabalha na organização da função de criação de objetos. Ele padroniza a atribuição dessa responsabilidade em classes que condizem com essa função, evitando problemas que podem surgir da ideia de que sempre a melhor classe para criar uma instância é a própria classe. Ao trabalhar com orientação a objetos nem essa lógica é válida.

Uma classe A deve criar instâncias de uma classe B quando uma ou mais afirmações a seguir acontecem quanto as instâncias:

- A contém ou agrega instâncias de B;
- A grava instâncias de B;
- A utiliza de perto instâncias de B;
- A têm as informações de iniciação das instâncias de B e passa isso na criação.
    
### Vantagens
	
- Evita violações em princípios como o de encapsulamento e alto acoplamento.

### Implementação no iDotPet
O grasp criador será extremamente útil e implementado no projeto do IdotPet sempre que for possível, criando novas instâncias de vários objetos principalmente Usuario e Pet. A Figura 1 mostra algumas classes de nosso [Diagrama de Classe](docs/modelagem/diagrama_classe.md), nela observa-se que temos a classe Endereco, porém ela não é uma instância TODO e sim uma instância PARTE pois ela não existe sem o TODO(Usuario).

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/diagrama_classe/diagrama_classe(v1).png?raw=true" alt="Diagrama de Classe"/>
  <figcaption align="center" >Figura 1 - Diagrama de Classe (parte). Fonte: Autores </figcaption>
</figure>

## GRASP 2 - Especialista

O padrão especialista trabalha na organização da função de especialização de objetos, definindo quando se deve dar essa responsabilidade para um outro objeto que seja especialista naquele domínio.
Tende ser mais fácil entender, manter, estender e reutilizar no projeto quando se conhece bem as responsabilidades de suas classes e objetos. Se deve utilizar bom senso para atribuir as responsabilidades a objetos condizentes.
  
### Vantagens
	
- Encapsulamento da informação é mantido para os objetos;
- O acoplamento entre objetos tende a ser baixo;
- A coesão dos objetos tende a ser alta.

### Implementação no iDotPet
Como explicado no GRASP Criador, não se é aplicado o GRASP Criado no Endereco na Figura 1 pois ele é PARTE do TODO(Usuario), logo ele é uma especialidade do Usuario, temos aí então um GRASP Especialista.

## GRASP 3 - Polimorfismo

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
  <figcaption align="center" >Figura 2 - Diagrama de Classe (completo). Fonte: Autores </figcaption>
</figure>

## GRASP 4 - Controlador

O padrão controlador atribui a responsabilidade de lidar com eventos do sistema a uma classe não relacionada à interface com o usuário (IU). Ele é o primeiro objeto depois da camada de IU, tratando mensagens de operações do sistema. Se deve atribuir essa responsabilidade de controlador para um classe que represente todo o sistema ou caso de uso.
    
### Vantagens
- Aumenta as possibilidades de reutilização e de interfaces “plugáveis”;
- Facilita reutilizar a lógica em futuras aplicações e definir diferentes interfaces para ela;
- Facilita o raciocínio sobre o estado do caso de uso já que parte da regra de negócio encontra-se nas classes controladoras.

### Implementação no iDotPet
O GRASP Controlador é implementado com a ajuda do padrão MVC utilizado em nosso projeto. A Figura 2 mostra a classe controladora user_controller.py que possui algumas funções de controle como a criação de um usuário e login de usuários.

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/grasp_controlador/classe_controller.png?raw=true" alt="Diagrama de Classe"/>
  <figcaption align="center" >Figura 3 - Controlador. Fonte: Autores </figcaption>
</figure>

### Referências

> Serrano, Milene. 2020. Aula GRASPs Parte I Conteúdo Complementar.  https://aprender3.unb.br/pluginfile.php/2277128/mod_label/intro/Arquitetura%20e%20Desenho%20de%20Software%20-%20Aula%20GRASP_A%20-%20Profa.%20Milene%20-%20Complementar.pdf. Acesso em 04/01/2023.

> Serrano, Milene. 2020. Aula GRASPs Parte II Conteúdo Complementar.  https://aprender3.unb.br/pluginfile.php/2277128/mod_label/intro/Arquitetura%20e%20Desenho%20de%20Software%20-%20Aula%20GRASP_B%20-%20Profa.%20Milene%20-%20Complementar.pdf. Acesso em 04/01/2023.

> BOAS, Leandro. Padrões GRASP — Padrões de Atribuir Responsabilidades. Medium, 2019. Disponível em: <https://medium.com/@leandrovboas/padr%C3%B5es-grasp-padr%C3%B5es-de-atribuir-responsabilidades-1ae4351eb204>. Acesso em: 04 jan. 2023.

> Renato. Desenvolvimento com qualidade com GRASP. Devmedia, 2013. Disponível em: <https://www.devmedia.com.br/desenvolvimento-com-qualidade-com-grasp/28704>. Acesso em: 04 jan. 2023.

> GRASP (padrão orientado a objetos). Wikipedia, 2020. Disponível em: <https://pt.wikipedia.org/wiki/GRASP_(padr%C3%A3o_orientado_a_objetos)>. Acesso em: 04 jan. 2023.