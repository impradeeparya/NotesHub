# Introduction to Cosmos DB
Cosmos DB is an Azure offering that stores documents, which are essentially JSON objects.

## Document Structure: 
Documents in Cosmos DB resemble rows in a relational database but are structured like JSON, allowing for nested objects and arrays.
## Schema Flexibility: 
Unlike traditional databases, Cosmos DB does not enforce a fixed schema, allowing developers to add or modify data fields dynamically.
## Geographical Replication: 
Cosmos DB supports geographic replication, enabling data to be replicated across multiple regions for improved performance and availability.
## Performance and Scalability: 
Cosmos DB is highly performant and scalable, with options for defining compute units and auto-scaling based on demand.
## Deployment Options: 
Cosmos DB offers various deployment options, including a free tier, provisioned throughput, and serverless mode.
## Global Data Access: 
Through geographical replication, Cosmos DB enables low-latency access to data from distributed applications deployed across different regions.
## Horizontal Scaling and Sharding: 
Cosmos DB implements hyperscale and sharding by default, allowing for horizontal scaling of databases while maintaining high performance.
## Querying Data: 
Cosmos DB supports querying data using SQL, making it compatible with existing applications and databases like Azure Table Storage, Gremlin, and MongoDB.
## Refactoring Applications: 
Developers can easily refactor existing applications to work with Cosmos DB, leveraging its fully managed database service for various data storage needs.

# Data Models:

## Document Model: 
> The document model allows you to store semi-structured data as JSON documents. This is similar to how you would store data in MongoDB.
## Key-Value Model: 
> Ideal for scenarios where you need fast access to data based on keys.
## Column-Family Model: 
> Suitable for storing and querying data in columnar format, commonly used in big data and analytics scenarios.
## Graph Model: 
> Designed for applications that need to represent and query relationships between data entities using graph structures.
