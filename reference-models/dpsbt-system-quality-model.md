# Reference Model: System Quality


## Purpose

An architecture reference model is an abstract framework or domain-specific ontology consisting of an interlinked set of clearly defined concepts produced by an expert or body of experts in order to encourage clear communication. This frame of reference can then be used to communicate ideas clearly among members of the architecture and/or delivery community.

When organisation makes the decision to extend an existing software system or to build a new software system it is nearly always a requirement that what is delivered should be "good quality". This model aims to explain what "quality" means for the software systems that we deliver.


## Contents

<!--TOC max3-->


## Revision History

| Version | Issued     | Comments
| -       | -          | -
|     0.1 | 26-04-2016 | Initial draft.


## Distribution List

| Role                         | RACI
| -                            | -
| Senior Responsible Officer   | Accountable
| Head of Digital Architecture | Responsible
| Lead architects              | Consulted
| Business analysts            | Consulted
| Delivery team                | Informed


## Review

| -                  | -
| *Review frequency* | Every six months.
| *Next review due*  | 26-10-2016


## Role

When organisation makes the decision to extend an existing software system or to build a new software system it is nearly always a requirement that what is delivered should be "good quality". This model aims to explain what "quality" means for the software systems that we deliver.

The basis for our definition of quality will be to define a series of attributes for the system and explain how an architect might go about quantifying what is required for a system with respect to each attribute.

To support this explanation we will then classify our list of system quality attributes into a series of perspectives on the system's architecture. Architects regularly use perspectives as a tool for explaining to stakeholders how a system will satisfy their requirements.


## Scope

- [x] Foundation
- [ ] Common Systems
- [ ] Industry
- [ ] Org-specific

This reference model is generally applicable across many classes of system and multiple systems. A particular architecture project may choose to supplement this foundation model with a more detailed model, where such a model is available (for example a system quality model for 'content management systems' in the 'public sector').


## Taxonomy


Utility
: when applied to a system, 'utility' describes *what* functionality is provided in order to meet a user's needs. At design time this translates into a set of functional requirements to be implemented.

Warranty
: when applied to a system, 'warranty' describes *how* the functionality is provided and will typically include specific promises or guarantees. At design time this typically translates into a set of non-functional requirements to be implemented.

Quality Attribute
: a specific property or characteristic of a system that contributes to the system's warranty.

Perspective
: a description of a system that explains how a quality attribute (or set of related quality attributes) will be realised. The creation of a perspective will make use of a range of analysis, tactics and guidelines to ensure that the system exhibits the required attribute(s).

### System Quality Attributes

Accessibility
: the degree to which a system is available to as many people as possible. The concept often focuses on people with disabilities or special needs and their right of access. This access is often enabled by the use of assistive technology.

Availability
: the amount of time that all components of the system are fully functional for its users. Planned maintenance periods are excluded from availability measures.

Capacity
: the maximum possible capability of the system in a particular dimension. Note that there is a distinction between *throughput* and *capacity*. We consider throughput to be the total amount work that can be achieved by a system in a fixed period of time. Capacity requirements might typically include:

    - Number of concurrent users
    - Number of concurrent requests
    - Number of concurrent messages processed
    - Total data stored
    - Network packet size

Compatibility
: the ability of a system to be fully functional across a defined range of technologies. We consider typical dimensions of compatibility to include:

    - Application Programming Interface (API) compatibility
    - Browser compatibility
    - Operating System (OS) compatibility
    - Virtual Machine (VM) compatibility
    - Programming language compatibility
    - Hardware / device compatibility
    - Character set compatibility

Efficiency
: the ability of a system to complete its tasks within a limited set of resources. Resource limits would typically include:

    - Memory
    - Disk space
    - CPU usage
    - Network bandwidth
    - Power consumption

Elasticity
: the ability of a system to add and remove capacity based on demand. It should be noted that elasticity could be achieved by both manual and automatic methods.

Extensibility
: the ability to extend a system, with a minimum amount of effort, without impact to existing system functions. Typically this would allow third parties to contribute new features or capabilities using published APIs, plugins or themes.

Localisability
: the ability of the system to be configured to support a number of locales.

Modifiability
: the ability of the system to accommodate the addition, change and removal of features, with minimal impact on the rest of the system.

Performance
: the ability of a system to complete a specific function in a defined amount of time. Compare this with our previous definition of capacity and our distinction of throughput.

