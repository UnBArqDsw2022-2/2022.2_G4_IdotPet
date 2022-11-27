# Introdução

Domain-Driven Design é um conjunto de princípios com foco em domínio, exploração de modelos de formas criativas e definir e falar a linguagem Ubíqua, baseado no contexto delimitado.

# Utilidade

No livro "Domain-Driven Design, Atacando as complexidades no coração do software" de Eric Evans, página 3, são destacadas três utilidades básicas que determinam a escolha de um modelo:

* O modelo e o coração do design dão forma um ao outro.
* O modelo é a espinha dorsal de uma linguagem utilizada por todos os membros da equipe.
* O modelo é um conhecimento destilado.

# Exploração de Modelos e Formas Criativas

DDD não é apenas focado em desenvolver um software, mas sim em entender a modelagem do projeto como um todo.
Se você não souber modelar o software, não conseguirá fazê-lo crescer e ser mantido a médio e longo prazo.

O DDD preza que os desenvolvedores façam parte do processo, entendendo o negócio e todos os seus modelos nos diferentes ângulos e não somente participando de reuniões com especialistas.

Fazendo um relacionamento com o mundo dos serviços, o novo perfil dos desenvolvedores faz com que o time participe de todo o processo, desde o levantamento de requisitos até o contato com o Domain Expert. Antigamente, o desenvolvedor apenas codificava.

# Linguagem Ubíqua (Ou Linguagem Onipresente)
Um dos pontos mais importantes do DDD, em que a maioria das pessoas acabam ignorando, que é falar e extrair a linguagem Ubíqua.

Linguagem Ubíqua é a linguagem falada no dia dia, no contexto da empresa. É a linguagem que utiliza as terminologias da realidade do negócio.

Eric Evans utiliza um trecho de Lewis Carrol, na obra "Poeta Fit, Non Nascitur" para exemplificar o significado desta linguagem:

<br>
_Primeiro, você descreve uma frase,</br>
Depois, corta daqui e corta dali;</br>
Mistura e separa os pedacinhos</br>
Sem saber onde vão cair:</br>
No fim, para a ordem da frase</br>
Nao se está nem aí.</br>
 - Lewis Carroll, "Poeta Fit, Non Nascitur"_</br>

# Pilares do DDD

## Linguagem Ubíqua
A ideia principal é você fazer a ligação da Linguagem Ubíqua entre os Experts no Negócio e os desenvolvedores. Quando eles conseguem definir quais são os termos que eles mais irão utilizar, essa extração fará toda a diferença no processo de desenvolvimento e comunicação na aplicação. Quando utilizamos a Linguagem Ubíqua é muito importante que esteja tudo organizado e extraído.

![linguagemUbiqua](https://user-images.githubusercontent.com/56610229/204137169-950b8947-0c28-4248-b6dd-3af9f2f8591f.png)

## Bounded Context

Os Bounded Contexts ou contextos delimitados, delimita os contextos da aplicação. Cada contexto possui suas responsabilidades claramente definidas que por sua vez pode ter sua própria linguagem Ubíqua. A utilização de histórias e levantamento do escopo do projeto com o Domain Expert auxilia no processo de delimitação de contexto.

## Context Map

O terceiro pilar do DDD é o Context Map, que nada mais é que o mapeamento dos Bounded Contexts.
a relação entre os domínios principais e genéricos são upstream/downstream, respectivamente. Isso porque o domínio principal é prioridade em relação ao genérico. Se alguma coisa mudar, terá que ser do lado do domínio genérico. É uma relação cliente/fornecedor.

![context_map](https://user-images.githubusercontent.com/56610229/204137183-00840c33-7a46-4866-9385-ae39c51a915d.png)





