# BIGDATA 510: INTRODUCTION TO DATA ENGINEERING

[UW PCE Course Page](https://bit.ly/3tMprN7)

In this course, you'll get an introduction to the fundamental building
blocks of big data engineering. You'll learn the foundational concepts
of distributed computing, distributed data processing, data management
and data pipelines. You'll also survey a variety of available data
stack technologies and learn how to run a data processing workflow
through a commonly used platform.

## WHAT YOU'LL LEARN
-	The fundamentals of modern big data stacks, their uses, advantages and limitations
-	How functional programming ideas help with building and using
     systems to store and process big data
-	The foundations of the Hadoop ecosystem and its emerging
     successors like Spark
-	The ins and outs of big data processing via multiple paradigms,
     both storage-bound and in-memory (Spark, Spark SQL, Delta Lake,
     Hive, SQL)
-	The origins, uses and limitations of NoSQL stores (HBase, Redis,
     Elasticsearch, Cassandra, graph-processing systems, etc.)

## GET HANDS-ON EXPERIENCE
-	Apply contemporary distributed computing frameworks to the
     storage, processing and analysis of large data sets
-	Use the MapReduce model and the Spark framework on big data problems
-	Apply principles of functional programming to data storage and analysis

## Course Outline

- Welcome and Logistics
- Introduction to Big Data, Data Engineering, Computing Fundamentals
  and the Cloud
   - Computer systems and performance
   - Virtualization, containers and the Cloud
- Hadoop and the Hadoop Ecosystem
   - Scalable Computing in the Hadoop era (and now beyond?)
   - Distributed computing: why we need it, why it's hard
   - An example, motivating data processing problem
   - The Hadoop Ecosystem: History and Key Components
      - HDFS: the Hadoop Distributed Filesystem
      - Hadoop MapReduce: the original Hadoop distributed computing model
- Big Data Processing with Apache Spark, Part 1
   - MapReduce revisited
   - MapReduce: a giant step backwards?
   - Interlude: Reconsider the Good, Old RDBMS
   - Introducing Spark
   - Spark: Components, Architecture and Ecosystem
- Spark Part 2: Resilient, Distributed Datasets
   - Resilient Distributed Datasets
   - Creating RDDs
   - RDD Transformations: Making new RDDs from Old
   - RDD Actions: Making computations happen on RDDs
   - Saving RDDs
- Functional Programming and Scala
   - Functional Programming: A Brief Aside
      - What is Functional Programming?
      - Immutability, Eagerness and Laziness
      - Referential Transparency and Functional Purity
      - FP and Spark: Why it matters
   - The Scala Programming Language
      - Scala and the Java Virtual Machine
      - Types, type systems and type inference
      - Scala collections
      - Case classes and pattern matching
- Spark Part 3: Partitions, Shuffling and Performance
  - Partitions, Shuffling and Performance
  - The Parable of the Giant, Company Picnic Hoagie
  - Partitions and Tasks
  - Narrow and wide dependencies
  - In-memory operation and performance
  - Persistence and caching
  - Serialization
- Spark Part 4: Spark SQL
   - DataFrames and Datasets
   - Data Sources: Getting data into Spark
   - Spark SQL Architecture: A Bit More Under the Hood
- Spark Part 5: Shared Variables and Miscellaneous Topics
   - Broadcast variables and Accumulators
   - FP: Closures, Lambda Capture and the need for Broadcast Variables
   - The Spark Web UI and Monitoring
   - The Spark SQL Server
   - Writing standalone Spark programs in Scala
- Spark Part 6: Processing Graphs with GraphX and GraphFrames
   - Graphs: definitions, practical applications, tools
   - Spark GraphX: representing graphs as RDDs
      - Transforming graphs and MapReduce
      - "Think Like a Vertex", BSP and Message Passing
      - Pregel and implementing iterative algorithms
  - Spark GraphFrames: graphs as DataFrames
  - Graph algorithms: families and applications
  - Miscellany: serialization; generating random graphs
