# Welcome and Introduction

- Student Tech Talk Requirement
    - Student Presentation Requirement
    - Course Outline, Logistics, Environment

# Building Apps in the Scala Ecosystem

- Akka HTTP: client-side and server-side HTTP stacks
- Akka HTTP's relationships to Akka actors and Akka Stream
- The Akka HTTP design philosophy
- Marshaling and serialization
- Typesafe config
- Responsiveness

# The Play Framework

- Disclaimer: I kind of hate front-end web development
  - the trivial reasons
  - the hopefully less trivial reasons
  - how (and why) to cope
- The Play Framework
   - Creating a new project
   - The MVC pattern
   - Canonical application structure
- Controllers
- Views
- The Play Implementation
   - Non-blocking I/O
   - Controllers, actions and asynchrony
- Streaming responses
- Comet and Websockets
- Database Access
- Forms
- Internationalization
- Testing
- Caching
- Summary of Play pros and cons

# Scala.js

- Disclaimer: Javascript, back to the hate
   - What's good about Javascript?
   - Why you can't avoid Javascript
- Scala.js: compiling Scala source to equivalent Javascript
- Extended Example: another G.D. to do list
- Extended Example: a paint program in your browser
- Extended Example: a fancy clock in your browser
- Scala.js summary of benefits
- jQuery integration
- Dealing with web services
- Testing
- Summary: What Scala-isms compile over into JS via Scala.js?

# CRDTs and Akka Distributed Data

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
