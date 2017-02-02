# Service Levels


Service Levels should be agreed and documented in a Service Level Agreement (SLA). Using an SLA provides Customers and Providers with a description of the service to be provided, the duties and responsibilities of both parties and measures of the service. The SLA should specify targets for the relevant system quality attributes identified as critical to the business needs and how performance against these targets will be measured, reported and reviewed. This gives Customers and Providers a quantitative measure of the service against which performance of both parties can be assessed.


## Overview

The purpose of this section is to outline how service levels are managed including how these are:

- defined;
- measured;
- reported;
- reviewed;
- governed;
- changed.


## Definition of the Service

The definition of the service forms the basis for the SLA and for Service Level Management. This includes the scope of all services to be provided, the service hours and details of all key people, applications and infrastructure necessary to provide the service.

### Roles and Responsibilities

Typical roles and responsibilities for the Customer may include the following:

| Role               | Responsibility
| ---                | ---
| Service Sponsor    | The Service Sponsor is the Senior Responsible Officer is responsible for the service. He/she is responsible for signing off the SLA, ensuring that the service meets the business needs and is aligned with the business strategy. He/she is also responsible for approving and signing off changes, assigning priorities and ensuring that the Customer Team meets their responsibilities. He/she  will also typically be the budget holder for the service.  The Service Sponsor will act as the final escalation point in the event of a major incident or any dispute or complaint.
| Service Manager    | The Service Manager reports to the Service Sponsor and is responsible for the day to day operation of the service from the Customer perspective.
| User               | There may be Users at different levels in the Customer organisation, ranging in experience and knowledge. Senior Users or business specialists  may be nominated who can advise the user community on the operation of the system(s). To prevent the Service Desk being inundated with requests, it is not unusual to only accept incidents from nominated users.

Typical roles and responsibilities for the Service Provider may include the following:

| Role               | Responsibility
| ---                | ---
| Service Sponsor    | The Service Sponsor is the Service Provider’s Senior Manager responsible for delivering the service. He/she is responsible for signing off the SLA and signing off changes. He/she is responsible for ensuring that the Service is properly resourced to ensure that the support  teams can meet their responsibilities. He/she will also typically be the budget holder for the service. The Service Sponsor will act as the final escalation point in the event of a major incident or any dispute or complaint.
| Service Manager    | TThe Service Manager reports to the Service Sponsor and is responsible for the day to day operation of the service. He/she is responsible for the day to day resourcing of the support teams, escalating any issues to the Service Sponsor.
| Application support Manager  | Responsible for ensuring that the application support team meets the requirements of the SLA with regard to responsiveness and resolution.
| Infrastructure Manager       | Responsible for ensuring that the infrastructure support team meets the requirements of the SLA with regard to responsiveness and resolution.
| Service Desk                 | Will typically act as a first point of contact for incidents and queries, providing first level support, agreeing classification of incidents, routing incidents to the appropriate support teams and ensuring that these are dealt with in the appropriate timescale.

### Service and asset criticality

This should identify the business-critical assets connected with the service such as the vital business functions supported by the service and other critical assets used within the service (e.g. certain types of business data) It should also provide an assessment of the business impact caused by a loss of the service or assets. This may be an expression in monetary terms but is more likely to be a classification scheme.

### Service hours

The service hours when the service is required to be available should be specified and any exceptions detailed.


## Service Measures

This section details how a range of quality attributes can be defined,  measured and reported. In providing targets against wich these attributes are measured it is important that the target has the following properties:

- attainable;
- repeatable;
- measurable;
- understandable;
- meaningful;
- controllable;
- affordable;
- acceptable (to provider and customer).

A service level target should generally be expressed in terms of one or more metrics, each with a measurement period, and a monitoring approach (where and how measured and reported).

The following table shows examples of targets for various System Quality Attributes.

| Attribute | Metric | Measure | Target | Threshold | Penalty
| ---       | ---    | ---     | ---    | ---       | ---
| Capacity | Expressed in terms of user visits, concurrent users, data volumes etc. | All capacity metrics must be measurable by monitoring/analytics and reported to Customer in regular reports | These measures form the basis for the other service measures. | A tolerance may be specified e.g. a variation of 20% plus or minus | There are no penalties relating to this measure but the process for altering service measures, costs or both in the event of capacity being exceeded should be specified. See also Change Control.
| Availability | %uptime | Uptime monitored using http get to index page from public internet every 10 minutes| 99.9% over a calendar month | Target missed in 2 consecutive months | Any penalties incurred as a result of missing the target should be specified. This may be in the form of a service credit and may vary depending on the extent of the failure.
| Performance | Response times, Page load times | Response must be no more than 3 seconds, Page load times must be less than 3 seconds | 95% over a calendar month | Target missed in 2 consecutive months | see above
| Recoverability | Recovery Time Objective(RTO), Recovery Point Objective(RPO) | Mean time to recover data, Extent of data loss | In the event of a fault/data loss, data must be recovered within 2 hours, Data must be recovered to within 2 minutes of the failure | Target missed in two consecutive months | see above
| Reliability | Incidence of failures, Service time between failures | Number of failures, Mean time between failures | No more than 'x' failures per calendar month, No component should fail more than twice per calendar month|Target missed in two consecutive months | see above


## Governance

Having defined the service and established the service measures, this section covers:

- how the service is reviewed in terms of performance against targets;
- how the service is changed, ie the addition, amendment or removal of services;
- how the service is renewed or terminated.

### Service Review Process

This section should describe the inputs and outputs to the review process, the frequency of reviews and the composition of the review body. There is likely to be regular operational reviews of the performance of the service using the service measures described above. The respective Service Managers should take the leading roles in the operational review and operational managers are also likely to be attend as appropriate.

The review process may lead to changes to the service measures which will be made using the process described in the service change process described below.

In addition to the regular operational reviews there should be a wider reaching review of the service as a whole conducted involving the senior Customer and Provider Stakeholders. This would normally be conducted at a suitable interval (annually or bi-annually) but may be scheduled as a result of issues arising from operational reviews.

### Exception Process

The exception process details the procedures to be followed when service targets are not met. This is the appropriate place for details of any service credit regime whereby the pricing is discounted progressively to reflect the extent of the failure to meet a specific target.

### Change Process

The process to handle any change to the service measures should be described. This should include the event(s) which would cause the service levels to be reviewed. An example of this would be if the workload was significantly different from the target capacity on which the service was based. While some tolerance should be specified, if this is exceeded, the service targets may need to be re-negotiated or additional capacity added (and costs adjusted accordingly).

Another example is the addition (or withdrawal) of a service.

This section should also contain details of the process to be followed for contract renewals, extensions or terminations including notice periods.


## Related Service Levels

This should detail any other agreements related to the service.

An Operating Level Agreement (OLA) is typically an agreement between the service provider and another service provider who is part of the same organisation. An example of this may be between a Service Desk handling incidents for several services and the the team(s) providing these services.

An Underpinning Contracts (UC) is typically an agreement with a third-party outwith the service provider's organisation. An example of this may be a Cloud Hosting contract where the provider is responsible for the build, test and support of the application and/or underlying operating system but the Hosting Service is responsible for providing the underlying infrastructure to support this (eg servers, networking etc.)

In both cases above the service levels must be aligned with the service measures and targets described above.
