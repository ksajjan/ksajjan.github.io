# ksajjan.github.io
Project listing

#### Project: Migrating a Monolithic application to a Microservices Architecture

**Duration:** 09/2022 - 11/2023

**Description:**

* Leadership and Technical Expertise:
	* As a team lead, successfully led a team in migrating a complex monolithic application to a modern microservices architecture.
* Architecture Design:
	* Designed and implemented a scalable and modular microservices-based system, improving overall system flexibility and maintainability.
* Code Review and Quality:
	* Conducted regular code reviews to ensure adherence to best practices, maintain code quality, and identify potential issues.
* Technical Guidance: 
	* Provided technical guidance and mentorship to team members, fostering a culture of continuous learning and innovation.

**Key Skills:** Python, Django, Django-DRF, FastAPI, PostgreSQL, Microservices Architecture, Event-based Architecture, Leadership, and Team Management, 
Technical Communication

**Key Achievements:**

* Successfully migrated a large-scale monolithic application to a microservices architecture, improving system scalability and performance.
* Reduced development time and increased time-to-market through the modular nature of microservices.
* Improved system maintainability and reduced technical debt by breaking the application into smaller, independent components.
* Successfully collaborated with cross-functional teams to ensure smooth integration of microservices within the overall system.


#### Project: Android Provising and Management APIs

**Duration:**: 07/2022 - 07/2023

<i>Android Device Provisioning Partner API</i> - This API lets device resellers programmatically manage zero-touch enrollment and is provided by Google. These APIs let you manage the zero-touch enrollment of Android devices.<br>
<i>Android Management API </i>- This API lets you develop an enterprise mobility management (EMM) solution to manage any Android device.

**Key Responsibilities**:

* System Design and Architecture:
	* Developed a comprehensive system architecture, including database schema design, and data modeling to meet project requirements.

* Google API Integration: 
	* Implemented a robust integration with Google APIs, incorporating authentication and rate-limiting mechanisms to ensure efficient and secure data exchange.

* Backend Application Development:
	* Wrote and maintained a backend application using FASTAPI to handle data processing, API interactions, and business logic.

* Deployment:
	* Successful deployment of the application to a production environment.

* Debugging:
	* Debugging of any issue occurring in any environment.

**Key Skill:** Python FastAPI, Uvicorn, Google android provisioning library, Docker, Docker-compose



#### Project: High-Availability Apache Kafka Streaming Platform with Real-Time Analytics

**Duration:** 01/2021 - 07/2023

**Key Skills:** Apache Kafka, Confluent Kafka, Zookeeper, Kafka Connect, Kafka Schema Registry, Kafka REST Proxy, KSQLDB,Docker, Docker-compose, Python, PyKafka, Kafka Consumer & Producer.

**Description**:

This project involved designing, deploying, and managing a highly available Apache Kafka streaming platform for real-time data processing. The infrastructure spanned from test to production environments, ensuring scalability and reliability.

**Key Technologies**:

* Apache Kafka (6-Node Cluster): Distributed messaging system for high-throughput data ingestion and delivery.
* Zookeeper (Single Node): Service discovery and coordination for the Kafka cluster.
* Kafka Connect (Distributed): Connects Kafka to various data sources and sinks.
* Schema Registry: Manages data schemas for serialization and deserialization across different applications.
* REST Proxy: Enables interaction with Kafka via a RESTful API.
* KSQLDB: Stream processing engine for real-time analytics on Kafka data.
* PyKafka: Python Library to use Kafka via Python.

**Key Responsibilities:**

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
* Debugging:
	* Debugging of any issue occurring in any environment.


#### Elasticsearch & Kibana Deployment and Integration

**Duration**: 06/2020 - 03/2023

**Description**:

This project involved setting up a single-node Elasticsearch cluster with Kibana for data analysis and visualization. The deployment spanned from testing to production environments, ensuring a secure and scalable solution.

**Key Skills**: ElasticSearch, Django, Python, Data Modeling, Docker, Docker-compose, Nginx, Kibana, Filebeat, Snapshot lifecycle management, aws s3