Recoverability
: the ability to bring the system back to a known working state in a well-defined period of time.

Resilience
: the ability of the system to tolerate anticipated faults.

Robustness
: is the ability of the system to tolerate unexpected or unplanned external or environmental conditions.

Scalability
: the relative increase in the capacity of a system as resources are added; while the efficiency and performance of the system remains constant.

Security
: the ability of the system to preserve the confidentiality, integrity and availability of information under external inputs.

Serviceability
: the ability of the system to be easily supported, maintained and operated. Service of the system will typically include activities such as:

    - Installation
    - Upgrading and patching
    - Configuration
    - Monitoring
    - Debugging

Testability
: the measure of how easy it is to create tests for a system and its associated components, increasing the ability to find and isolate bugs in an effective way.

Usability
: the ease of use and learnability of the system.


### System Perspectives

Performance
: this perspective explains how the system will meet the expected levels of usage. Quality attributes included:

    - Performance
    - Capacity
    - Efficiency

Scalability
: this perspective describes how the system will meet changes to the expected levels of usage over its lifespan. Quality attributes included:

    - Scalability
    - Elasticity

Availability
: this perspective describes how the system will be designed to remain available to users as a result of both planned as well as unplanned events. Quality attributes included:

    - Availability
    - Resilience
    - Robustness
    - Serviceability
    - Recoverability

Evolution
: this perspective describes how requirements related to the ability to change the system over time will be met. Quality attributes included:

    - Extensibility
    - Modifiability
    - Testability
    - Localisability

Interaction
: this perspective describes how the system will meet attributes related to the quality of a user's experience of the system. Quality attributes included:

    - Accessibility
    - Usability
    - Compatibility

Security
: this perspective describes how the system will meet security requirements. Quality attributes included:

    - Security


## Graphic

![The System Quality Model Graphic](https://scottishgovernment.github.io/arch-reference-library/reference-models/dpsbt-system-quality-model-graphic.svg)


## Discussion

Our basic expectations for usage of this model are as follows:

- delivery teams will be aware of this model, will undertand the definitions above, and will consistently use the definitions as a part of day to day delivery of the project;
- the technical architect on a delivery team will be proficient in the model and will use it as an integral part of the architecture definition process;
- the technical architect will work, during the alpha phase, with project / programme stakeholders in order to explain the model to them as well as the importance of beginning to establish a clear understanding of system warranty;
- the technical architect will run a series of workshops, during the alpha phase, to ensure a collaborative discussion amongst stakeholders takes place and to determine a draft of a system quality specification;
- by default the system quality specification will be documented using our standard template;
- the technical architect will incrementally author a series of system perspectives, as a part of the architecture definition process during the beta phase, to describe how the system being built meets the system quality specification;
- the technical architect will continue to liaise with stakeholders during the beta in order to update the system quality specification as the team learns more about the real business requirements;
- the delivery team will make use of this reference model as well as the system quality specification during the elaboration of user stories in order to ensure that system warranty is regularly considered alongside feature delivery;
- during beta the technical architect will work with the delivery team reach a level of delivery maturity where it is possible to provide regular reporting on which quality attributes are and aren't met;
- the model will be used as a domain engineering tool to identify novel tools, tactics and approaches that can be doucmented for re-used as a part of the division's building block catalogue.


## References

- [The Digital First Service Standard](http://resources.mygov.scot/standards/digital-first/);
- [The High Level Operating Framework](http://www.gov.scot/Topics/Economy/digital/digitalservices/HLOF);
- [ISO/IEC/IEEE 42010:2011 Systems & Software Engineering – Architecture Description](http://www.iso-architecture.org/ieee-1471/);
- [ISO/IEC 25010:2011 Systems and software engineering – Systems and software Quality Requirements and Evaluation (SQuaRE) – System and software quality models](http://www.iso.org/iso/catalogue_detail.htm?csnumber=35733)
- [TOGAF standard, version 9.1, part VI](http://pubs.opengroup.org/architecture/togaf9-doc/arch/toc-pt6.html);
- [Wikipedia: Reference Models](https://en.wikipedia.org/wiki/Reference_model).
- [Quantify the un-quantifiable: Tom Gilb at TEDxTrondheim](https://www.gilb.com/blog/quantify-the-un-quantifiable-tom-gilb-at-tedxtrondheim)
