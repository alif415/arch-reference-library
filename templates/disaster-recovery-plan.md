# Disaster Recovery Plan: <_Service or Capability Name_>


## Purpose

This document is intended as a template for a Disaster Recovery Plan (DRP).


## Contents

<!--TOC max3-->


## Revision History

| Version | Issued     | Comments
| ---     | ---        | ---
| 0.1     | dd-MM-yyyy | …


## Distribution List

| Role | RACI
| ---  | ---
| …    | …


## Review

| Review frequency | Next review due
| ---              | ---
| ?                | ?


## Introduction

 Disaster Recovery Planning is a subset of Business Continuity Planning and addresses the recovery of systems. Invocation of a DRP will be directed and controlled under Business Continuity Planning. This document will contain detailed instructions to recover systems following invocation of the Business Continuity procedures (if necessary).

The Infrastructure strategy gives details at a high level of the activities necessary to prepare for, document, test and maintain a BCP and a DRP. The Business Continuity Management Toolkit  available from Gov.uk provides a more detailed guide to BCP and is available by following this link [BCP Toolkit](https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/137994/Business_Continuity_Managment_Toolkit.pdf)

The following template assumes that these documents have been read and the recommendations contained therein have been adopted in full or in part depending on a business impact assessment and risk assessment.


## Scope

<_Clearly state the scope of the document including all systems covered by this plan. Reference to other relevant plans or documents e.g. Operations Manuals, system documentation and product manuals including details of where such documents are stored and how they can be accessed should be provided._>


## Plan Ownership and Maintenance

<_The owner of the plan should be detailed. Those responsible for reviewing amending and updating the plan should also be included. Regular review cycles should be detailed and scheduled together with events which will cause the plan to be reviewed outwith the regular cycle. This may include re-organisation of the business, lessons learned following an invocation or test, addition or removal of systems etc._>


## Roles and responsibilities

<_List all individuals with a role in the implementation of the plan and state their responsibilities. Contact details for all such individuals, both during and outwith working hours should be held._>


## Invocation

<_The invocation process is described in the BCP. This includes the individuals who have the authority to invoke and the circumstances which will trigger invocation. The circumstances which will trigger invocation will have been detailed in the Risk Analysis and Business Impact Analysis and may include the following:_

