---
title: My Site
date_created: 2020-04-08 00:00:00
author: Jeffrey Xiao
path: /blog/my_site
tags:
  - Programming
  - Competition
---

## The big enterprise question : ESB vs API

APIs have changed the applications development landscape in this decade. But large organizations
are well invested in SOA (Service Oriented…

* * *

### What are APIs

APIs have changed the applications development landscape in this decade. But large organizations are well invested
in SOA (Service Oriented Architecture) and middleware infrastructure already and such enterprises ask repeatedly
one question:

### What is the difference between an ESB (Enterprise Service Bus) and an API ?

or why shouldn’t we simply use an ESB to create APIs ?

After all ESBs come with a wide range of tooling and automation - gui modeling with drag and drop palettes, built-in
features for mapping various data formats; can easily integrate with back end systems with out of box routing options
and high fault tolerance.
So why not just configure them with APIs ?

We may have to look at what APIs, SOA and ESBs represent conceptually.

API architectures focus on developing a network of well connected domain models, which can be packaged, published,
deployed
& scaled with independent requirements

![](https://cdn-images-1.medium.com/max/600/1*ZzJtb7KKtLkJlvckeR9H2w.png)

SOA creates a stack with a group of services. Each layer is an abstraction and reduces the complexity of the services
below it.
SOA does a good job in reducing the complexities of integrating with external/third-party systems and the need for
service consumers to be aware of it.

ESBs are built into the SOA “middleware” to overcome integration problems between incompatible systems. One of the
systems may be a slow receiver, another may need messages in binary format.

## APIs inherently necessitate being platform independent
          and having less interaction with its runtime / container. They are logical units that
can be replicated and scaled as necessary to accomplish a very focused aspect.

### ESB’s are containers
          which run integration specifications to receive a message from one producer and
transform and transport reliably to multiple consumers.

While there are many technical answers, we need a more intuitive example.

### Comparing ESBs to APIs is similar to comparing Tunnels to Cities

Planning a city requires connecting living spaces, roads, and resources, with specific policies and standards.
It helps in effectively connecting and utilizing independent aspects of an urban architecture for social
and economic benefits.

![](https://cdn-images-1.medium.com/max/600/1*X8vOSmt5Jn1Ok2sZel0fgw.jpeg)

APIs can have a similar interpretation. Every API focuses on a specific aspect of the solution architecture and
provides maximum utilization. API’s transform IT from traditional architectures into independent catalogs of APIs
that can be mixed and matched for specific needs.

Though urban architecture makes city planning easier, natural geography like mountains, water bodies always limit
it’s extend. To overcome any limitation, architects resort to highly technical structures like tunnels, suspension
bridges, etc.

![](https://cdn-images-1.medium.com/max/600/1*qPjXOSzn3KpdA35XgLvdOQ.jpeg)

ESBs and message brokers have the same characteristics of complicated structures like tunnels.
They play an integration role in SOA.

When certain parts of enterprise architecture do not communicate well, ESB’s can provide integration structures
to simplify the passage of message between them.

ESBs provide configurable state machines for messages transported between two incompatible interfaces
(example: legacy products like Mainframes, ERP, etc).

The main aim of ESBs is to reduce the limits of IT Architecture.

The implementation and technology of ESBs can be technically impressive, but there are reasons for why
they cannot consume the whole IT infrastructure.

When large middleware containers run application logic, new application use-cases become tough to be introduced
in that ecosystem. Every new requirement will require additional infrastructural spending.

![](https://cdn-images-1.medium.com/max/600/1*aawwfXT8ome1d6WmQhl1yQ.jpeg)

APIs encourage creation of simplified models which can be applied for various use cases. Every new feature introduced
can be easily decomposed into smaller artifacts.

API catalogs give an understandable documentation. Business Analysts, Consumers, Third party app developers
all work hand in hand.

API economy and monetization takes the benefits of IT infrastructure beyond an organization’s borders.

APIs allow applying different policies for security, roles, data standards, into different parts of an application.
APIs have changed the layout of software architecture from being heavily layered into a highly interactive graph.

Whereas in the case of ESBs, the more they become logically involved in a use-case, the less flexible IT assets
will become.

Tunnels are fascinating. They need technical expertise. But Tunnels are not the same as Cities. They both
have their own functional areas.

By [Deepak Rajamohan](https://medium.com/@deepakrajamohan) on [May 1, 2017](https://medium.com/p/4c463a2bf40c).

[Canonical link](https://medium.com/@deepakrajamohan/the-big-enterprise-question-esb-vs-api-4c463a2bf40c)

Exported from [Medium](https://medium.com) on November 16, 2019.