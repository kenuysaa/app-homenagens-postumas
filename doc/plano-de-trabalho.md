# PLANO DE TRABALHO

| Nome do Projeto:       | Memórias Póstumas |
| ---------------------- | --------------------------------- |
| Versão:                | 2.0                              |
| Status:                | Prototipação             |
| Executor Principal:    | Guilherme Kenuy Saavedra Nunes    |
| Coordenador Principal: | Andrey Rodrigues                  |

---

# HISTÓRICO DE VERSÕES
| Versão | Descrição                              | Autor                          | Data       |
| ------ | -------------------------------------- | ------------------------------ | ---------- |
| 1.0    | Elaboração do Plano de Trabalho        | Guilherme Kenuy Saavedra Nunes | 10/06/2024 |
| 1.2    | Melhorias e Mudanças de Funcionalidade | Guilherme Kenuy Saavedra Nunes | 13/07/2024 |
| 1.5    | Arquitetura do Sistema                 | Guilherme Kenuy Saavedra Nunes | 16/07/2024 |
|2.0|Prototipação|Guilherme Kenuy Saavedra Nune|24/07/2024|

---

# 1. INTRODUÇÃO
## 1.1 Objeto
Desenvolvimento de uma rede social que conecte familiares e amigos de uma pessoa falecida para compartilharem os sentimentos e lembranças através de publicações textuais, de imagens e vídeos.

## 1.2 Motivação, Justificativa e Oportunidade
**Motivação:** Apesar de outras redes sociais terem uma função para tornar o perfil de uma pessoa falecida em um memorial, o projeto em desenvolvimento será focado para tal função, com uma página do falecido, onde os usuários farão suas homenagens.  
**Justificativa:** O acolhimento entre os familiares e amigos, e o compartilhamento de momentos em mídia que um ou outro não o teriam acesso.  
**Oportunidade:** Uma aplicação para compartilhar, salvar e agrupar lembranças entre os usuários. Além disso, um usuário poderá publicar em seu perfil sua vida antes de falecer, planejando para logo o tornar um memorial com responsáveis escolhidos pelo mesmo.  

## 1.3 Caracterização do Projeto
### 1.3.1 Classe
| Classe                 | Detalhamento                                                                                                                                 |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| Aplicativo WEB e Móvel | Aplicativo WEB para navegadores de internet e mobile desenvolvido para Android, com funcionalidade de publicação de texto, imagens e vídeos. |

### 1.3.2 Enquadrabilidade

| Enquadrabilidade  | Detalhamento                                                                                                                |
| ----------------- | --------------------------------------------------------------------------------------------------------------------------- |
| Aplicativo Social | Cumpre as regulamentações de proteção de dados pessoais, privacidade, acessibilidade digital e práticas culturais e éticas. |

### 1.3.3 Tipo
| Tipo                        | Detalhamento                                                                                                                                       |
| --------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| Desenvolvimento de Software | Criação de um produto de software com sistema de banco de dados em nuvem, com interface focada na experiência do usuário e sistema de privacidade. |

# 2 INFORMAÇÕES GERAIS
## 2.1 Objetivo
Desenvolver uma rede social de homenagens póstumas dedicada a preservar e compartilhar memórias de entes queridos falecidos. Oferecendo ao usuários a funcionalidade de herdar seu perfil a usuários responsáveis para torna-lo um memorial após sua morte. Enfim, oferecendo um ambiente onde amigos e familiares possam se reunir virtualmente para prestar homenagens, compartilhar histórias, fotos, vídeos e recordar os momentos especiais vividos com a pessoa falecida.

## 2.2 Escopo geral
O aplicativo contará com publicações principalmente entre usuários na página do memorial para compartilhar textos, fotos e vídeos em homenagem ao falecido. O sistema terá uma visualização de publicações em sessões, uma maneira de interagir com os momentos mais marcantes da vida da pessoa querida de maneira dinâmica. Controle total sobre quem pode acessar e interagir com o conteúdo, assegurando um ambiente seguro e respeitoso.

### 2.2.1 Escopo Específico
- Criação de Perfil individual.
- Criação da página do memorial do falecido com até 3 perfis responsáveis. Esses perfis poderão aceitar solicitações de acesso a visualização ou publicação de outros usuários.
- O memorial será composto de publicações de diversos usuários. Há destaque a pessoa falecida se o memorial foi criado a base do perfil da mesma antes de falecer.
- Publicação de textos, fotos e vídeos em memória do falecido.
- Implementar ferramentas robustas de controle de privacidade, permitindo que os usuários determinem quem pode visualizar e interagir com o conteúdo compartilhado.
- Permitir que os usuários organizem e destaquem publicações em Sessões de lembranças.
- Integração de ferramentas de edição para publicações.
- Implementação de um layout que permita fácil navegação na Pagina do memorial: Linha de Postagens e Sessões.

