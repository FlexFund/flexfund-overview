# FlexFund - Project Overview
Welcome to FlexFund! FlexFund is a ground-breaking, intuitive software tool designed to influence smart fiscal decision making based on market trends.

## Architecture
The FlexFund project is comprised of a multi-layer data processing pipeline. This pipeline follows a representative pub-sub pattern in which data is ingested and fed into a message broker. The data then undergoes a transformation which is intercepted and fed into a SQL database into a time series. The breakdown of logical architectural components is listed below:

- Data Ingestion Layer
- Message Broker Layer (Apache Kafka)
- Stream Processing Layer (.NET Core Application)
- Production Database Layer (MS SQL Server)
- Presentation Layer (ASP.NET 8.0 Web API)

The below excerpts describe, at a lower level, the implementation details of each logical architectural component.

### Data Ingestion Layer
TODO

### Message Broker Layer
TODO

### Stream Processing Layer
TODO

### Production Database Layer
TODO

### Presentation Layer
TODO
