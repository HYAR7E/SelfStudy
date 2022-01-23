# Software Architecture


### Scope
- Macroscopic system structure
- Architecural design decisions
- Important and fundamental stuff


### Characteristics
- **Multitude of stakeholders**

	Address the concern of the different stakeholders by design.

	Balance the concerns and demostrate that they are addressed in the design.

	Multidisciplinary nature due to the variety of stakeholders.

- **Separation of concerns**

	Separate the concerns that drive the design into _architectural views_

	Include modular design (optional Aspect Oriented programming)

	**Architectural view**
	> Architecture documentation that shows an individual stakeholder concerns are addressed by describing the architecture from their separate point of view.

	E.g.: [4+1 view model](./4+1_architectural_view_model.md)

- **Quality Driven**

	The architecture of a software system must have:
	- Fault tolerance
	- Backward compability (if required)
	- Extensibility
	- Maintainability
	- Availability

- **Recurring styles**

	Standar "ways" like architectural pattern and reference architecture.

- **Conceptual Integrity**

	Represents an overall vision of what it should do and how it should do it.

	The architect assumes the role ot *keeper of the vision*, preserving the conceptual integrity by making sure that additions to the system are in line with the architecture.

- **Cognitive Constraints** (aka Conway's Law)

	Organizations which design systems are constrained to produce designs which are copies of the communication structure of these organizations.


### Motivation

- Gives a basis for analysis of software systems' behaviour before the system has been built.
	- Verify a system will fulfill its stakeholders' need.

- Provides a basis for re-use elements and decisions across multiple systems whose stakeholders require similar quality attributes of functionality.

- Support early design decisions that impact a system's development, deployment and maintenance life.

- Facilitates communication with stakeholders helping them to understand the consequences of their stated requirements and the design decisions based on them (allowing to change/adapt stakeholders requirement based on the project capabilities).


### Architecture Activities

Four core activities in software architecture design:

- Architectural Analysis

	Receive requirements from the stakeholders, understand the environment in which a proposed system will operate and determine the requirements for the system.

	The outputs of this analysis are those to have a measurable impact on the software system's architecture, called *architecturally significant requirements*

	- What the system will do when operational (*functional requirements*)
	- Requirements such as reliability, operability, performance efficiency, security and compability. (*non-functional requirements*)
	- Development time of non-functional requirements such as maintainability and transferability.
	- Business requirement and environmental context of a system that may change over time (such as legal, social, financial, competitive and techonology concerns).

- Architectural Synthesis
	
	Given the significant requirements determined by the analysis, the current state of design and the result of evaluation activities, the design is created and improved

- Architecture Evaluation

	Determine how well the current design satisfies the requirements derived during analysis.

	This process may occur when the architect is considering a design decision, after some portion of the design has been completed or at the very end when the final design has been completed or the system has been constructed.

	This usually involves using some architecture evaluation techniques like [ATAM](./ATAM.md) and TARA.

- Architecture Evolution

	Adding new functionality as well as maintaining existing functionality and system behaviour, to meet changes in requirements and environment


### Architecture supporting activities

In general architecture requrires critical supporting activities which take place throughout the core software architecture process.

Includes:
- Knowledge management and communication
- Design reasoning
- Decision making
- Docummentation.


#### References
- [Wikipedia](https://en.wikipedia.org/wiki/Software_architecture)
