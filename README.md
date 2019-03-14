# Network

## Concept

A persons life is a network of events, people, communication, trust, social networks should be social, which also means it needs to be a community, or many communities working together. 

Each community lives by a code of conduct, this could either be written in law, or written by a committee for an open source community, networks have specific interactions that can happen, for example a customer could contact a company, but a company shouldn't be able to contact a customer out of the blue, unless the customer signed up to specific advertising. 

A community itself could be a company, that wants to advertise directly to other companies. 

Advertisement must be shown only in the correct context though, for example don't advertise to people that just work at the store, or don't advertise to teens, the community could define these rules for the community, or suggest defaults. 

A user is a person who has certain information available to see for specific people. 
If they want to add information like a picture to their profile, then they can, and then set the access allowed to their picture. 

A user can post statuses, or blog posts, or stories, they can allow people to comment, or enable advertisements which are automatically filtered based on the viewer (restrictive rather than suggestive), a user can opt out of advertisement, but with the knowledge that the creator won't receive anything from it. 

People can post pictures for the public, or they can make it private for one or more groups of people, specific people can have access via a paid group depending on who is allowed to see it. 

This all works by being able to control how your network works. 

## Timeline example

Lets say we have a timeline, as a company we have developed to variations of a status timeline, one that displays statuses in chronological order, and another that is "interest optimised". 

We wouldn't be able to offer the interest optimised version if 

a) the user didn't provide interestes
b) the user just wanted to see in chronological order

Once the user has selected this option, they won't be asked again if they want to change, they can get suggestions from the community on how to add that interface, or go into company variations and add it back.

A person or company could develop a new timeline, and they could something that is paid for, like a timeline with ads, or a timeline with a pay monthly, or they could have proof of work timelines where someone performs a specific task and receives payment....

## Chat example

A user finds a person, they could either follow the persons statuses, or public activity, or blog posts etc, or they could become friends. 

A person can decide if someone can start a chat based on how they are connected, for example:

- public
- following
- part of a group (free and/or paid)
- someone you have mutually connected by scanning public keys etc, or received a key from somewhere specific (which can be disabled after a certain time or left enabled)

A chat does a specific set of things, for example once you start a chat, you can share actions in the chat

A chat would just be a stream of realtime, or async communication

A company could publish when someone from the company has seen the users message
A person could disable the seen function

A person could receive certain messages via a text message
A person could receive certain messages via an email

A person could receive certain messages via an app, if it was a machine to machine communication 

## Extensability & Trust

If a person or company publishes an algorithm for usage, the algorithm has to be published as open source. 

The community can decide if an algorithm isn't doing what it is supposed to do. 

There will be levels of trust, and moderation throughout the community. 

If there is a decision that is made by a set of moderators, then the decision has to be public to those who were able to connect to that algorithm or node, or whatever the data may have represented. 

If there was no person or company attached to that data, then no one needs to be notified. 

A company can be assigned moderation "tokens" by the community.

As the tokens get distributed more, the more expensive it comes for the company give out those decisions, each ledger entry is currency. 

The usage of each token gets re-assigned after a certain cut off period, depending on how widespread the data was, and how many tokens were used, the community can say that a company has so much power over those kinds of decisions about non related information. 

## Private spaces

Spaces can be private, encrypted, and with no liablility to us, the company, for these private spaces, the data is hosted on the users own infrastructure, they could either host a version of this software, or use a company hosted version, or have something completely offline or just on their local network. 

Spaces should be considered peer to peer rather than single nodes. 

I think maybe companies owning all the infrastructure is a bit horse shit. 

Maybe we should have it where a company can host specific nodes only on their networks, this means that the company could offer a specific proprietery node or something. 

The reason I want to set it up like this is that in development we work with projects like this all the time, we have generic building blocks and we work on top of those building blocks, then we want to develop with someone else, so we share through git, but we sign that we sent it and some other person can receive it, but we have an intermediatry server. 

Something I need to think about a lot more though. 

I want people to be able to be in control of their own data. 

This can extend to learning etc and schools, even parents and kindergardens etc. 

## Cost factors

Because a someone needs to pay for a server, and pay for electricity etc, each transaction a user makes actually costs money. 

For example a transaction to list available statuses to read will take maybe 4ms which costs a specific amount of CPU host etc etc. 

We would need to know the cost of each transaction beforehand, each thing planned to an absolute unit. 

If you are a company, and you want to appear in those advertisments, you would need to pay for that compute time, and also extra for either costs of development, infrastructure work, or to pay for newer users to experience add free for a while. 

Essentially the platform pays for the platform, and the development of the platform. 

The platform pays for upgrades for speed, reduction in costs, reduction in operating costs, and increasing the standards of privacy and transparency. 

## Open Decisions

I think something that would be vital is being able to give up the platform, to the platform, after a specific period in time the platform can either be handed to the people that use the platform, or they could vote to allow specific top decisions, imagine like a country voting on a referendum. 

Specific voting could be maybe by companies with stakes in a specific algorithms or **public** decisions, or by people either annoymously, or publicly. 

Some things need a bunch of voices and a network around the decisions, and some others are things that would be made by a group of designers working with developers. 

These groups of decisions can be seperated or combined to create the correct set of permissions for specific things.

Open decisions go on the ledger and are set in stone, if the decision is private then a hash of a private message could be recorded as proof of a decision being made.

### Open decisions in a company context

A decision could be made to assign a specific task to a user, the decision would be encrypted, the hash would be stored, and then the user would receive the message, the user would check that the message is on the ledger using the same algorithm and then would read the message. 

A ledger could be built by a user locally as well, as a user could be sent the message and a new hash for the ledger, or ledger _block_, this creates a chain of blocks locally and externally. 

Specific types of communications will force the user to split the block locally and the receiving ledger would do the same. 

If a decision didn't reach a specific party for whatever reason, the parties ledger is not changed. 

## Contributing

Please see [Contributing](./CONTRIBUTING.md)

## Code of Conduct

This project and everyone participating in it is governed by the [Code of Conduct listed here](./CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [conduct@open-network.dev](mailto:conduct@open-network.dev).

## Licence

The written documentation and source code examples are licensed under the [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) license.