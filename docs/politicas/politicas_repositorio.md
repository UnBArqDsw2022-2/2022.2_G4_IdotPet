# Políticas do Repositório

## Histórico de versão

| Data | Versão | Modificação | Autor |
| :- | :- | :- | :- |
| 07/11/2022 | 0.1 | Criação da primeira versão do documento | [@klyssmannoliveira](https://github.com/klyssmannoliveira) |
| 08/11/2022 | 0.2 | Revisão e aprimoramento do documento| [@kayrocesar](https://github.com/kayrocesar) |
| 20/11/2022 | 0.3    | Revisão gramatical do documento | [João Durso](https://github.com/jvsdurso)| 

## Objetivo:

Critérios a serem seguidos por todos que queiram contribuir para o projeto, principalmente os colaboradores e desenvolvedores oficiais.

**Índice do documento**:

- [Políticas do Repositório](#políticas-do-repositório)
  - [Histórico de versão](#histórico-de-versão)
  - [Objetivo:](#objetivo)
  - [Política de Branches](#política-de-branches)
    - [Master](#Master)
      - [Features](#features)
      - [Hotfix](#hotfix)
      - [Doc](#doc)
  - [Política de Commits](#política-de-commits)

## Política de Branches

A partir das branches que serão resolvidas as issues e criados artefatos para serem adicionados ao projeto principal, após revisões.

Existem 3 tipos de branches, que, para projetos de menor escopo, como este, possui uma menor burocracia e maior eficácia no gerenciamento do projeto.

- São elas:
  - [Master](#Master)
  - [Features](#features)
  - [Hotfix](#hotfix)
  - [Doc](#doc)

### Master

**Existe somente uma branch Master!** Essa branch contém o projeto em seu estado mais estável. É nessa branch que deve-se ter todos os arquivos antes de alguma release. Quando alguma funcionalidade é implementada, deve ser feito um pull request para essa branch, que será analisada pelo colaborador responsável.

Deverão ser utilizadas tags, o que eliminará a necessidade de criação de branches develop. Com as tags têm-se referência de versão, correções e afins. Deve-se associar tags aos commits, quando necessário.

- **Para criar tags:**

``` git
git tag -a v1.1 -m "Descrição da tag"
```

Substitua os números dentro do seu contexto de versão

- **Para transferir tags para o rep:**

``` git
git push origin --tags
```

- **Para associar tags com commits:**

``` git
git tag -a nomedatag hashcode-do-commit
```

- **Para listar tags:**

``` git
git tag
```

#### Features

Essa ramificação é criada sempre que uma issue endereça uma nova funcionalidade para o projeto. **Essa branch é criada a partir da [Master](#Master) e é mesclada à mesma branch**. Para criar uma branch desse tipo, devemos executar os comandos:

```git
git branch feature/indice-nome-da-issue
git checkout indice-nome-da-issue
```

ou ainda

```git
git checkout -b feature/indice-nome-da-issue
```

#### Hotfix

As branches hotfix devem ser criadas quando há uma issue apontando a necessidade de correção de bugs nas funcionalidades do projeto. **Essa branch é criada apartir da [Master](#Master) e é mesclada à mesma branch**.

Para criar uma branch desse tipo, devemos executar os comandos:

```git
git branch hotfix/indice-nome-da-issue
git checkout hotfix/indice-nome-da-issue
```

ou ainda

```git
git checkout -b hotfix/indice-nome-da-issue
```

#### Doc

As branches docs devem ser criadas quando há uma issue apontando a necessidade de criação de documentos. **Essa branch é criada a partir da [Master](#Master) e é mesclada à mesma branch**. Após a primeira versão estável, correções podem ser feitas diretamente na branch Master.

Para criar uma branch desse tipo, devemos executar os comandos:

```git
git branch doc/indice-nome-da-issue
git checkout doc/indice-nome-da-issue
```

ou ainda

```git
git checkout -b doc/indice-nome-da-issue
```

## Política de Commits

Os commits são essenciais para acompanharmos as alterações e adições ao projeto. 
Deve ser usado o modo imperativo (ações e ordens assertivas) para mencionar o que foi feito.

### Princípios básicos

####  1. Faça commits atômicos quando possível

Os commits atômicos são aqueles que gravam apenas uma única mudança – ainda que envolva vários arquivos – em um único commit. É claro que nem sempre dá para fazer, mas é uma prática excelente se conseguir fazer.


####  2. Faça commits regulares e frequentes

Não espere demais!

Algumas pessoas esperam demais até gravar alguma alteração, às vezes ficam ali melhorando algo que já está funcionando, buscando algum tipo de perfeição antes de gravar. Ao gravar com frequência você vai rastrear inclusive como você foi melhorando aquele código ao longo do seu processo e histórico de desenvolvimento.


####  3. Escreva mensagens de commit claras

As mensagens precisam fazer sentido e ser úteis para todos do time.



#### 4. Faça commits pontuais e objetivos
Evite fazer um commit com dezenas de arquivos, em especial se esses arquivos trazem mais de uma mudança ou correção. Devemos evitar isso pois fica difícil rastrear, entender e revisar o que foi feito no commit. Prefira fazer commits pequenos e pontuais de algo que está terminado, algo que funciona e que não traga muitas alterações de uma vez só.

### Modelo do commit
#### Commit Simples
Caso o commit trate de uma questão simples, faça o commit da seguinte maneira:

```git
git commit -m "#IdIssue - Mensagem"
```
#### Commit Complexo
Devido à importância, caso o commit trate de algo mais complexo, use o seguinte template para padronização, substituindo o texto dos comentários '# não será lido no commit':

``` txt
. #Id-da-Issue - Título do commit: comece com  letra maiúscula, objetivo
#Não mais que 50 chars,Essa linha possui   50                   #
#Pular linha

# Corpo: Explique o quê e porque
# Não mais que 72 caracteres (essa linha possui)                                                                             #

#OPCIONAL: Caso haja, inclua essa linha de co-autores do seu commit para cada contribuidor.
#Pular 2 linhas


# Co-authored-by: nome1 <usuário1@users.noreply.github.com>
# Co-authored-by: nome2 <usuário2@users.noreply.github.com>
#Pular linha

```
