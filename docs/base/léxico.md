# Léxico

## Histórico de Versões

|    Data    | Versão |            Modificação             |                                                 Autor                                                  |
| :--------: | :----: | :--------------------------------: | :----------------------------------------------------------------------------------------------------: |
| 14/11/2022 |  0.1   |        Criação do documento        | [Nicolas-Roberto](https://github.com/Nicolas-Roberto) & [Herick Lima](https://github.com/hericklima22) |
| 18/11/2022 |  0.2   |       Melhorias no documento       |                             [Herick Lima](https://github.com/hericklima22)                             |
| 20/11/2022 |  0.3   |   Revisão gramatical do artefato   |                               [João Durso](https://github.com/jvsdurso)                                |
| 20/11/2022 |  1.0   | Atualização e correção do artefato | [Nicolas-Roberto](https://github.com/Nicolas-Roberto) & [Herick Lima](https://github.com/hericklima22) |

## Introdução

Léxico é uma técnica com a finalidade de descrever os símbolos de uma linguagem. No escopo de engenharia de requisitos, o léxico é um artefato importante em um produto de software, para que todos as palavras chave sejam catalogadas e definidas.

## Metodologia

No processo de desenvolvimento do artefato léxico utilizaremos o modelos de tabela a seguir:

|     Nome:     |          Usuário          |
| :-----------: | :-----------------------: |
|   Sinônimos   |      Nomes sinônimos      |
|     Noção     |  A noção sobre o léxico   |
|    Impacto    |    O impacto do léxico    |
| Classificação | A classificação do léxico |

## Léxico

### Classe Objeto

#### Anunciante

|     Nome:     |                      Anunciante                       |
| :-----------: | :---------------------------------------------------: |
|   Sinônimos   |                   Informar, exibir                    |
|     Noção     |             Anunciante que está doando um             |
|    Impacto    | Anunciante deseja doar um pet através do _smartphone_ |
| Classificação |                        Objeto                         |

### Adotante

|     Nome:     |                                     Adotante                                   |
| :-----------: | :----------------------------------------------------------------------------: |
|     Noção     | Usuário que está adotando um animal                                            |
|    Impacto    |           Usuário deseja adotar um pet através do _smartphone_                 |
| Classificação |                                     Objeto                                     |

### Voluntário

|     Nome:     |                                     Voluntário                                   |
| :-----------: | :----------------------------------------------------------------------------: |
|     Noção     | Usuário que está se dispondo a ser voluntário na comunidade     =              |
|    Impacto    |           Usuário deseja ajudar e auxiliar a comunidade voluntariamente        |
| Classificação |                                     Objeto                                     |

### Administrador do sistema

|     Nome:     |                                     Administrador                              |
| :-----------: | :----------------------------------------------------------------------------: |
|     Noção     | Usuário que fará o gerenciamente e manutenção do aplicativo                    |
|    Impacto    |           Gerenciar publicações e perfis para que estejam dentro das regras da comunidade |
| Classificação |                                     Objeto                                     |

#### Pet

|     Nome:     |                                        Pet                                        |
| :-----------: | :-------------------------------------------------------------------------------: |
|   Sinônimos   |                             Mascote, animal favorito                              |
|     Noção     | Pet que é domado ou domesticado e mantido como companheiro ou tratado com carinho |
|    Impacto    |                            Pet que necessita de adoção                            |
| Classificação |                                      Objeto                                       |

### Classe Verbo

#### Adotar

|     Nome:     |                                Adotar                                 |
| :-----------: | :-------------------------------------------------------------------: |
|   Sinônimos   |                      Assumir, filiar, legitimar                       |
|     Noção     | Aquele que aceita legalmente alguém como filho ou animal de estimação |
|    Impacto    |                      Permite a adoção de um pet                       |
| Classificação |                                 Verbo                                 |

#### Doar

|     Nome:     |                        Doar                        |
| :-----------: | :------------------------------------------------: |
|   Sinônimos   | Dar, oferecer, presentear, ceder de forma gratuita |
|     Noção     |      Ceder algo seu para alguém gratuitamente      |
|    Impacto    |             Permite a doação de um pet             |
| Classificação |                       Verbo                        |

#### Listar

|     Nome:     |                                    Listar                                     |
| :-----------: | :---------------------------------------------------------------------------: |
|     Noção     | Será exibido ao usuário uma tela com todos os animais disponíveis para doação |
|    Impacto    |         Permite que um usuário indeciso encontre um pet de seu desejo         |
| Classificação |                                     Verbo                                     |

#### Filtrar

|     Nome:     |                                      Filtrar                                      |
| :-----------: | :-------------------------------------------------------------------------------: |
|     Noção     | O usuário irá abrir o aplicativo e poderá filtrar raças, portes e gêneros de pets |
|    Impacto    |                 Permite que o usuário escolha qual pet irá adotar                 |
| Classificação |                                       Verbo                                       |

#### Pesquisar

|     Nome:     |                       Pesquisar                       |
| :-----------: | :---------------------------------------------------: |
|   Sinônimos   |                        Buscar                         |
|     Noção     |             Usuário que pesquisa pelo pet             |
|    Impacto    | Dá a possibilidade de pesquisar por um pet específico |
| Classificação |                         Verbo                         |

#### Entrega

|     Nome:     |                             Entrega                              |
| :-----------: | :--------------------------------------------------------------: |
|     Noção     | Os usuários poderão combinar a busca e entrega de um pet adotado |
|    Impacto    |         Dá a possibilidade de entrega de um pet adotado          |
| Classificação |                              Verbo                               |

### Classe status

#### Status pet

|     Nome:     |                          Status pet                           |
| :-----------: | :-----------------------------------------------------------: |
|     Noção     |                  Status de adoção de um pet                   |
|    Impacto    | Adotante poderá saber se um pet está sendo adotado no momento |
| Classificação |                            Estado                             |

## Comunidade pet

|     Nome:     |                        Status pet                                 |
| :-----------: | :---------------------------------------------------------------: |
|     Noção     |  Conjunto de anunciantes, ONGs, adotantes, voluntários e patrocinadores|
|    Impacto    |     Ajudar a manter o aplicativo e auxiliar usuários e entidades necessitadas |
| Classificação |                 Objeto                                            |

## Referências

> SERRANO, Milene. Arquitetura e Desenho de Software. Apresentação do Power Point. Disponível em: https://aprender3.unb.br/pluginfile.php/2277111/mod_label/intro/Arquitetura%20e%20Desenho%20de%20software%20-%20Aula%20Projeto-DSW%20-%20Profa.%20Milene.pdf. Acesso em: 18 nov. 2022.

> SERRANO, Milene. DSW-BASE - Glossário Léxico. Apresentação do Power Point. Disponível em: https://unbbr-my.sharepoint.com/personal/mileneserrano_unb_br/_layouts/15/stream.aspx?id=%2Fpersonal%2Fmileneserrano_unb_br%2FDocuments%2FArqDSW%20-%20V%C3%ADdeosOriginais%2F02g%20-%20VideoAula%20-%20DSW-Base%20-%20Glossario%20Lexico%2Emp4&ga=1. Acesso em: 18 nov. 2022.
