## Fichamento do Artigo: *Catching Smells in the Act: A GitHub Actions Workflow Investigation*

KHATAMI, Ali; WILLEKENS, Cćdric; ZAIDMAN, Andy. *Catching smells in the act: A github actions workflow investigation*. In: *2024 IEEE International Conference on Source Code Analysis and Manipulation (SCAM)*. *IEEE*, 2024. p. 47-58.

### 1. Fichamento de Conteúdo

Este artigo investiga os "*workflow smells*", características em configurações de *workflows* do *GitHub Actions* (*GHA*) que podem indicar problemas. O objetivo é verificar a existência de padrões para essas ocorrências e avaliar a possibilidade de detectá-las automaticamente. Além disso, explora como os desenvolvedores podem corrigi-las. O estudo empírico foi realizado em 83 projetos no *GitHub*, analisando 10.012 *commits*. Os autores identificaram 64 padrões de mudança frequente em *workflows* de *GHA*, agrupados em 8 categorias, levando à definição de 22 potenciais *smells*. A validação externa, baseada na análise de 32 *pull requests* contendo correções, confirmou a relevância de 7 *GHA workflow smells*. O estudo reforça que *workflows* no *GHA* podem acumular *dívidas técnicas* e que a detecção automática desses problemas pode otimizar e manter a qualidade das configurações. A pesquisa também propõe ferramentas de detecção automatizada e sugere investigações futuras sobre como o contexto do projeto influencia a percepção e a importância dos *smells*, destacando a necessidade de suporte ferramental para *refatoração em tempo real*. 

### 2. Fichamento Bibliográfico

- ***GitHub Actions* (GHA):** Plataforma integrada ao *GitHub* que automatiza *workflows* de *CI/CD*, permitindo a execução de ações baseadas em eventos, como *push* de código e *pull requests*.

- ***Workflow Smells*:** Características ou padrões problemáticos em *workflows* de *CI/CD* que podem indicar problemas ocultos, como má configuração ou ineficiência.

- ***Continuous Integration* (CI):** Prática de engenharia de software que envolve a integração frequente de código em um repositório compartilhado, acompanhada pela execução automatizada de testes.

- ***Continuous Deployment* (CD):** Extensão do *CI* que automatiza a entrega contínua de software, publicando as alterações aprovadas para produção.

### 3. Fichamento de Citações

- "*From these frequent change patterns, we identified and defined a candidate list of 22 potential *GHA workflow smells* (*RQ2*). The external validation confirmed the relevance of six previously discussed *smells* and identified a new *smell*, *Smell 10: “Avoid uploading artifacts on forks”*, highlighting optimization of resource usage.*"

- "*This study provides insight into the existence and relevance of seven *GHA workflow smells*, which have been validated by *open-source developers* through our *contribution study*.*"

- "*Future work should focus on understanding how *project-specific context* influences the perception and importance of *smells*.*"

---

Ajustei tudo para destacar os termos em inglês corretamente! Se precisar de algo mais, é só falar. 🚀
