# README - RHM Accounting Open Source ERP/CRM system

This repository features all types of SysML/UML diagrams to cover all aspects of the system coded using Zend Framework.

Including styles to this readme file with [Markdown](https://github.com/fletcher/MultiMarkdown/blob/master/Documentation/Markdown%20Syntax.md title="Markdown") 

# Structure of the technical specifications

A software is organized around functional and architectural aspects (see [Wikipedia](https://en.wikipedia.org/wiki/4%2B1_architectural_view_model title="4+1 view"))

Analysis
--------

1. User needs
	
	1. A context diagram is used to define the system actors
	2. The package diagram splits the system in categories and identifies actors interacting with the system
	3. A Use case diagram represents required functionalities (use cases) for the user of a package or the whole system
	
2. Logical View

This view represents a functional aspect, it identifies the elements and their relation for the system.

	1. A class diagram in the analysis phase represents entities (informations) used by actors. During the conceptual phase, the class diagram will detail objects manipulations.
	
	2. An Object diagram details an example of an instance and is used when a class is more complex.

3. Process View

This view shows the processes and work flow rules of a system and how these processes communicate with each other. It explores *what needs to happen* in a system.

	1. A Sequence diagram describes the scenarios of a use case.
	2. An activity diagram describes the process work flow without using objects. It helps consolidate use case specifications.
	3. A communication diagram highlights the objects messaging exchanges. It can complete the sequence diagram. It clarifies actions.
	4. A state transition diagram describes the life cycle of an object.
	5. A global interaction diagram provides an overview of the interactions of a system. Each element of this diagram can be detailed using a sequence or an activity diagram.
	

Conception
----------

1. Component View

This view features all the components being parts of the system (libraries, interfaces, database, executables...) and materials in use.

	1. The composite structure diagram describes a complex object while executing.
	2. A components diagram describes all useful components of the system (applications, libraries, database instances, executables...)
	
2. Deployment View

Its purpose is to show the material involved and the repartition of the different software elements.

	1. The Deployment diagram helps identifying the execution environment and the way components are involved.
	