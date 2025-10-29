## BIG DATA ARCHITECTURE & DATA INTEGRATION
Atendendo aos requisitos de coleta, ingestão, armazenamento, transformação, consumo e orquestração: 
### 1) Uso de ferramenta de ETL ou ingestão (como PIG, Sqoop, Knime, Data Factory, Glue, Data Fusion ou semelhantes) - Respeite a Arquitetura Proposta
- Copie/Colete o arquivo com os dados de origem para o ambiente de armazenamento (data lake) definido, como por exemplo: Hadoop HDFS, Azure Blob Storage, AWS S3, Google Cloud Storage ou similares.
- Esse porcesso deverá conter a orquestração de todo o pipeline ou fluxo de dados realizado.
- Carregue os dados do data lake utilizando a ferramenta de ETL. ou de ingestão. Prepare e estruture o arquivo para que ele possa ser carregado em um ambiente de dados estruturados, caso não esteja estruturado (relacional ou serverless SQL) preparando para consumo. Exemplos: Apache Hive, Azure Synapse, Google BigQuery, AWS Redshift, AWS Athena.
- Para essa etapa de estruturação, processamento lógica e preparação, utilize ferramentas como PIG, Python, Spark ou ferramentas equivalentes. Respeite a Arquitetura Proposta
- Copie o arquivo preparado e gerado para o ambiente local. O nome do arquivo deve seguir o padrão RM9999, onde RM9999 corresponde ao número do RM do representante do grupo.
- Crie um arquivo PDF contendo as evidências das operações realizadas.

### 2) Uso de ferramentas de dados estruturados (SQL) para consultas - Respeite a Arquitetura Proposta
- Aqui, o arquivo pós-transformação, análise e tratamentos pode ser consumido diretamente do data lake (storage) ou pode ser carregado, via ferramenta de ETL/ELT, para um ambiente relacional.
- Carregue o arquivo gerado pela ferramenta de ETL no ambiente SQL ou relacional.
- Utilizando ferramentas como Apache Hive, Azure Synapse, AWS Redshift, AWS Athena, Google BigQuery, entre outras, realize uma análise exploratória dos dados, contemplando:

        a) Contagem de registros
        b) Visualização de uma amostragem dos dados (as dez primeiras linhas)
        c) Descrição dos campos da tabela
        d) Contagem de valores distintos
        e) Estatística descritiva (média, mínimo, máximo)
        f) Distribuição de frequência (contagem dos elementos em cada campo)

Obs.: Apresente códigos, comandos, prints de workflows ou adaptações da arquitetura que entender necessários para entendimento da solução proposta.

### NOTA: 100

### FEEDBACK:
Primeiramente parabéns ao grupo pela iniciativa aceitando o desafio de conhecer novas ferramentas (AWS) para a entrega do projeto. Todo o trabalho realizado de orquestração, coleta, ingestão (data lake) análise e ou ETL, foi realizado com excelência, o grupo observou e aplicou temas importantes de uma arquitetura de Big Data, como escalabilidade, flexibilidade e velocidade. Parabéns e agradeço a dedicação e empenho!