- _loss of systems (IT and telecomm's)_
- _loss of or damage to premises_

_This section should also detail the process for mobilising the individuals and teams responsible for any recovery actions._>


## Contact Details

<_Contact details for all key stakeholders and individuals and teams charged with implementing the plan should be detailed. In addition, other third-party key resources such as suppliers, service providers, organisations providing disaster recovery or organisations with whom reciprocal arrangements have been made should be documented here._>


## Incident Management

<_Incident Management is covered in the BCP and details the tasks that will be needed to manage the incident initially and the early steps to be taken before recovery can be started. The BCP will also identify and detail the location from where the incident can be managed and an alternative should should the primary location be affected by the incident. Both locations should have facilities such as telecommunications so that the incident team can initiate response and recovery actions and co-ordinate activity. Depending on the recovery strategy, the disaster recovery may also be conducted from the same site. If the disaster recovery strategy means that system recovery is conducted from another site, e.g. from a specialist DR provider details of this site, together with access details and supplier invocation procedures should be detailed. Copies of this plan and all related documents should be held at all sites which are hosting recovery activity._>


## Communication  

<_Details of the communication strategy is included in the BCP. This is likely to include procedures to inform staff, Stakeholders and any wider audience such as the media of progress. This will also record details of progress reporting from the individuals and teams involved in the recovery._

_The extent of the communication details relating to the disaster recovery should be the procedures to be followed by the disaster recovery team to update the Incident Management Team on progress._>


## Recovery Procedures

<_This section should set out:_
- _the critical systems to be recovered_
- _the order in which these should be recovered_
- _the recovery time objective_
- _the recovery point objective_
- _the recovery timeline_
- _the resources required and the times when these will be needed_>


### Systems to be Recovered

<_For each system in scope, details of the system, recovery method, and relative priority should be specified. The recovery time objective (RTO) and recovery point objective (RPO) should also be specified._

_In terms of resources this is likely to include details of backup schemas and locations, details of secondary data centre facilities, details of specialist disaster recovery provider depending on the recovery strategy to be used._

_Detailed recovery instructions for each system will be included here. While it is acceptable to assume that the teams responsible for restoring operations will have a good technical knowledge the instructions should be sufficiently detailed that no application specific knowledge is assumed. These instructions should be completed under instruction from the senior manager responsible for recovery who will ensure that this process is followed in the correct order, progress is communicated and testing of recovery is completed._

_A sample table below is included for guidance but should be adapted or replaced with appropriate details for the systems to be recovered._>

|                     |             |
| -                   | -           |
| **System**          | System Name |
| **Description**     | Brief details of the system |
| **Priority**        | In order to assess relative priority a numeric scale could be used, e.g. for the most critical priority 1, next most important priority 2 etc.|
| **Recovery Method** | Details of the recovery method. This may be switch to hot standby site, switch to cold standby site, recovery from backup at a DR site etc.|
| **Resources**       | Dependant on recovery method. Details of secondary/standby site including all equipment deployed there, details of backup schemas and their location, including transaction logs for point in time recovery.|
| **Recovery steps**  | Activities to be performed to recover the system, the order in which these should be performed, dependencies and estimates of duration. These should be clear, unambiguous and at a level of detail which allows a suitably qualified technician to perform recovery with no prior knowledge of the application.|
| **Testing**         | Details of any testing to be performed during or after recovery with suitable acceptance criteria. Note that this may involve an element of user testing with a limited, controlled group of users before the system is signed off as recovered and made available to all users.
| **Sign-off**        | Details of the sign-off process to confirm that recovery is complete and the system has been successfully tested.


#### Pre-requisite Activities

<_Describe any pre-requisites that must be completed before this system can be recovered._>

| Activity | Action
| ---      | ---
| …        | …

#### Recovery Steps

<_Document the steps required to recover this system._>

| Step | Description | People Req'd | Est. Time | Comments
|  --- | ---         | ---          | ---       | ---
|    1 | …           | …            | …         | …


## Resumption of Normal Operations

<_Where applicable, this plan should detail procedures for resuming normal operation following an invocation and recovery. For example this may include:_

- _return to original premises following restoration of facilities_
- _reversion to a primary data centre following operation at a secondary site_

_The same criteria should be applied to these instructions as the recovery instructions as outlined in the section above._>

## Testing

<_It is important that the plan is regularly tested._

_Disaster Recovery procedures lend themselves to realistic simulation of a catastrophic event, e.g. recovery of a system from backup, dry runs of recovery at a specialist DR site, switch to standby site. These elements should be tested at regular intervals by carrying out recovery instructions in a test situation. It is recommended that this is done at least annually and preferably every six months._

_The scope of such testing should be agreed in advance, and a detailed report on recovery times, issues, failures and lessons learned should be produced and the results fed back into updates to the DRP._>


## Plan Maintenance and Review

<_The plan should be reviewed at regular intervals to ensure that_

- _all key systems and their critical activities and supporting resources have been identified_
- _arrangements still accurately reflect your organisation’s objectives and priorities_
- _arrangements are fit for purpose, and appropriate to the level of risk_
- _the plan reflects feedback and lessons learned from testing_
- _the plan reflects feedback and lessons learned from any invocation_

_All Stakeholders involved in the review process should be identified and responsibility for drafting, approving and committing changes should be assigned._

_In addition, depending on the recovery strategy used, updating of a DR environment may be routinely performed as part of production Change Control. If the recovery strategy is to recover to a standby site changes applied to the production environment may need to be applied to the DR site. An example of this would be patching or upgrades to operating systems or databases._>


## Appendices

<_Provide any relevant appendices._>


## References

<_Provide any relevant references._>
