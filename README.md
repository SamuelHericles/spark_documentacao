# Estudo sobre o pyspark
repositório contendo estudos sobre o framework PySarpk. Nele há apenas 3 notebook que produzi, lendo sobre a documentação do PySpark. Abaixo está algumas das minhas anotações:

O site tem:
  - HOME: apresentação do framework
  - GETTING STARTED: guias básico de uso
  - USER GUIDE: 
  - API REFERENCE: documentação das funções;
  - DEVELOPMENT: queira contribuir com o framework;
  - MIGRATION GUIDE: notas de release, digamos.

- É uma interface do apache spark em python;
- Você não tem permissão de fazer comandos diretos no ambiente, mas pode rodar o shell com comandos para analisar a distribuição de dados;
- PySpark suporta tais ambientes:
  - Spark SQL e DataFrame;
  - Streaming;
  - MLlib (Machine Learning);
  - Spark Core.

- Todas as features do PySpark rodam em cima do Spark Core.
  1. Spark SQL e dataframe: modulo estrutura para processamento de dados em dataframe e podemos fazer consultas em sql
  2. Pandas API no Spark: podemos trabalhar spark no pandas(workload).
  3. Streaming: trabalha com dados do Apache Spark em tempo de execução, ferramenta poderosa.
  4. MLlib: built-in do spark para construir pipelines otimizadas para pipelines de ML;
  0. Spark Core: onde todas as features acima rodam. Chamada de RDD(Resilient Distributed Dataset),
