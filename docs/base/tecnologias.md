# Tecnologias

## Histórico de versão

| Data       | Versão | Modificação                              | Autor                                                                                                                                                                |
| :--------- | :----- | :--------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 18/11/2022 | 0.1    | Criação da primeira versão do documento  | [Vitor Kühl](https://github.com/vitorekr) & [Thalisson Alves](https://github.com/Thalisson-Alves) |
| 18/11/2022 | 0.2    | Adição de tecnologias de _back-end_  | [Vitor Kühl](https://github.com/vitorekr) & [Thalisson Alves](https://github.com/Thalisson-Alves) |
 20/11/2022 | 0.3    | Revisão gramatical do artefato | [João Durso](https://github.com/jvsdurso)| 

## Introdução

Este documento possui como finalidade apresentar as tecnologias e ferramentas que serão utilizadas ao longo do desenvolvimento do projeto.

### Flutter

O Flutter é um framework criado pelo Google, e é um facilitador no desenvolvimento, que possibilita criar aplicativos mobile para Android e iOS com algumas funcionalidades vantajosas para o dia a dia de um programador.

O framework do Flutter foi todo desenvolvido em Dart, uma linguagem também criada pelo Google e que em muitos pontos se assemelha a C# e Java. Apenas para lembrar, o framework é um conjunto de bibliotecas usadas para criar uma base, sobre a qual as aplicações serão construídas.

### Dart

O Dart é uma linguagem de programação fortemente tipada, inicialmente criada pela Google em 2011. O objetivo inicial do Dart era substituir o JavaScript para desenvolvimento de scripts em páginas web. Porém, com a evolução da linguagem e com o passar dos anos, ela hoje pode ser considerada uma linguagem multi-paradigma, embora a linguagem apresente fortes estruturas típicas de linguagens orientadas a objeto.

### Python

Python é uma linguagem de programação interpretada, de alto nível, com tipagem dinâmica e forte. Inicialmente foi desenvolvida por Guido Van Rossum em 1991, e atualmente possui um desenvolvimento aberto e gerenciado pela ONG Python Software Foundation. Essa linguagem prioriza a legibilidade do código, possuindo uma sintaxe concisa e clara.

Essa linguagem exige pouco esforço de aprendizado e pode expressar algoritmos complexos com poucas linhas de código. Além disso ela conta com várias bibliotecas poderosas desenvolvidas pela própria comunidade.

### FastAPI

FastAPI é um framework moderno criado para desenvolver APIs Web. Esse framework possui alguns pontos chave, são eles:

- Rapidez: É um dos frameworks mais rápidos disponíveis para Python, possuindo um nível de performance parecido com NodeJS e Go.
- Rapidez para desenvolvimento: Possui uma interface de uso bem simples e concisa, podendo aumentar a velocidade de desenvolvimento em 200% a 300% de acordo com testes internos realizados pela própria equipe que a desenvolveu.
- Intuitiva: Possui um ótimo suporte às anotações de tipo, que facilita aos editores de texto de proverem sugestões de código no momento do desenvolvimento e diminui o tempo necessário para debugar um código visto que já se sabe os tipos esperados para cada função.
- Fácil: Foi desenhada de modo que seja fácil de ser usada e aprendida. Diminuindo o tempo gasto lendo a documentação.
- Curta: Minimiza os códigos duplicados, possuindo múltiplas funcionalidades para cada declaração de parâmetros.
- Robusta: Possui um código pronto para produção com documentação interativa automática.
- Baseada em padrões: Completamente compatíveis com os padrões mais usados para APIs Web, como OpenAPI (antigamente chamada de Swagger) e JSON Schema.

### Uvicorn

O Uvicorn é uma implementação para Python do ASGI (Asynchronous Server Gateway Interface). Por muito tempo o Python não tinha uma interface de baixo nível para servidores e aplicações assíncronas. Para preencher essa lacuna o ASGI foi criado.

### SQLAlchemy

SQLAlchemy é uma ferramenta SQL e ORM (Object Relational Mapper) para Python. Ela segue padrões conhecidos e estabelecidos no mercado, e foi desenhada para ser eficiente e disponibilizar uma forma bem performática de acesso ao banco de dados.

### PostgreSQL

PostgreSQL é um banco de dados relacional _open source_, possui mais de 35 anos de desenvolvimento ativo e ganhou uma forte reputação por ser performático, robusto e confiável. Atualmente, ele é um dos SGBDs (Sistema Gerenciador de Bancos de Dados) de código aberto mais avançados.

### Docker

Docker é uma ferramenta de plataforma como serviço (PaaS) usada para virtualização de nível de sistema operacional para entregar software em contêineres. Essa ferramenta auxilia na eliminação de tarefas repetitivas como configuração do ambiente para desenvolvimento e produção. Além disso ela garante que sempre estaremos usando o mesmo ambiente, assim não teremos problemas de dependências ou configurações específicas em alguma máquina, eliminando desculpas para o uso daquela famosa frase "Mas na minha máquina funciona".

## Conclusão

Após reuniões e discussões internas, chegamos na conclusão de que as tecnologias acima serão utilizadas no processo de desenvolvimento do projeto. Porém, não é descartado possíveis mudanças que venham a serem propostas antes do começo do desenvolvimento.


## Referências

> Introdução ao Flutter: como funciona o framework e sua linguagem Dart. [S. l.]: Digital House, 13 jun. 2020. Disponível em: https://www.digitalhouse.com/br/blog/o-que-e-flutter-e-como-funciona/. Acesso em: 18 nov. 2022.

> GUEDES, Marylene. O que é Dart?. [S. l.]: TreinaWeb, 21 out. 2019. Disponível em: https://www.treinaweb.com.br/blog/o-que-e-dart. Acesso em: 18 nov. 2022.

> Introdução ao Python. [S. l.]: Wikiversidade, 31 jan. 2020. Disponível em: https://pt.wikiversity.org/wiki/Introdu%C3%A7%C3%A3o_ao_Python/Introdu%C3%A7%C3%A3o. Acesso em: 18 nov. 2022.

> Você sabe como usar a FastAPI?. [S. l.]: Digital House, 4 jul. 2022. Disponível em: https://www.digitalhouse.com/br/blog/voce-sabe-como-usar-a-fastapi/. Acesso em: 18 nov. 2022.

> ANDRADE, Ana. O que é o SQLAlchemy?. [S. l.]: TreinaWeb, 1 nov. 2019. Disponível em: https://www.treinaweb.com.br/blog/o-que-e-o-sqlalchemy. Acesso em: 18 nov. 2022.

> Docker (software). In: WIKIPEDIA: a enciclopédia livre. Disponível em: https://pt.wikipedia.org/wiki/Docker_(software)#Refer%C3%AAncias. Acesso em: 18 nov. 2022.
