## Fichamento do Artigo: Evaluating Test Quality in GitHub Repositories: A Comparative Analysis of CI/CD Practices Using GitHub Actions

SILVA, Edson Campolina et al. Evaluating Test Quality in GitHub Repositories: A Comparative Analysis of CI/CD Practices Using GitHub Actions. In: Workshop de Visualização, Evolução e Manutenção de Software (VEM). SBC, 2024. p. 45-55.

### 1. Fichamento de Conteúdo

O artigo investiga a qualidade dos testes em repositórios do *GitHub* que implementam ou não as práticas de *Continuous Integration* (*CI*) e *Continuous Delivery* (*CD*), comparando repositórios que utilizam o *GitHub Actions* como ambiente de *CI/CD* com aqueles que não adotam essas práticas. Para avaliar a qualidade da suíte de testes, foi realizado um estudo quantitativo, minerando repositórios do *GitHub* com *Python* e aplicando filtros, como o uso da linguagem *Java*, recorte temporal e a presença de testes automatizados com *GitHub Actions*. Foram detectados *test smells*, analisados *bug issues* e o tempo necessário para corrigi-los. O estudo abrangeu 651 repositórios que usam *GitHub Actions* e 289 que não utilizam *CI/CD*. Foram identificados 1.648.254 *test smells* nos repositórios com *GHA* e 709.680 nos repositórios sem *CI/CD*. No entanto, ao considerar a métrica de *test smells* por *lines of code* (*LOC*), as medianas foram próximas: 0,1495 para repositórios com *GHA* e 0,1515 para os sem *CI/CD*. Os resultados mostram que 86,18% dos *bug issues* foram fechados nos repositórios que utilizam *GitHub Actions*, em comparação com 89,20% nos demais. O tempo mediano para resolver *bug issues* foi de 156 horas nos repositórios com *GitHub Actions* e 178 horas nos sem *CI/CD*. Após testes estatísticos, não foi possível afirmar que o uso do *GitHub Actions* melhora a qualidade dos testes implementados.

### 2. Fichamento Bibliográfico
- ***GitHub Actions* (GHA)**: Plataforma integrada ao GitHub que automatiza workflows de CI/CD, permitindo a execução de ações baseadas em eventos, como push de código e pull requests.
- ***Test Smells:*** Testes mal projetados que afetam negativamente a qualidade das suítes de testes e do código. 
- ***Continuous Integration* (CI):** Prática de engenharia de software que integra mudanças de código continuamente em um repositório compartilhado, acompanhado por testes automatizados.
- ***Continuous Delivery* (CD):** Extensão do *CI* que automatiza a entrega contínua de software, publicando as mudanças aprovadas em produção.

### 3. Fichamento de Citações

- "*Test smells are poorly designed tests that negatively affect the quality of test suites and code.*"
- "* This quantitative study aims to measure the quality of tests in GitHub repositories that use GitHub Actions as a CI/CD tool compared to those that do not use CI/CD. We use test smells to evaluate the quality of tests*"
- "*The median time for resolving bug-type issues was 156 hours in repositories using GitHub Actions, compared to 178 hours in those without CI/CD.*"
- "*After statistical tests, it was not possible to state that the use of GitHub Actions in the repositories improves the quality of the tests implemented.*"

