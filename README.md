# 🚀 System Design Resources 🌟

A comprehensive collection of system design resources, interview preparation materials, and reference architectures. Curated with ❤️ for engineers!

## 📚 Table of Contents
- [🎯 Introduction](#-introduction)
- [🚦 Getting Started](#-getting-started)
- [🧠 Core Concepts](#-core-concepts)
- [🌐 Distributed Systems](#-distributed-systems)
- [🗃️ Databases](#%EF%B8%8F-databases)
- [⚡ Caching](#-caching)
- [🔌 API Design](#-api-design)
- [🧩 Microservices](#-microservices)
- [☁️ Cloud Architecture](#%EF%B8%8F-cloud-architecture)
- [🏗️ System Design Examples](#%EF%B8%8F-system-design-examples)
- [💼 Interview Preparation](#-interview-preparation)
- [📖 Books](#-books)
- [🤝 Contributing](#-contributing)
- [⚖️ License](#%EF%B8%8F-license)

## � Introduction

This repository aims to be your **one-stop shop** 🛒 for all things system design! Whether you're:
- 🎓 Learning system design concepts
- 💻 Preparing for system design interviews
- 🏢 Exploring reference architectures
- 🧑‍💻 Leveling up your backend skills

## 🚦 Getting Started

New to system design? Start here! 👇

- 📖 [System Design Primer](https://github.com/donnemartin/system-design-primer) - The **Bible** of system design
- 🧠 [Grokking the System Design Interview](https://www.educative.io/courses/grokking-the-system-design-interview) - **Best-selling** course
- 📚 [System Design Interview: An Insider's Guide](https://www.amazon.com/System-Design-Interview-insiders-Second/dp/B08CMF2CQF) - **Practical** examples

## 🧠 Core Concepts

### 📈 Scalability
- 🏗️ [Scalability for Dummies](https://www.lecloud.net/tagged/scalability)
- 🕸️ [How to Scale a Web Application](https://www.digitalocean.com/community/tutorials/5-common-server-setups-for-your-web-application)
- 🚀 [Scaling to 100k Users](https://alexpareto.com/scalability/systems/2020/02/03/scaling-100k.html)

### ⚖️ Load Balancing
- 🔄 [Introduction to Load Balancing](https://www.nginx.com/resources/glossary/load-balancing/)
- 🧩 [Layer 4 vs Layer 7 Load Balancing](https://www.nginx.com/resources/glossary/layer-7-load-balancing/)
- 🎯 [Consistent Hashing](https://www.toptal.com/big-data/consistent-hashing)

### 🧩 CAP Theorem
- 🔍 [CAP Theorem Explained](https://www.ibm.com/cloud/learn/cap-theorem)
- 🎨 [Visual Guide to CAP Theorem](https://mwhittaker.github.io/blog/an_illustrated_proof_of_the_cap_theorem/)
- ➕ [PACELC Theorem](https://www.geeksforgeeks.org/pacelc-theorem/)

## 🌐 Distributed Systems

### 🤝 Consensus Algorithms
- 🚣 [Raft Consensus Algorithm](https://raft.github.io/)
- 📜 [Paxos Made Simple](https://lamport.azurewebsites.net/pubs/paxos-simple.pdf)
- 🧩 [Understanding Distributed Consensus](https://blog.yugabyte.com/a-primer-on-distributed-consensus-for-software-practitioners/)

### 🛡️ Fault Tolerance
- ⚠️ [Designing for Failure](https://medium.com/netflix-techblog/fault-tolerance-in-a-high-volume-distributed-system-91ab4faae74a)
- 🔌 [Circuit Breaker Pattern](https://martinfowler.com/bliki/CircuitBreaker.html)
- 🚢 [Bulkhead Pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/bulkhead)

### 🧩 Replication and Partitioning
- 🔄 [Database Replication Explained](https://medium.com/swlh/database-replication-explained-3a4904b479d9)
- ✂️ [Data Partitioning Strategies](https://docs.microsoft.com/en-us/azure/architecture/best-practices/data-partitioning)
- 🧩 [Sharding Pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/sharding)

## 🗃️ Databases

### 🏛️ SQL Databases
- 🐘 [PostgreSQL Documentation](https://www.postgresql.org/docs/)
- 🐬 [MySQL Performance Tuning](https://dev.mysql.com/doc/refman/8.0/en/optimization.html)
- 🧩 [SQL Database Design Patterns](https://www.methodsandtools.com/archive/archive.php?id=83)

### 🚀 NoSQL Databases
- 📊 [NoSQL Database Types](https://www.mongodb.com/nosql-explained)
- 🪐 [Cassandra Architecture](https://cassandra.apache.org/doc/latest/architecture/overview.html)
- 🆚 [MongoDB vs DynamoDB](https://www.mongodb.com/compare/mongodb-dynamodb)
- 🔥 [Redis Use Cases](https://redis.io/topics/use-cases)

### 🆕 NewSQL
- ❓ [What is NewSQL?](https://www.cockroachlabs.com/blog/what-is-newsql/)
- 🕸️ [Google Spanner](https://cloud.google.com/spanner)
- 🪳 [CockroachDB Architecture](https://www.cockroachlabs.com/docs/stable/architecture/overview.html)

## ⚡ Caching

### 🧠 Caching Strategies
- 💾 [Cache-Aside Pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/cache-aside)
- ✍️ [Write-Through vs Write-Behind Caching](https://codeahoy.com/2017/08/11/caching-strategies-and-how-to-choose-the-right-one/)
- 🔄 [Cache Invalidation Strategies](https://www.usenix.org/system/files/conference/nsdi13/nsdi13-final170_update.pdf)

### 🛠️ Caching Solutions
- 🔥 [Redis Documentation](https://redis.io/documentation)
- 🆚 [Memcached vs Redis](https://aws.amazon.com/elasticache/redis-vs-memcached/)
- 🌍 [CDN Caching](https://www.cloudflare.com/learning/cdn/what-is-caching/)

## 🔌 API Design

### 🔄 REST API Design
- 🏆 [REST API Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)
- 🧩 [RESTful API Design](https://blog.restcase.com/restful-api-design-13-best-practices-to-make-your-users-happy/)
- 🔢 [API Versioning Strategies](https://www.freecodecamp.org/news/api-versioning-methods-a-brief-overview-2f9a8478cf82/)

### 🎯 GraphQL
- 🆕 [GraphQL Introduction](https://graphql.org/learn/)
- 🆚 [REST vs GraphQL](https://www.apollographql.com/blog/graphql-vs-rest-5d425123e34b/)
- 🏗️ [GraphQL Schema Design](https://www.apollographql.com/blog/graphql-schema-design-building-evolvable-schemas-1501f3c59ed5/)

### ⚡ gRPC
- 🚀 [gRPC Introduction](https://grpc.io/docs/what-is-grpc/introduction/)
- 🆚 [gRPC vs REST](https://blog.dreamfactory.com/grpc-vs-rest-how-does-grpc-compare-with-traditional-rest-apis/)
- 📦 [Protocol Buffers](https://developers.google.com/protocol-buffers/docs/overview)

## 🧩 Microservices

### 🏗️ Architecture Patterns
- 🧩 [Microservices Pattern](https://microservices.io/patterns/index.html)
- 📖 [Saga Pattern](https://microservices.io/patterns/data/saga.html)
- 🚪 [API Gateway Pattern](https://microservices.io/patterns/apigateway.html)
- ⏳ [Event Sourcing](https://martinfowler.com/eaaDev/EventSourcing.html)
- ↔️ [CQRS Pattern](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs)

### 📡 Service Communication
- 🔍 [Service Discovery Patterns](https://www.nginx.com/blog/service-discovery-in-a-microservices-architecture/)
- 📨 [Asynchronous Messaging](https://docs.microsoft.com/en-us/azure/architecture/patterns/async-request-reply)
- 🕸️ [Service Mesh Explained](https://www.nginx.com/blog/what-is-a-service-mesh/)

### 🐳 Containers and Orchestration
- 🐋 [Docker Documentation](https://docs.docker.com/)
- ☸️ [Kubernetes Concepts](https://kubernetes.io/docs/concepts/)
- 🧩 [Kubernetes Design Patterns](https://subscription.packtpub.com/book/cloud-and-networking/9781789619270/1/ch01lvl1sec13/kubernetes-design-patterns)

## ☁️ Cloud Architecture

### 🅰️ AWS
- 🏗️ [AWS Architecture Center](https://aws.amazon.com/architecture/)
- 🏆 [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/)
- 🧩 [AWS Solutions](https://aws.amazon.com/solutions/)

### 🔵 Azure
- 🏗️ [Azure Architecture Center](https://docs.microsoft.com/en-us/azure/architecture/)
- 🧭 [Azure Application Architecture Guide](https://docs.microsoft.com/en-us/azure/architecture/guide/)
- 🏛️ [Azure Reference Architectures](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/)

### 🅶️ Google Cloud
- 🏗️ [Google Cloud Architecture Framework](https://cloud.google.com/architecture/framework)
- 🧩 [Google Cloud Solutions](https://cloud.google.com/solutions)
- 🏛️ [Google Cloud Architecture Center](https://cloud.google.com/architecture)

## 🏗️ System Design Examples

### 🌍 Real-world Examples
- 📸 [Designing Instagram](https://www.educative.io/courses/grokking-the-system-design-interview/m2yDVZnQ8lG)
- 🐦 [Designing Twitter](https://github.com/donnemartin/system-design-primer/blob/master/solutions/system_design/twitter/README.md)
- 🔗 [Designing TinyURL](https://www.educative.io/courses/grokking-the-system-design-interview/m2ygV4vpzY0)
- 💬 [Designing Facebook Messenger](https://www.educative.io/courses/grokking-the-system-design-interview/B8R22v0wqJo)
- 🎬 [Designing Netflix](https://medium.com/double-pointer/system-design-interview-netflix-95f3399ce31f)

### ⚙️ Specific Components
- ✂️ [URL Shortener Service](https://www.educative.io/courses/grokking-the-system-design-interview/m2ygV4vpzY0)
- 💾 [Distributed File Storage](https://lethain.com/introduction-to-architecting-systems-for-scale/)
- ⚡ [Distributed Cache](https://www.usenix.org/system/files/conference/nsdi13/nsdi13-final170_update.pdf)
- 📰 [News Feed System](https://www.infoq.com/presentations/linkedin-news-feed/)
- 💰 [Payment Processing System](https://stripe.com/blog/payment-api-design)

## 💼 Interview Preparation

### 📝 System Design Interview Guides
- 🧭 [System Design Interview Guide](https://www.interviewbit.com/system-design-interview/)
- 🏆 [How to Succeed in a System Design Interview](https://blog.pramp.com/how-to-succeed-in-a-system-design-interview-27b35de0df26)
- 🗒️ [System Design Interview Cheatsheet](https://gist.github.com/vasanthk/485d1c25737e8e72759f)

### 🏋️ Practice Problems
- 💪 [System Design Problems](https://github.com/donnemartin/system-design-primer#system-design-topics-start-here)
- 📚 [Tech Interview Handbook](https://github.com/yangshun/tech-interview-handbook/blob/master/contents/system-design.md)
- 🎮 [Interactive System Design](https://www.tryexponent.com/courses/system-design-interview)

### 🎤 Interview Experiences
- 📦 [System Design Interview at Amazon](https://www.educative.io/blog/amazon-system-design-interview-questions)
- 🔍 [Google System Design Interview](https://www.educative.io/blog/google-systems-design-interview-questions)
- 👍 [Facebook System Design Interview](https://www.educative.io/blog/facebook-system-design-interview-questions)

## 📖 Books

- 📚 [Designing Data-Intensive Applications](https://www.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/1449373321) by Martin Kleppmann - **The Bible** of system design
- 🧩 [Building Microservices](https://www.amazon.com/Building-Microservices-Designing-Fine-Grained-Systems/dp/1491950358) by Sam Newman
- 💼 [System Design Interview – An Insider's Guide](https://www.amazon.com/System-Design-Interview-insiders-Second/dp/B08CMF2CQF) by Alex Xu
- 🗃️ [Database Internals](https://www.amazon.com/Database-Internals-Deep-Distributed-Systems/dp/1492040347) by Alex Petrov
- 🏛️ [Clean Architecture](https://www.amazon.com/Clean-Architecture-Craftsmans-Software-Structure/dp/0134494164) by Robert C. Martin

## 🤝 Contributing

**We 💖 contributions!** Help make this resource even better!

1. 🍴 Fork the repository
2. 🌿 Create your feature branch (`git checkout -b feature/amazing-resource`)
3. 💾 Commit your changes (`git commit -m 'Add some amazing resource'`)
4. 🚀 Push to the branch (`git push origin feature/amazing-resource`)
5. 🔄 Open a Pull Request

## ⚖️ License

MIT License - see the [LICENSE](LICENSE) file for details.
