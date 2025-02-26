# Fichamento do Artigo: Modular Monolith: Is This the Trend in Software Architecture?

SU, Ruoyu; LI, Xiaozhou. Modular Monolith: Is this the trend in software architecture?. In: Proceedings of the 1st International Workshop on New Trends in Software Architecture. 2024. p. 10-13.

## 1. Fichamento de Conteúdo
O artigo explora a arquitetura *modular monolith*, que combina a simplicidade dos monólitos com a escalabilidade dos microserviços. Por meio de uma revisão sistemática da literatura cinza (SGLR), foram analisados 64 estudos publicados entre 2019 e 2023, com o objetivo de compreender como a indústria adota essa arquitetura. O estudo investiga três frameworks principais — *Service Weaver*, *Spring Modulith* e *Light-hybrid4j* — e apresenta quatro casos práticos: *Shopify*, *Appsmith*, *Gusto* e *PlayTech*. A arquitetura modular monolith organiza os sistemas em módulos fracamente acoplados, cada um com limites bem definidos e dependências explícitas, mantendo um único banco de dados e um processo de aplicação unificado. O artigo conclui que essa abordagem é uma alternativa viável aos microserviços, oferecendo simplicidade no desenvolvimento e a flexibilidade para futuras migrações, caso necessário.

## 2. Fichamento Bibliográfico
- **Modular Monolith:** Arquitetura que combina modularidade (baixo acoplamento, alta coesão) e um único processo de aplicação, contrastando com a fragmentação dos microserviços. (pág. 3)
- **Systematic Grey Literature Review (SGLR):** Revisão sistemática da literatura cinza utilizada para investigar como a arquitetura modular monolith tem sido adotada na indústria. (pág. 2)
- **Segregação de módulos:** Cada módulo contém camadas de Domínio, Infraestrutura e API, permitindo desenvolvimento independente sem comprometer a integridade do sistema. (pág. 5)
- **Esquema de banco de dados unificado:** Utiliza um banco de dados centralizado, simplificando a sincronização e evitando a complexidade de bases distribuídas dos microserviços. (pág. 6)
- **Shopify:** Optou por modular monolith para equilibrar a simplicidade de um código-base único com limites claros entre componentes, evitando os desafios iniciais dos microserviços. (pág. 8)
- **Appsmith:** Rejeitou microserviços em favor do modular monolith devido às complexidades associadas a deploys *on-premise*, priorizando a simplicidade operacional para seus clientes. (pág. 9)

## 3. Fichamento de Citações
- " Ultimately, a Modular Monolith represents a holistic and flexible approach to application design, where each module encapsulates specific functionality, fostering ease of development, testing, and deployment."
- " The results show that Modular Monolith is a software architecture pattern that combines the advantages of monolith with microservices architecture."
- " It emphasizes the interchangeability and potential reusability of modules, promoting a clear programming interface between them."
- "Service Weaver is an open-source framework, written by Google, for building and deploying distributed systems."

---

