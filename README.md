# Network

## Concept

The most basic way to outline of the vision is to describe a graph made up of nodes and edges/links, each node and edge can have basic information stored against it, each new edge or node will emit events that can be listened to, this leads to being able to react to information changes in real time while building a logical representation of the underlying data. 

This graph doesn't need to be stored in a graph database, or be stored in a database at all, it could be an in memory data set. 

This documentation is going to describe the basic structure of the graph, and how the graph can be interacted with.

The intended audience of this documentation is developers looking to implement the graph in their own langauge or infrastructure.

## Why

The target is to be able to define underpinnings to a standard model which can be used across different kinds of networks, 
this could be a social network, or a commercial network used for internal processes, if we're able to support Consumer-to-Consumer, Consumer-to-Business, Business-to-Consumer, and Business-to-Business use cases without breaking any privacy concerns, then we've hit the right mark.

## Privacy 

Data must always be owned by the producer of the data, or authorised parties that are able to modify that data (for example an employee working for a company). 

Data must be in complete control of the data's owner, this includes being able to define the audience of the data and how it is distributed across the internet. 

If a data owner never shares data to another party outside their own host, and doesn't explicitly define that they want their data distributed, then the data should only be retained on that original host. 

If a party hasn't been given permission to specific information, then the information must never be accessible to that party in any way.

## Nodes

A node is a representation of owned or accessible data, this could contain a set of key/value pairs, a file, or a renderable interface. 

A node can be:

- Data
- Subgraph
- Executable Code

### Data

If a node is a data node, then it can take on a few different forms, this depends on the implementation:

- Key/Value pairs
- File
- Static GraphQL object

### Subgraph

A subgraph is a set of nodes and edges from the parent graph, a subgraph can be created by first defining a prototype
of the subgraph and outlining what topology is required to create the subgraph. 

A subgraph can also define additional nodes and edges within its definition. 

A subgraph can also store data against it, defined above in [data](#Data), a subgraph could either expose this additional data, or use it for internal context information for executable nodes, this could also be used to provide environment details (like database urls etc)

### Executable Code

If a node is a node with executable code, depending on the implementation, the executable code could take on the form of:

- A functional process that takes an input and returns a consistent output
- An input only process
- An emitting process

When a executable node is invoked, it will be provided only what is required to run.

These executable nodes can be compared to FaaS functions, commonly referred to as [serverless](https://serverless.com) functions. 

Implementations could chose to invoke these functions within a client, or within a service like [AWS Lambda](https://aws.amazon.com/lambda).

Executable nodes can also store data against it, like a subgraph, defined above in [data](#Data)

Executable nodes can also define a prototype for a required topology by defining itself as a subgraph.

## Contributing

Please see [Contributing](./CONTRIBUTING.md)

## Code of Conduct

This project and everyone participating in it is governed by the [Code of Conduct listed here](./CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [conduct@open-network.dev](mailto:conduct@open-network.dev).

## Licence

The written documentation and source code examples are licensed under the [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) license.