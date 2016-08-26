# Test Plan: <_Project Name_>

This document describes how system testing will be managed and performed as an integral part of overall delivery. This includes the test items, the test approach (based on the test concepts and test techniques) as well as the test reporting and metrics.

<_The Test Strategy describes the principles, approach, standards, practices, tools and techniques that are to be used by the division and should be referred to if any further guidance on testing is required._>


<!--TOC max3-->


## Revision History

| Version | Issued     | Comments
| ---     | ---        | ---
|     0.1 | dd-MM-yyyy | …


## Distribution List

| Role | RACI
| ---  | ---
| …    | …


## Review

|                    |     |
| ---                | ---
| *Review frequency* | ?
| *Next review due*  | dd-MM-yyyy

## Approvals

| Name | Sign-off Date
| ---  | ---
| …    | dd-MM-yyyy


## Background

<_Briefly describe the project and provide links to further information._>


## Traceability

This section catalogues the inputs into the test planning process – i.e. those documents that were used to determine the elements of the system / service to be covered by testing activities.

| Document | Version | Link
| ---      | ---     | ---
| …        | 0.1     | [Example](http://example.com)

<!--
Examples of documents we would expect to see referred to here:

- business requirements;
- user stories on a product backlog;
- the architecture description;
- the system quality specification.

-->


## Scope

System delivery includes a range of different activities and outputs. Only some of these require to be tested. The following table lists the activities undertaken on the project and specifies whether they require associated testing activities.

| Without Tests | With Tests
| ---           | ---
| Epics			| User Story delivery
| Spikes		| Technical debt correction
|               | Defect fixes
|               | Document creation


### Test Items

<_If this test plan only covers a subset of the overall solution list the components / applications / etc. Otherwise this section can be deleted._>

| Test Item | Notes
| ---       | ---
| …         | …


## Test Approach

### Test Techniques

This section describes the test techniques that will be used. It explains who will undertake each form of testing, the reason for performing the tests, whether the test will be automated, and, crucially, the level of coverage required.

| Test Technique | Objectives | Authored by | Executed by | Automated? | Coverage target (%) | Notes
| ---            | ---        | ---         | ---         | ---        | ---                 | ---
| …              | …          | …           | …           | Y/N        | …                   | …

### System Quality Attributes

#### Out of Scope

The following system quality attributes, as described in the test strategy, have been identified as out of scope for this release, phase or project as covered by this test plan.

| System Quality Attribute | Reason Not in Scope
| ---                      | ---
| …                        | …

#### In Scope

The following system quality attributes, as described in the test strategy, are required to prove that the non-functional requirements for this project have been achieved.

| System Quality Attribute | Environment | Data required | Test Approach
| ---                      | ---         | ---           | ---
| …                        | …           | …             | …


## Test Data

The data required for testing purposes is documented in the table below. Further details of our approach to test data management can be found in the test strategy.

| Test Data | Notes
| ---       | ---
| …         | …

<!-- The notes section for each test dataset in the table above should, at a minimum describe:

- volumetrics: size of the dataset as a percentage of the size of the predicted operational dataset;
- arrangements for import and export to a test enviornment;
- how the dataset will be created: random data / anonymised data / pseudonymised data;
- how asset management and version control will be undertaken.
-->

Any specific deviations to the general test data approach must also be noted here.

<!-- Note any deviations. -->


## Test Tools

The section outlines the testing tools that have been selected for use in this project.

| Test Technique | Tool | Notes / Explanation		
| ---            | ---  | ---
| …              | …    | …

| System Quality Attribute | Tool | Notes / Explanation		
| ---                      | ---  | ---
| …                        | …    | …


## Test Environments

The environments required to be commissioned for testing purposes are documented in the table below. Full details for these environments can be found in the deployment and operational views of the architecture description.

| Test Environment | Test Activities
| ---              | ---
| …                | …


## Exit and Entry Criteria

Entry and exit criteria are as documented within the test strategy, unless a specific deviation is noted here.

<!-- Note any deviations. -->


## Test Team

The following table defines the names and roles of those involved in testing activies. Please refer to the test strategy for a full description of the roles.

| Name | Role
| ---  | ---
| …    | …


## Defect Management

Defects identified as a part of test acitivities will be handled as documented within the test strategy, unless a specific deviation is noted here.

<!-- Note any deviations. -->


## Deviations from the Test Strategy

By default testing follows our defined test strategy. Any deviations will be recorded in the table below.

| Test Strategy Deviation | Reason for Variation
| ---                     | ---
| …                       | …


## Governance

<_Using what has been defined within the test strategy for the test reporting, describe what will be delivered within this test plan as well as documenting the risk and issues management as well as dependancies and assumptions associated with this specific testing initiative._>

### Project Dates

The following table identifies the planned dates in which test activity tasks are applicable.

N.B. These dates were correct at the time the test plan was approved. Any changes to these dates will be discussed and agreed and the reasons for change will be recorded in the corresponding test completion report.

| Task     | Planned End Date
| ---      | ---
| Sprint 0 | dd-MM-yyyy
| Sprint 1 | dd-MM-yyyy
| Sprint 2 | dd-MM-yyyy
| …        | …

### Test Reporting & Test Metrics

The following information will be reported via a dashboard as documented within the test strategy.

For each test technique that is applicable (except exploratory testing):

- Total tests:
	- % Passed;
	- % Failed;
	- % Ignored;

- At Unit and Component level:
	- Test coverage;

- Total defects in backlog:
	- Total defects by age;
	- Total defects by severity.

### Risk and Issue Management Process

Risks and Issues related to this testing initiative will be recorded under the project's RAID log and will be regularly reviewed and progressed by the delivery team.


### Dependencies and Assumptions

The following is a list of dependencies and assumptions identified, which may impact the specific testing initiative for this project.

| ID  | Assumption
| --- | ---
| …   | …


## Appendices

<_Provide any relevant appendices._>


## References

<_Provide any relevant references._>
