# BIGDATA 520: BUILDING THE DATA PIPELINE

[UW PCE Course Page](https://bit.ly/49cGnfP)

This course focuses on the process used to acquire, store and process
data for downstream analysis. You'll analyze and compare available
technologies in order to make informed decisions as data
engineers. You'll also learn how to build data processing workflows
using several data stack platforms and design and run data pipelines
for real-world business use cases.

## WHAT YOU'LL LEARN

- How a data lake can enhance the usability of your organization’s data
- Batch and streaming processing using tools such as Spark, Flink and others
- How to use Kafka for stream processing for low-latency and real-time applications
- Data acquisition and modeling techniques
- Pipeline design and integration

## GET HANDS-ON EXPERIENCE

- Organize and store data in a data lake and handle updates and
  changes to your data
- Use Spark to connect to different data sources and process batch and streaming data
- Design and build a complete end-to-end data pipeline to support a
  realistic business case


## Course Outline

- Welcome and Logistics
- NoSQL Part 1:
  - Big Data Technologies Today: an overview
  - Database engine types by approximate level of complexity
  - NoSQL: a motivating example application
  - ACID transaction guarantees
     - Two-phase commit
     - ACID: the good and the bad
  - BASE: Basically Available Soft State
  - The CAP Principle
  - The PACELC Principle
- HBase: a columnar NoSQL database system
  - BigTable and HBase
  - HBase features
  - HBase cluster architecture
  - HBase data architecture and operations
    - Column families, regions, compaction and splitting
    - Table operations
    - Scans and processing
    - Advanced features: coprocessors and custom filters
    - HBase: when to use or not use it
- NoSQL: Reflecting on what we gain and lose
  - The classic RDBMS world: the good and the bad
  - The rise of NoSQL
  - The Faustian bargains of NoSQL
  - How to think about when the gains and losses matter
  - Cassandra: A Dynamo-like NoSQL system
    - Cassandra features, motivation and history
    - When does Cassandra make sense?
    - Cassandra: physical structure, gossip, failure detection
  - Hashing--A quick review
  - Cassandra data architecture
     - Consistent hashing; rings and tokens, virtual nodes
     - Replication strategies
     - Reads and writes: WALs, MemTables, SSTables and guarantees
     - Tunable consistency levels
  - The CQL query language
  - NoSQL Data Modeling: Some HBase and Cassandra Tricks and Punchlines
- Data Pipelines and the Modern Cloud Data Platform
   - Toward the "Modern Cloud Data Platform"
   - Prelude; The Enterprise Data Warehouse
   - The Data Lake
   - The Cloud
   - How "The Modern Cloud Data Platform" Emerged
   - Pieces of a Modern Cloud Data Platform
   - Building Data Pipelines--A First Look
   - Distributed Systems Redux--Their Discontents and Some Coping Strategies
- Modernizing the Data Warehouse
   - The EDW vs. the Data Lake
   - Dealing with Batch Data
   - Modernizing the Data Warehouse
- Beyond the DW--The Lakehouse
   - The Data Lakehouse
   - Lakehouse Implementation
- Delta Lake
   - Delta Lake as Lakehouse implementation
   - The trouble with cloud object stores
   - Storing relational datasets in cloud object stores
   - Delta Lake and ACID guarantees
      - Optimistic Concurrency Control
      - OCC vs Locking
  - Delta Lake under the hood
     - Table storage formats and access protocols
     - Isolation levels, snapshot isolation, serializability
     - Logs and checkpoints
  - Delta lake use cases
- Streaming Analytics, Unified Log Model, and Kafka
   - Streaming data
   - The Unified Log Model: implications and applications
   - Apache Kafka: architecture, use cases, operations
- Processing Streaming Data
   - Record-at-a-time vs. micro-batch processing
   - The Spark Structured Streaming programming model: streaming
     DataFrames
   - Spark Structured Streaming under the hood
   - Streaming sources and sinks
   - Streaming transformations, statefulness and incrementality
   - Windowing streams
   - Joining streams
   - Streams: performance and tuning
- The Data Platform Serving Layer
   - The serving layer: goals, considerations and options
- Production Considerations for Data Platforms
   - The "Lambda Architecture" and the "Kappa Architecture"
   - The Modern Cloud Data Platform: review and ingredients
   - Production considerations: the human parts
   - Workflow management and automation
   - Data governance
   - Open source governance tools: Apache Atlas, Ranger and Knox
   - Important Cloud Services on the Big Three
   
