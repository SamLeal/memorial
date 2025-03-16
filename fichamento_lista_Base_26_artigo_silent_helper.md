# The Silent Helper: The Impact of Continuous Integration on Code Reviews

CASSEE, Nathan; VASILESCU, Bogdan; SEREBRENIK, Alexander. The silent helper: the impact of continuous integration on code reviews. In: 2020 IEEE 27th International Conference on Software Analysis, Evolution and Reengineering (SANER). IEEE, 2020. p. 423-434.

## 1. Fichamento de Conteúdo  

Este artigo explora o impacto da adoção de *Continuous Integration* (*CI*) nos aspectos sociais do desenvolvimento de software, com foco específico em revisões de código, e tem como objetivo entender se a comunicação e os *updates* de *pull request* diminuem ou aumentam depois da implantação da integração contínua. Por meio de um estudo empírico em 685 projetos do *GitHub* que adotaram o *Travis-CI*, utilizando *Regression Discontinuity Design* (*RDD*), o artigo compara variáveis de revisão de código e como as discussões em *pull requests* mudaram com essa mudança. Os resultados indicam que, com a implementação do *CI*, há uma redução no número de comentários; essa redução é, em média, de 1 comentário de *review* por *pull request*, sugerindo que o *CI* atua como um "*silent helper*", permitindo que os desenvolvedores realizem a mesma quantidade de trabalho com menos comunicação. Além disso, o estudo destaca que, embora o número de comentários diminua, a quantidade de alterações no código durante as revisões permanece constante, indicando que o *CI* reduz a carga de comunicação sem afetar o esforço de desenvolvimento.

## 2. Fichamento Bibliográfico  
- ***Continuous Integration* (CI):** Prática de engenharia de software que automatiza e executa frequentemente etapas de *build* e *test*, facilitando a integração de software.
- ***Regression Discontinuity Design* (*RDD*):** Método de pesquisa usado para estimar o efeito causal de uma intervenção, aproveitando uma variável de corte para comparar os resultados antes e depois da intervenção. É especialmente útil em estudos onde a randomização não é possível.
- ***Travis-CI*:** Serviço de *CI* baseado em nuvem amplamente utilizado em projetos de código aberto no *GitHub*.  
- ***Code Review* (Revisão de Código):** Processo essencial para a qualidade do software, funcionando como um mecanismo de controle em comunidades de código aberto, especialmente quando as contribuições vêm de colaboradores externos.  
- ***Silent Helper* (Auxiliar Silencioso):** Metáfora utilizada para descrever o papel do *CI*, que auxilia os desenvolvedores ao reduzir a necessidade de comunicação explícita durante as revisões de código.  

## 3. Fichamento de Citações  

- "*We observe that with the introduction of CI, pull requests are being discussed less.*"  
- "*On average CI saves up to one review comment per pull request.*"  
- "*In presence of CI developers perform the same amount of work by communicating less, giving rise to the idea of CI as a silent helper.*"  
- "*The number of comments per code review decreases after to the adoption of continuous integration, while the number of changes made during a code review remains constant.*"
