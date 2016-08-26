# Test Reqirements Checklist

The aim of requirements testing is to reduce the number of defects found later in the software development lifecycle. This 10 point checklist will provide a mechanism to ensure that requirements accurately describe what is needed.

<!--TOC max3-->


## Revision History

Version | Issued     | Comments
------- | ---------- | --------
0.1     | dd-MM-yyyy | …


## Distribution List

| Role | RACI
| ---- | ----
| …    | …


## Overview

### Process

Complete the questions in the checklist in an objective and unbiased manner, then evaluate the score.

### Structure

This document contains the following sections:

   - _Checklist Criteria_: details of the 10 point checklist to be reviewed in relation to each requirement;
   - _Scoring_: per-requirement scores for each of the requirements;
   - _Overall Result_: did the test pass or fail;
   - _Comments_: any additional relevant comments, for example, providing an outline of any necessary remediating actions.

### Instructions for Completion

The Checklist Criteria section lists each of the 10 requirements checkpoints with some further detail and guidelines as to what each means. The checkpoint names only, are then listed in the Scoring section.

Add a row to the table for each requirement including the requirement reference in column 0. Each of the 10 questions should be answered per requirement, inserting a 'Y' if the requirement meets the criterion and 'N' if it does not meet the criterion. Count the failures and record this counts in the relevant columns.

An overall result of 'Passed' or 'Failed' is determined upon completion, based on the individual scores.


## Checklist Criteria

### Complete

Are your requirements complete?

- How likely are they to change
- Is effective change control in place
- How can current requirements be potentially affected by new requirements
- What are the dependencies on completing each requirement
- What will late changes do to the Test lifecycle and / or Production launch

### Unambiguous

Are your requirements unambiguous?

- Not open to interpretation
- Not an opinion or a story
- Direct and to the point
- Not full of jargon or buzzwords
- Do other parties understand your requirement definition
- No escapism, no suggestions

### Singular

Are your requirements in the singular?

- Don’t merge / link requirements
- Avoid nightmare 'twinning'
- Break the requirements down into singular units
- Keep to the agreed level of granularity
- No overlapping of boundaries

### Achievement Driven

Are your requirements achievement driven?

- What benefits will be derived from the requirement
- Is the cost of building, testing and managing the requirement GREATER than the perceived end benefit
- Has the cost / look / feel of the Project changed since creating the technical specifications

### Measureable

Are your requirements measurable?

- Defined specific metrics appropriately used
- No ‘woolly’ statements e.g. ‘most of the time’, ‘reasonable use’, ‘a number of’
- Specific measurable ranges defining clear start and end ranges
- Agreed set of metric values used across in-scope requirements

### Developable

Are your requirements developable?

- Is the requirement build feasible
- Can the requirement be built within project timeframes
- Does the internal / external
- Development Team(s) have the relevant skills to build the requirement
- Is the requirement cost justified

### Business Owned

Who owns the requirements?

- Each requirement should have a nominated owner
- How do the technical requirements link in to their relevant business counterparts?
- Technical requirements should be technically focused
- The owner must be aware of the impact of the requirement’s risk becoming reality

### Security

Have you considered security requirements?

- Will the system process critical / sensitive information?
- Is the business subject to external or internal drivers that include security requirements?
- Have you assessed the impact of security risks to the confidentiality, integrity and / or availability of the system?
- Have you included appropriate functional application security requirements?
- Have you formally evaluated possible Misuse cases?
- Does your test plan reflect security assurance requirements?

### Performance

Have your requirements been designed with system performance in mind?

- What should the response time be? - define them
- Number of overall users versus number of concurrent users
- Perceived growth of data for particular functions / requirements
- Data migration requirements
- Critical function junctions

### Testable

Are your requirements testable?

- Can the requirement be replicated
- Can the requirements test output be measured
- Can you test the other 9 rules?
- What supporting  elements need to be in place to test out the requirement
- Can the technical specifications be easily interpreted by the Testers?


## Scoring

|                            |     |
| ---                        | ---
| **Organisation**           |
| **Division**               |
| **Project**                |
| **Reviewed Document Name** |
| **Date**                   |

| Req' ID | Complete | Unambiguous | Singular | Achievement Driven | Measureable | Developable | Business Owned | Security | Performance | Testable | Problem Count
| ---     | ---      | ---         | ---      | ---                | ---         | ---         | ---            | ---      | ---         | ---      | ---
| …       | (Y/N)    | (Y/N)       | (Y/N)    | (Y/N)              | (Y/N)       | (Y/N)       | (Y/N)          | (Y/N)    | (Y/N)       | (Y/N)    | 0

| Checkpoint         | Problem Count
| ---                | ---
| Complete           | 0
| Unambiguous        | 0
| Singular           | 0
| Achievement Driven | 0
| Measureable        | 0
| Developable        | 0
| Business Owned     | 0
| Security           | 0
| Performance        | 0
| Testable           | 0
| Problem Count      | 0

## Overall Result

<_Pass / Fail._>

## Comments

<_Provide any further comments or observations._>