**Key Responsibilities**:

* Deployment and Security:
	* Installed and configured Elasticsearch and Kibana on a single node.
	* Implemented authentication mechanisms (basic auth and API key) for secure access.
	* Configured SSL certificates for secure communication across all environments.
* Data Management:
	* Data Modeling tailored for reporting requirements.
	* Developed Django code to handle data indexing and updates within Elasticsearch.
	* Collaborated with front-end developers to integrate Elasticsearch REST API for data visualization.
* Scalability and Resilience:
	* Automate snapshot creation and retention with snapshot lifecycle management (SLM)
	* Implemented a backup and restore policy leveraging AWS S3 buckets for disaster recovery.
	* Built enriched data processing pipelines(ingest pipeline) within Elasticsearch to meet data enrichment needs.
* Observability:
	* Integrated diverse application logs (Django, Nginx, etc.) into Elasticsearch using Filebeat for unified log viewing and searching.
	* Created index patterns and aliases for efficient management and organization of different log sources.
	* Implemented log rotation with ILM (Index Lifecycle Management) to optimize storage and manage log lifecycles.
	* Collected system metrics with Metricbeat for comprehensive infrastructure monitoring alongside application logs.


#### Project - Django Application for Data Requirements(ES-RPC)

**Duration:** 06/2020 - 03/2022

**Description:**

* Developed a Django application to act as a wrapper on top of the ElasticSearch REST API.
* Enhanced data with additional processing and functionalities to meet specific business requirements.
* This application caters to a diverse user base:
	Multiple Clients
	Frontend Dashboard Team
	Internal Support System
	Account Department

**Key Features:**

* API Key Authentication: Ensures secure access to the application.
* Endpoint and Client-Level Data Isolation: Guarantees data privacy for each client and user.
* Real-Time Output Handling: Efficiently processes and delivers moderate amounts of data in real-time.
* Large Data Delivery via Email: For requests exceeding 10k records, a user-friendly email notification system delivers the data to the user's inbox.
* Rate Limiting on REST APIs: Prevents abuse and protects system resources.

**Key Skill**: Python, Django-DRF, Celery, SMTP, SendGrid, elastic search-py


#### Wahoo 

Duration: 12/2019 - 12/2021

**Description**
A small independent API-based application integrated into Datacultr's product Odyseey. It provides an API-level interface for terms & conditions, privacy policy, and FAQs and also holds the records corresponding to user inputs.

currently, this application has a workload of around 8 to 15k requests per day.

**Key Skills:** Python, Django, Rest Framework, REST API

**Key Responsibilities:**

* Converting business requirements to code


#### Project: IQ

**Duration:** 10/2019 - 10/2021

**Project Summary:**

When I joined Datacultr, the first project I was assigned to was Project IQ, a new product that required the development of its backend infrastructure. My primary responsibility was to set up the backend, which involved integrating with end devices that communicated via REST APIs.

One of the key challenges in this project was handling large volumes of raw and improperly formatted data containing numerous special characters from Android devices, which often led to parsing errors. 

To resolve this, I explored the inner workings of Django's request-response cycle and implemented modifications to the incoming requests before they reached the view layer. This involved using different streamer classes to parse the data and customizing some of the built-in streamers to exclude extraneous characters. This experience was invaluable, and the skills I gained were applied to various projects over the years.

For a significant period, the project remained in the demo phase. During this time, I frequently handled data analysis requests for the raw data. I eventually identified patterns and created ready-to-run scripts to streamline this process.

I managed deployments up to the pre-production stage. Initially, we started with SQLite as the database, but we later transitioned to MongoDB for better scalability.

**Key Skills:** Django, Django-DRF, MongoDB, Nginx, uWSGI, Pandas, Numpy, Ipython



#### Project: Hadoop Setup with HiveQL 

**Duration:** 02/2022 - 10/2022
Set up a 3 Node Hadoop Cluster with HiveQL interface.