---
layout: episode
title: "Hexagonal Architectures in .NET"
date: "2014-12-09"
episode_number: "1071"
episode_url: "https://www.dotnetrocks.com/?show=1071"
links:
- title: "Looping Mixer Code"
  url: "http://tinyurl.com/loopingmixer"
- title: "Alistair Cockburn Hexagonal Architecture"
  url: "http://alistair.cockburn.us/Hexagonal+architecture"
- title: "Jeff Palermo Onion Architecture"
  url: "http://jeffreypalermo.com/blog/the-onion-architecture-part-1/"
- title: "Paramore Project"
  url: "http://iancooper.github.io/Paramore/"
---

While at NDC London, Carl and Richard talk to Ian Cooper about hexagonal architectures. Turns out the important part is not the six sides - it's the idea of ports and adapters. Originally talked about by Alistair Cockburn, this is an architectural approach that focuses on being tolerant to testing as well as separating commands from querying. It's not quite Command Query Responsibility Segregation (CQRS), but you can see it from there! Ian discusses testing in a hexagonal architecture and how Test Driven Development (TDD) works so well with the separation of concerns that ports and adapters offers. If you're working on a long lived application that needs to be maintainable, you should be looking at hexagonal architecture!
