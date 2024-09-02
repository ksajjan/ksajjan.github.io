# ksajjan.github.io
Project listing 

##### Elasticsearch & Kibana Deployment and Integration

**Description**:

This project involved setting up a single-node Elasticsearch cluster with Kibana for data analysis and visualization. The deployment spanned from testing to production environments, ensuring a secure and scalable solution.

**Key Responsibilities**:

* Deployment and Security:
	* Installed and configured Elasticsearch and Kibana on a single node.
	* Implemented authentication mechanisms (basic auth and API key) for secure access.
	* Configured SSL certificates for secure communication across all environments.
* Data Management:
	* Data Modeling tailored for reporting requirements.
	* Developed Django code to handle data indexing and updates within Elasticsearch.
	* Collaborated with frontend developers to integrate Elasticsearch REST API for data visualization.
* Scalability and Resilience:
	* Automate snapshot creation and retention with snapshot lifecycle management (SLM)
	* Implemented a backup and restore policy leveraging AWS S3 buckets for disaster recovery.
	* Built enriched data processing pipelines(ingest pipeline) within Elasticsearch to meet data enrichment needs.
* Observability:
	* Integrated diverse application logs (Django, Nginx, etc.) into Elasticsearch using filebeat for unified log viewing and searching.
	* Created index patterns and aliases for efficient management and organization of different log sources.
	* Implemented log rotation with ILM (Index Lifecycle Management) to optimize storage and manage log lifecycles.
	* Collected system metrics with Metricbeat for comprehensive infrastructure monitoring alongside application logs.


##### Project - Django Application for Data Requiremnts(ES-RPC)

**Description**:

* Developed a Django application to act as a wrapper on top of the ElasticSearch REST API.
* Enhanced data with additional processing and functionalities to meet specific business requirements.
* This application caters to a diverse user base:
	Multiple Clients
	Frontend Dashboard Team
	Internal Support System
	Account Department

**Key Features**:

* **API Key Authentication**: Ensures secure access to the application.
* **Endpoint and Client-Level Data Isolation**: Guarantees data privacy for each client and user.
* **Real-Time Output Handling**: Efficiently processes and delivers moderate amounts of data in real-time.
* **Large Data Delivery via Email**: For requests exceeding 10k records, a user-friendly email notification system delivers the data to the user's inbox.
* **Rate Limiting on REST APIs**: Prevents abuse and protects system resources.

**Tech-Skill**: Python, Django, Celery, sendgrid, elasticsearch-py


#### Project: High-Availability Apache Kafka Streaming Platform with Real-Time Analytics


**Description**:

This project involved designing, deploying, and managing a highly available Apache Kafka streaming platform for real-time data processing. The infrastructure spanned from test to production environments, ensuring scalability and reliability.

**Key Technologies**:

* Apache Kafka (6-Node Cluster): Distributed messaging system for high-throughput data ingestion and delivery.
* Zookeeper (Single Node): Service discovery and coordination for the Kafka cluster.
* Kafka Connect (Distributed): Connects Kafka to various data sources and sinks.
* Schema Registry: Manages data schemas for serialization and deserialization across different applications.
* REST Proxy: Enables interaction with Kafka via a RESTful API.
* KSQLDB: Stream processing engine for real-time analytics on Kafka data.

Key Responsibilities:

* Deployment and Configuration:
	* Set up a 6-node Kafka cluster and a single-node Zookeeper instance across test, staging, and production environments.
	* Dockerized the entire infrastructure for containerized deployment and management.
* Data Integration:
	* Implemented various Kafka Connect connectors:
	* JDBC source connector for ingesting data from relational databases.
	* File source connector for processing data from files.
	* Elasticsearch sink connector for storing data in Elasticsearch.
	* Utilized Single Message Transformers (SMTs) within connectors to transform incoming messages for improved data quality.
* Real-Time Processing and Analytics:
	* Developed Python producer and consumer applications to interact with the Kafka ecosystem.
	* Implemented KSQLDB for real-time data joins and transformations.
	* Created tables and streams in KSQLDB to redefine and reorganize data keys for efficient processing.
* Monitoring and Alerting:
	* Monitored Kafka consumer lag and set up alerts via Slack to notify of potential issues.
	* Implemented Standard Operating Procedures (SOPs) for deployment and maintenance activities.
* Schema Management:
	* Configured Schema Registry to support multiple serialization formats (Avro, Protobuf, JSON) for data interchange.
* Visualization:
	* Integrated Grafana dashboards for real-time visualization of key streaming metrics.

Tech-Stack: Apache Kafka, Confluent Kafka, Zookeeper, Kafka Connect, Kafka Schema Registry, Kafka REST Proxy, KSQLDB,Docker, Python


### Project: Hadoop Setup with HiveQL 

Setup a 3 Node Hadoop Cluster with HiveQL interface.