# IT Design Blog

Go to https://defraine.github.io/defraine/



* Command Query Responsability Segregation (CQRS)
* [CQRS+ES](http://fr.slideshare.net/mbild/cqrs-event-sourcing-28292586)
* Lambda vs Kappa Architecture
* [questioning the lambda architecture](https://www.oreilly.com/ideas/questioning-the-lambda-architecture)
* [kappa architecture](http://milinda.pathirage.org/kappa-architecture.com/)
* Data ingestion, data processing, data serving
* Change Data Capture (CDC)
* Real-Time vs Offline, streaming vs batch
* Micro-services
* [Philosophy Unix](https://www.confluent.io/blog/apache-kafka-samza-and-the-unix-philosophy-of-distributed-data/)
* Conway's Law (1967)
* Postel's Law
* Moore's Law - End at 2014
* Multi-cores (2004) < Multi-server (2014) , distributed environment
* [Latency Numbers Every Programmer Should Know](https://gist.github.com/jboner/2841832)
* I love logs
* Kafka = this is a single data(logs) centric platform
* Kafka Streams = Event-driven Micro-services
* Single API
* Web API, not RESTfull API
* [Marble diagrams](http://rxmarbles.com/)
* [Reactive Manifesto](http://www.reactivemanifesto.org/fr)
* Reactive, Non blocking I/O
* [RxJava, RxJS...](http://reactivex.io/)
* [Event Sourcing](http://slides.com/ugobourdon/eventsourcing#/)
* Retro-Action Loop with Command, Event, State artifacts and two functions : decide, apply.
* EventStore
* DDD - Domain Driven Design by Eric Evans
* Boundary Context, Ubiquitous Language
* A single common language is hard, and we have various Boundary Contexts.
* [DDD vite fait !](http://blog.infosaurus.fr/public/docs/DDDViteFait.pdf) 
* Functional Reactive Programming (FRP)
* [Java 8 - API Stream](https://zeroturnaround.com/rebellabs/java-8-streams-cheat-sheet/)
* Callback Hell
* AVRO
* Kafka : public topic vs private topic
* Kafka : data on inside vs data on outside
* Kafka : make data on outside a first class citizen
* Command Event : a single writer
* Event is a fact in the past, not a action to do in the future !
* Kafka = Hub and Spoke with Indexation, Denormalized Views, Analytics, Distributed Cache, Fraud Detection...
* Pub/Sub, Post & Forget !
* Kafka : write-ahead log (WAL) = write in log at first, then flush into data store
* Kafka : replaying logs, keep two systems in sync
* Vertical vs Horizontal Scalability, linear performance/cost 
* Commodity hardware, design for failure, cattle vs pets, replication, fault-tolerant system
* Sharding, data partition
* Distributed Computing, MapReduce pattern
* Principle of Colocality Data/Computing
* Master-Slave vs Masterless topology

