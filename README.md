# C4 Diagram Challenge

C4 diagrams are 4 layers of increasing detail outlining the architecture of a software system.

It can be used on software projects of all sizes.

C4 diagrams are used by software engineers, architects, and stakeholders involved in the design and implementation of software systems. There are 4 layers and each layer goes into further detail of a specific aspect of the system, layer 1 is the most "zoomed-out" and layer 4 being the most "zoomed-in".

These kinds of diagrams use other architecture modelling techniques like Unified Modeling Language (UML) or Entity-Relationship Diagrams (ERDs) to break the architecture down into the most decomposed layers (layer 3 or 4).

## Why does this get used?

We might see a software architecture diagram get used:

- To give the whole software development team a solid high-level overview of the software system they're working in/on. It's great for agile working and rapid prototyping (Internal Dev 👀).

- To provide a common language for a cross-department team to discuss and understand the system. It's great for stakeholders to have a less complex and easier-to-digest view of what's being worked on. The fact it's in layers means you can introduce more detail if need be.

- To flexibly represent a system of large or small size\*.

\*Although sometimes applying layered abstraction to a very simple design might be hard, we might risk over complicating it. Some diagrams will be v simple, don't overcomplicate it if it doesn't need it.

## What actually is it

Here are the layers involved (the 4 Cs):

1. **Context Diagram:**
   Shows the system in relation to users and other systems (if relevant). High-level view of the system and interactions with external entities.

2. **Container Diagram:**
   Decomposes the system into interrelated containers. Each container represents an application or data store.

3. **Component Diagram:**
   Decomposes containers into components and relates the components to other containers/systems

4. **Code Diagram:**
   Additional details about the design of elements that cnan be mapped to code. At this point relying on UMLs and ERDs

[Check out this site for more information on c4 diagrams](https://c4model.com/)

## The task

[Use this website to draw out a c4 diagram for a system you work with.](https://c4model.com/)

Example systems include:

- A full-stack project phase app
- Internal Dev work (the LMS system and all the comes with it)
- An app you enjoy using

^^ use your own creative license to guess unknowns, maybe you don't know the backend of Reddit but what could it be? What could that diagram look like?

This is an exercise in exploring how a diagram like this could work in our job:

- What's complicated about it?
- What is made clearer with a set of diagrams like this?
- Does it work for the project you picked or not?

Start simple and work up the complexity as you get more used to this design system.
