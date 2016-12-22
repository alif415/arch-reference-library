# Performance Testing Checklist

N.B. This checklist is based on a proposal from GDS to the Digital Leaders Network around assessing the performance testing undertaken for new services.


## Background

- Do you have an intended launch date?
- What determined that date and how flexible is it?
- Are there significant drivers or things that will make it hard to launch quietly? (major policy change, controversial service, ministerial commitment, etc)
- When this launches as a beta, will it be the only service available for users?


## Dependencies

- What are the main ways people, whether end users or internal staff, interact with the service?
- What dependencies on other systems and services do you have?
    - this should include other services that are consulted or updated via APIs, admin interfaces that are required to complete the overall user journey, batch jobs, etc.
- Which of those are within your control?
- What is your agreed level of service for these dependencies? How are you notified of planned/unplanned outages? How much warning will you have of planned outages, and how will you deal with that?
    - at alpha: know these are considerations, know who to talk to, and what you’re likely to need
    - at beta: clearly understood and documented
    - at live: confidence that the services can meet the agreed levels
- Which of your dependencies do you share with other services? How are you ensuring that they are prepared for potential spikes across multiple services?
- How are you ensuring that you are doing realistic testing across the entire service?
    - expect concerns about test data and some legacy/3rd party systems
- How will you ensure that you are able to repeat your testing regularly?
- What is the procedure for handling unanticipated traffic levels?
    - at alpha: have thought about it, know constraints
    - at beta: have a way of managing impact on users, scale up systems quickly or manage usage of legacy components
    - at live: documented and rehearsed


## Overall performance testing approach

- How many users are you anticipating using the service and how frequently will they use it?
- Are those numbers consistent across the year, or do they vary? (seasonally, particular deadlines, etc)
- Describe the expected take­up of the new service over time (vs existing digital and non­digital services)
- How have you arrived at those details?
    - Looking for for things like evidence from existing service, forecast from policy and socio­demographic data, understanding of impact of policy change and likely comms around it
- How are you testing that the service will be able to handle the likely demand?
    - looking for thorough soak testing, capacity and performance testing
    - at alpha: understand the types of tests and have an idea of how to do it
    - at beta: be able to do it repeatedly and regularly
    - at live: have done it repeatedly, know how they’ll continue to test
- How are you working out the levels of traffic to test with?
    - should be starting with realistic data and then multiplying
    - should have allowed for spiky traffic
    - should understand numbers for simultaneous use and describe how that relates to estimated session duration and variance
- How are you monitoring performance? What do you do with that monitoring data?
    - at alpha: have thought about it, expect to be alerting people
    - at beta: have implemented monitoring and basic alerting
    - at live: have tested alerting processes, know about support routes, etc.


## Joined up team

At beta and live stages we also want to know.

- What comms are you or your department planning to do around the service?
- Who is in charge of the launch plan and comms?
    - looking to make sure that someone is seen as being in charge
- What steps are you taking to avoid a big bang launch?
