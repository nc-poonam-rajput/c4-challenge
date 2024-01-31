# C4 Diagram Challenge

C4 diagrams are 4 layers of increasing detail outlining the architecture of a software system.

It can be used on:

- Software development projects
- System migrations
- Open source projects
- Microservice-centred projects
- Enterprise-level projects

C4 diagrams are used by software engineers, architects, and stakeholders involved in the design and implementation of software systems.There are 4 layers and each layer goes into further detail of a specific aspect of the system, layer 1 is the most "zoomed-out" and layer 4 being the most "zoomed-in".

These kinds of diagrams use other architecture modelling techniques like Unified Modeling Language (UML) or Entity-Relationship Diagrams (ERDs) to break the architecture down into the mode decomposed layers (layer 3 or 4).

## Why does this get used?

We might see a software architecture diagram get used:

- To give the whole software development team a solid high-level overview of the software system they're working in/on. It's great for agile working and rapid prototyping (Internal Dev 👀).

- To provide a common language for developers, stakeholders, and architects to discuss and understand the system. It's great for stakeholders to have a less complex and easier to digest view of what's being worked on. The fact it's in layers means you can introduce more detail if need be.

- To flexibly represent a system of large or small size. It's cool to be able to apply a diagram to the smallest project\* or the largest system.

\*Although sometimes applying layered abstraction to a very simple design might be hard, we might risk over complicating it. My advice is to accept some diagrams will be v simple, don't overcomplicate it if it doesn't neded it.

## What actually is it

Here are the layers involved (the 4 Cs):

1. Context Diagram (Layer 1):
   Shows the system in relation to users and other systems (if relevant). High-level view of the system and interactions with external entities.

2. Container Diagram (Layer 2):
   Decomposes the system into interrelated containers. Each container represents an application or data store.

3. Component Diagram (Layer 3):
   Decomposes containers into components and relates the components to other containers/systems

4. Code Diagram (Layer 4):
   Additional details about the design of elements that cnan be mapped to code. At this point relying on UMLs and ERDs
