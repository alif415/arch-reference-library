#Technology Stack

The technology stack will be dependent on the solution design and selection but there are some over-arching principles that will apply to the selection of a technology. The UK Government Digital Service (GDS) have published guidance on Technology Architecture and Standards and the full version can be found at

https://www.gov.uk/service-manual/technology/index.html

The material below is derived from these.

## Technology Architecture

Architecture is not just about the design and deployment of technology and should encompass the following elements:

- the high-level business vision and requirements that guide the design of processes and systems around the needs of users (recognise that business requirements will change over time, so design solutions that minimise the impact of such changes
- an information model covering both public and private data, as well as wider information management requirements like business intelligence
- technology, the modelling of core capabilities, their structure and relationships
- implementation, including the development and application of guidelines, patterns, blueprints, models and communities that ensure consistent implementation and compliance across multiple programmes and projects
- throughout the project lifecycle you will need to make sure stakeholders stay aligned on what is needed (you’ll need to resolve issues when stakeholder requirements conflict with business growth (like reduced cost), system design (like network latency and operational issues (like security, privacy and auditing)

The term “architecture” includes both the logical design as well as its physical implementation. Logical architecture based on user-centric service design and clear user needs should always precede physical architecture. At a minimum you need to the capabilities required must be understood before product choices can be made.

## Technology Reference Model

The reference model draws on modern platform-based architectures. The highly scalable open platform model of internet-scale organisations, as illustrated below, may be used. 

Not all organisations will have legacy applications and this tier can be disregarded if that is the case. If legacy applications are present these should be modernised to reduce costs and risks and wrapped where appropriate to provide open interfaces and interoperability with platforms. Legacy applications should be replaced / re-architected periodically to prevent situations where the application can no longer be supported because it’s grown too complex for anyone to understand or too expensive relative to the benefits delivered.


![](assets/architecture-reference-model.png)


*Note: examples are for illustration purposes only.*

To support this, the architecture will need to move away from tightly coupled and proprietary models towards an open, interoperable architecture using open standards and open interfaces, eg XML- and JSON-based data services, to maximise flexibility and improve the delivery speed of services.

We should strive to:

- avoid duplication of data ownership – to prevent synchronisation, data quality, security, and privacy problems
- limit duplication of development effort – to prevent the continual reinvention of the wheel across multiple projects dealing with common data, users and processes
- wherever possible, use and reuse standard, interoperable components, interfaces, data formats and processes using open standards

## Open Standards

Open standards principles for software interoperability, data and document formats enable software to interoperate through open protocols and allow the exchange of data between data stores and software through open data and document formats. This applies equally to data flows between old and new systems and between new systems.

Open standards are able to be implemented by a diverse range of suppliers. The selection of open standards for IT specifications reduces the risk of lock-in to suppliers, software, service and support, or to old and inefficient IT. Smaller, component-based IT systems provide a flexible design to allow choice and enable an evolution of the IT estate, rather than costly big bang changes.

It should be noted that a large market still exists for commercial software products. The availability of open source software doesn’t automatically mean that a proprietary technology should not be chosen if it meets the user needs. However, the HMG position is that:

> where there is no significant overall cost difference between open and non-open source products that fulfill minimum and essential capabilities, open source should be selected on the basis of its inherent flexibility.

Further information about open standards can be found using the link below.

<https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/78892/Open-Standards-Principles-FINAL.pdf>
