# aws-msk-snowflake-pipeline
Real-time data pipeline using AWS MSK and Snowflake Kafka Connector to stream Kafka topics into Snowflake tables.
This project demonstrates a real-time data streaming pipeline from AWS MSK (Managed Streaming for Apache Kafka) to Snowflake using the Snowflake Kafka Connector.

It enables continuous ingestion of Kafka topic messages directly into Snowflake tables for analysis, reporting, or downstream processing.

🚀 Key Features
🟡 Real-time Kafka-to-Snowflake streaming

📡 Deployed using EC2 and Snowflake Sink Connector

🔄 Configurable buffer size, flush intervals, and record limits

📊 Automatic Kafka topic to Snowflake table mapping

🔐 Secure authentication using private key integration

⚙️ Technologies Used
Apache Kafka (AWS MSK)

Snowflake

Snowflake Kafka Connector

EC2 (SSH & deployment)

Kafka Topics & CLI
