# PlantUML Examples
Practical examples of [PlantUML](https://plantuml.com/) diagrams. I also prefer to use an include file like [include.puml](./include.puml) in this repo to make diagrams monochrome by default.

## Domain Model
This domain model depicts a conceptual model of the data objects supporting a online store.
![domain model diagram](out/diagram_examples/Conceptual%20Domain%20Model.svg)
## Use Case
This use case diagram depicts the use cases supporting an online store.
![use case diagram](out/diagram_examples/Use%20Case%20Diagram%20-%20Park%20Entry.svg)
## Activity
This activity diagram is intended to represent how messages in an event-driven architecture are handled, the sequence diagram below it may provide additional context.
![activity diagram](out/diagram_examples/Message%20Processing%20Activity%20Diagram.svg)
![supporting sequence diagram for activity diagram](out/diagram_examples/New%20Resource%20Processor.svg)
## Deployment
This deployment diagram depicts a stateless system that's deployed across multiple physical locations & datacenters with master-master replication of the underlying database.
![deployment diagram](out/diagram_examples/Deployment%20Diagram.svg)
## Sequence
These sequence diagrams depict simple microservice CRUD operations with an underlying document database. 
### GET
![GET sequence diagram](out/diagram_examples/GET%20%20resource.svg)
### POST
![POST sequence diagram](out/diagram_examples/POST%20%20resource.svg)
### PUT/PATCH
![PUT/PATCH sequence diagram](out/diagram_examples/PUT%20PATCH%20%20resource%20{resource-id}.svg)
### DELETE
![DELETE sequence diagram](out/diagram_examples/DELETE%20%20resource%20{resource-id}.svg)
