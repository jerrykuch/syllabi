# SCALA 220: Reactive and Concurrent Programming in Akka

# Introduction, Road Map and Setup

    - Course logistics
    - Why concurrency matters more as Moore's Law taps out
    - Amdahl's Law
    - The challenges of traditional "threads and locks" based
      concurrency
      - Race conditions, livelock and deadlock
    - Concurrent programming and I/O
    - Distributed Systems and Their Discontents
    - Why Build Distributed Systems?
    - The Fallacies of Distributed Computing
    - Reactive Programming
    - Actors and the Message Passing Approach

# The Actor Model
   - "One Ant Is No Ant"
   - What makes an actor and actor?
   - Creating actors in Akka
   - Hiding state
   - Best practice: specialize messages and exceptions
   - Dissecting an Actor and the ActorContext
   - How actors start, stop and run
   - The semantics of message passing
   - Delivery guarantees and reliable messaging
   - Failure handling with actors

# Failure, Supervision and the Actor Lifecycle
   - Domain Driven Actors and Work Distribution Actors
   - Handling failures in asynchronous, concurrent, distributed
     systems
   - Supervision of actors
   - Resilience and containing failure
   - Supervision hierarchies and supervisor strategies
   - The actor lifecycle

# Distributed Actors
    - The curse of the network
    - RPC and its discontents
    - Actors and remoting
    - Actor references, paths and addresses
    - The ActorRef and types of ActorRefs
    - ActorPath: finding one's way on the network
    - ActorPaths vs. ActorRefs
    - Logical and physical ActorPaths
    - Distributed actors and remote deployment of actors
    - Mailboxes and dispatchers

# Clustering
    - Akka clustering as dynamic membership service
    - Gossip protocols, probabilistic failure detection, vectorclocks
      and a simple CRDT
    - Nodes, clusters and leaders
    - Cluster membership lifecycle

# Persistence
    - Actor persistence and fault tolerance
    - Event sourcing
    - The PersistentActor trait
    - Journaling and snapshots
    - Commands and events
    - Serialization issues

# Routers
    - Routers
    - Routers for load balancing and scaling
    - Pool and group routers
    - Types of routing logic

# Streams
    - Akka streams and reactive streams
    - Flows and graphs
    - Materialized values
    - Stream materialization
    - Comparing streams and actors
    - Use cases and examples

# Distributed Data and CRDTs
    - CRDTs and synchronizing data
    - Eventual consistency
    - Availability
    - Partition tolerance
    - The CAP Principle
    - CmRDTs / operation-based CRDTs
    - CvRDTs / state-based CRDTs
    - An algebraic view of CRDTs
    - A portfolio of known, simple CRDTs
    - CRDTs in Akka Distributed Data
    - The Akka Cluster Replicator
    - Write consistency levels
    - Akka Distributed Data: provided CRDT types

# System Design Tips, Strategies, and Conclusion
    - What tools have we acquired so far?
    - The reactive manifesto redux
    - Performance vs. scalabiltiy
    - Responsiveness
    - Elastic scaling
    - Cascades and their costs
    - Circuit breakers
    - Bulkheading
    - Failure detection and replacement
    - A bit of queueing theory
    - Measuring actor performance
    - Attacking bottlenecks (in queueing theory terms)
    - Threading woes and dispatchers
    - Thread releasing and context switches

# Term Project

