# Diagrama de Classes

## Histórico de Versões

| Data       | Versão | Modificação                                                                                                                           | Autor                                                                                              |
| :--------- | :----- | :------------------------------------------------------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------------------- |
| 28/11/2022 | 0.1    | Criação e elaboração do documento                                                                                                     | [Herick Lima](https://github.com/hericklima22) & [Pedro Cassiano](https://github.com/PedroLucasCM) |
| 28/11/2022 | 0.2    | Mudança no diagrama de classe com a adição de Anuncio, Mensagem, Denuncia e herança de Usuario para UsuarioAnunciante e UsuarioDoador | [Herick Lima](https://github.com/hericklima22) & [Pedro Cassiano](https://github.com/PedroLucasCM) |
| 04/01/2023 | 1.1    | Adição de uma ligação entre UsuarioAdotante com Anuncio | [Herick Lima](https://github.com/hericklima22) & [Pedro Cassiano](https://github.com/PedroLucasCM) & [Victor Cabral](https://github.com/victordscabral) |
## Introdução

A Linguagem de Modelagem Unificada (UML) é uma linguagem visual criada para padronizar modelagens para programações orientadas a objeto como o diagrama de classes. Por sua vez, um diagrama de classe é uma notação visual de um diagrama estático que mostra um conjunto de classes e interfaces, suas propriedades, métodos e comportamentos dos objetos e seus relacionamentos com as outras classes.

[comment]: <> (Mudar próximo parágrafo se houver alteração no diagrama de classes)

Nosso diagrama inicial mostra suas classes como Pet, Usuario, UsuarioAnunciante, UsuarioAdotante, Endereco, Mensagem, [Anuncio](master\docs\base\léxico.md) e Denuncia.

## Metodologia

  O grupo se reuniu e com a ajuda dos desenvolvedores principais Vitor Kuhl e Thalisson Jesus ouve um brainstorming de quais classes teríamos de base no código já que não tínhamos os códigos do produto. Foi-se feito então um diagrama de classe básico com Usuario, Pet e Endereco. Logo depois foi-se desenvolvendo as classes e foram criadas as classes Mensagem, Anuncio, Denuncia e as classes hereditárias UsuarioAnunciante e UsuarioAdotante. Com o tempo fomos evoluindo o diagrama de acordo com a necessidade e coerência.

## Diagrama de Classe

<figure>
  <img src="https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/diagrama_classe/diagrama_classe(v4).png?raw=true" alt="Diagrama de Classe"/>
  <figcaption align="center" >Figura 1 - Diagrama de Classe. Fonte: Autores </figcaption>
</figure>

## Versões

[Versão 1](https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/diagrama_classe/diagrama_classe(v1).png?raw=true)

[Versão 2](https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/diagrama_classe/diagrama_classe(v2).png?raw=true)

[Versão 3](https://github.com/UnBArqDsw2022-2/2022.2_G4_IDotPet/blob/master/docs/assets/diagrama_classe/diagrama_classe(v3).png?raw=true)


## Referências

> SERRANO, Milene. Arquitetura e Desenho de Software: AULA - MODELAGEM UML ESTÁTICA. 2021. Disponível em: https://aprender3.unb.br/pluginfile.php/2277120/mod_label/intro/Arquitetura%20e%20Desenho%20de%20Software%20-%20Aula%20Modelagem%20UML%20Estática%20-%20Profa.%20Milene.pdf. Acesso em: 25 nov. 2022.

> Lucid Software Inc. O que é um diagrama de classe?. 2022. Lucidchart. Disponível em:https://www.lucidchart.com/pages/pt/o-que-e-diagrama-de-classe-uml. Acesso em 28 nov. 2022.
