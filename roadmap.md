```mermaid
flowchart LR
    A[Stage 1: Foundations]:::stage1 --> A1[Programming: Java, Python, Scala]
    A --> A2[SQL, Basic NoSQL]
    A --> A3[Hadoop: HDFS, YARN]
    A --> A4[Git, CI/CD Basics]
    A --> A5[Azure Basics, ADLS Intro]
    A --> A6[Docker Basics]
    A --> A7[Security Basics: HTTPS, OAuth, JWT]

    B[Stage 2: Intermediate]:::stage2 --> B1[Apache Spark, PySpark]
    B --> B2[Spark Streaming Basics]
    B --> B3[HBase Basics - CRUD, Model]
    B --> B4[Airflow, Oozie, ADF]
    B --> B5[Kafka Basics, Connect]
    B --> B6[Data Modeling (Star/Snowflake)]
    B --> B7[Azure HDInsight]
    B --> B8[Kubernetes Basics, Helm]
    B --> B9[Spring Boot Basics, Microservices]
    B --> B10[OAuth/JWT in Spring Boot]

    C[Stage 3: Advanced]:::stage3 --> C1[Spark Optimization, AQE, Skew Handling]
    C --> C2[HBase Advanced - Compactions, Kerberos]
    C --> C3[Kafka Advanced Exactly-once, Flink]
    C --> C4[Azure Databricks, Synapse, Event Hubs]
    C --> C5[Delta Lake, Hudi, Iceberg]
    C --> C6[Azure Purview, Key Vault, RBAC]
    C --> C7[Cosmos DB, Advanced SQL]
    C --> C8[Grafana, Prometheus, ELK, OpenTelemetry]
    C --> C9[Spring WebFlux, API Gateway]
    C --> C10[Data Quality - Great Expectations, Deequ]

    D[Stage 4: Expert]:::stage4 --> D1[Data Mesh, Data Fabric, Lakehouse]
    D --> D2[CI/CD for Data, GitOps (ArgoCD)]
    D --> D3[Performance & Cost Optimization]
    D --> D4[Event-driven Architectures]
    D --> D5[Enterprise Security, Zero Trust]
    D --> D6[GDPR, HIPAA Compliance]
    D --> D7[Observability at Scale]
    D --> D8[ML Feature Stores (Feast, Tecton)]

    classDef stage1 fill:#add8e6,stroke:#333,stroke-width:2px;
    classDef stage2 fill:#90ee90,stroke:#333,stroke-width:2px;
    classDef stage3 fill:#ffa500,stroke:#333,stroke-width:2px;
    classDef stage4 fill:#ffb6c1,stroke:#333,stroke-width:2px;
```
