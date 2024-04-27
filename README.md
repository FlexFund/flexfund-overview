# FlexFund - Project Overview
Welcome to FlexFund! FlexFund is a ground-breaking, intuitive software tool designed to influence smart fiscal decision making based on market trends.

## Architecture
The FlexFund project is comprised of a multi-layer data fabric. The data fabric is based on a message-driven architecture in which data is ingested and fed into a message broker. Batch workflows are triggered nightly to perform analysis and inferencing:

- Data Ingestion Layer (.NET CLI Application)
- Message Broker Layer (Apache Kafka)
- Batch Processing Layer (Prefect/Python Application)
- Production Database Layer (MS SQL Server)
- Presentation Layer (ASP.NET 8.0 Web API)

The below excerpts describe, at a lower level, the implementation details of each logical architectural component.

### Data Ingestion Layer
The data ingestion layer is a small microservice which will subscribe to messages from the Confluent stream data and ingest them into the SQL server database.

### Message Broker Layer
The core of the application's event-driven approach resides on Apache's Confluent/Kafka broker system.

### Batch Processing Layer
The batch processing layer is a Prefect application which pulls new data nightly for processing and to perform routine inferencing on new datasets.

### Production Database Layer
TODO

### Presentation Layer
TODO

## Key Concepts
This project is intended to demonstrate proficiency with key concepts such as batch processing, web application development, relational database systems and security, and technical competency with the Microsoft ASP.NET stack. There are additional AI-centric core concepts demonstrated such as Linear Regression using production-grade pretrained models as well as the use of LLMs to generate AI summaries. This is used to provide additional value thru inferencing techniques to the end user.