### 2.2.2 Escopo Negativo
- O aplicativo não terá financiamento através de anúncios.
- O sistema não incluirá funcionalidades de gamificação para incentivar o uso do aplicativo.
- Não será desenvolvida uma funcionalidade de chat ou mensagens instantâneas entre usuários nesse estágio inicial.

## 2.3 Ambiente de Desenvolvimento
### Ferramentas e Tecnologias
| Tipo                                        | Modelo e Especificações     |
| ------------------------------------------- | --------------------------- |
| Plataforma de repositório e versionamento   | GitHub                      |
| Plataforma de Design                        | Figma                       |
| Ambiente de Desenvolvimento Integrado - IDE | VS code e Android Studio    |
| Linguagem de Programação                    | Kotlin, Python e JavaScript |

## 2.4 Características Inovadoras do Projeto
- O aplicativo permite tornar perfis individuais e suas publicações em paginas de memorial com responsáveis escolhidos pelo mesmo antes de falecer.  
- Republicação de momentos a partir da data especificada ou data de postagem.  

## 2.5 Resultados Esperados
- Uma pagina de memorial personalizável. 
- Armazenamento de informações do usuário e mídia com alta segurança.
- Feedback positivo dos usuários em relação a usabilidade do aplicativo.

# 3 METODOLOGIA DE PROJETO
## 3.1 Estrutura do Projeto
- Scrum Master.
- Equipe de Desenvolvimento.
- Equipe de Design.
- Equipe de Testes.

## 3.2 Equipe de Projeto: Papéis e Responsabilidades dos integrantes
| Responsabilidade        | Profissional                   |
| ----------------------- | ------------------------------ |
| Scrum Master            | Guilherme Kenuy Saavedra Nunes |
| Desenvolvedor Front-End | Laís Samily Xavier de Sousa    |
| Desenvolvedor Back-End  | Manoele Braga Colares da Costa |
| Designer de UX/UI       | Maria Vitória Brasil Campos    |
| Testador de Software    | João Vitor de Oliveira Simões  |

## 3.3 Fases, Atividades e Cronograma
- **Fase I: Especificação – Janeiro/Fevereiro:**
  - Planejamento inicial.
  - Levantamento de requisitos do sistema.
  - Desenvolvimento de Personas.
  - Trabalhar histórias do usuário e seus critérios de aceitação e regras de negócios.

- **Fase II: Inspeção – Março/Abril:**
  - Revisão dos requisitos do sistema.

- **Fase III: Projeto e Arquitetura – Maio/Junho:**
  - Design da arquitetura do sistema através de diagramas dinâmicos e estáticos.

- **Fase IV: Prototipagem e Refinamento – Julho:**

- **Fase V: Prototipagem e Refinamento – Agosto:**

- **Fase VI: Encerramento – Setembro**

## 3.4 Entregas de cada Fase
| Fase                           | Mês               | Entregável                                                                            |
| ------------------------------ | ----------------- | ------------------------------------------------------------------------------------- |
| I. Especificação               | Janeiro/Fevereiro | Personas, Histórias do Usuários e Requisitos do sistema.                              |
| II. Inspeção                   | Março/Abril       | Resolução de defeitos apontados na Inspeção. Mudanças e Melhorias de Funcionalidades. |
| III. Projeto e Arquitetura     | Maio/Junho        | Diagramas de Classes, Diagrama de Sequencia e Modelo C4                               |
| IV. Prototipagem e Refinamento |                   |                                                                                       |
| V. Encerramento                |                   |                                                                                       |

## 3.5 Controle de Mudanças
O monitoramento e controle do escopo do projeto serão realizados a partir das seguintes diretrizes:

- Requisitos do projeto devem ser compreendidos por todos os membros da equipe.
- Todas as questões técnicas, de entregas e do cronograma que a equipe do projeto possui devem ser respondidas.
- Todas as entregas devem ser acordadas pela equipe do projeto e entidades parceiras.
- Todas as informações devem estar atualizadas no escopo e não-escopo.
- Nenhum trabalho fora do escopo do projeto deve ser feito.
- Solicitações de mudança no escopo do projeto devem ser efetivamente comunicadas e compreendidas.
