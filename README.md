# [iDempiere micro](https://idempiere-micro.github.io/) - open source headless serverless ERP and CRM microservices compatible with [iDempiere](http://www.idempiere.org/)

When building a new business system there is a lot of stuff you can reuse. Most of the well-known libraries give you reuse on the technological level: logging, users, access control etc.

We decided to raise the bar a little bit higher and give software developers a possibility to reuse business entities from one of the most advanced open source Enterprise Resource Planning (ERP) and Customer Relationship Management software (CRM) - [iDempiere](http://www.idempiere.org/).

## What is iDempiere micro
[iDempiere micro](https://idempiere-micro.github.io/) is an open source project to build headless serverless ERP and CRM microservices to be used by custom frontend applications like e-shops, specialized vertical applications, IoT appliances etc.

## How it works
Microservices are small application running usually in a cloud environment like Kubernetes, IBM Cloud, Microsoft Azure or Amazon Web Services (AWS). They are quite small in terms of lines of code (LoC), are loosely coupled (you can update them independently) and have very small requirements on the underlying operating system.

[iDempiere micro](https://idempiere-micro.github.io/) microservices are standard Java executable JARs that can run on any Java 1.8+ capable Docker image like [openjdk:8-jre-alpine](https://hub.docker.com/_/openjdk).

All the microservices share the same iDempiere database leveraging [the shared database pattern](https://microservices.io/patterns/data/shared-database.html). This also allows adding the microservices easily to existing iDempiere installation or using the full feature iDempiere](http://www.idempiere.org/) application to fulfill tasks not covered by the microservices.

## Want to know more?

[Explore the iDempiere Micro Wiki pages.](https://github.com/iDempiere-micro/Docs/wiki)

[Have a look at the samples](https://github.com/iDempiere-micro-samples)
