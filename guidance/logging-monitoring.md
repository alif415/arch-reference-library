# Logging and Monitoring


## Logging

Writing various categories of messages to logs can provide useful information when troubleshooting issues. For example, Java provides the facility to record various events which can be configured to be written to logs. When setting up logging, it is important to ensure that this is done at an appropriate level. For example, during development and some of the test phases it may be necessary to produce detailed information on the application activity to debug code problems. It would not be appropriate to produce such log events in production as this would be an unnecessary overhead and producing large volumes of data in a log could make important error messages more difficult to find. 

The expectation is that the level of logging would decrease as the application neared and reached production. Although some informational data such as start and stop times would still be recorded, the focus would be on recording events and conditions which, if not addressed, could impact availability. In addition, any failure events would be recorded for later analysis. Where the data is generated programmatically, it is important to capture the details of when, what, where, who, and some indication of how serious the event that triggered the message was.

Where logs are collected at the product or OS level there is not the same degree of flexibility to produce such detailed information on what may have caused the failure without switching on debugging at an instance level. This should be used with caution and avoided in Production.

Many components of the system can produce logs at various levels of detail which would be difficult and time-consuming to analyse manually but there are open-source tools available to collect, consolidate and analyse logs such as Logstash. Such tools allow logs to be searched down to a fine level of detail or graphed and analysed.


## Monitoring

This section covers all aspects of monitoring from alerting support teams through monitoring systems to providing real-time information on the performance of the system. In determining a strategy for monitoring it is important to identify the various stakeholders, their interests and the appropriate level of reporting. This section is closely linked to the section on Reporting, which details how the monitored data will be disseminated when collected.

### Operational Monitoring

Typically operational monitoring will report on the status of various components within the system. At a basic level this will be whether the component is up or down. In addition to alerting on failure a more proactive monitoring regime should be implemented based on threshold alerting. This will ensure that the appropriate support teams are alerted when a threshold or condition is reached allowing preventative measures to be implemented before this impacts on availability.

In addition to the more widely used monitoring metrics such as disk utilization, memory usage etc useful information can be derived from the various logs available. An increase in the number of errors reported can be an indication of an impending problem and so monitoring logs at all levels, eg server, database, application etc. is recommended.

### Resource Usage

In addition to monitoring to prevent failures, capacity measures should be monitored and reported. This data, including trend analysis, can be used as input to capacity planning in addition to identifying and addressing problems early. See also the Capacity Planning section.

### Analytics

There are various web analytics tools available to help you measure how people are using the service. These include measuring the number, flow paths outcomes and of user visits, the devices and browsers used, location of users etc. An assessment of how well a particular tool meets the analysis needs should be done before deciding which one to use.

### Performance

The various monitoring systems will provide data which can be used to assess the performance of the service. In measuring the performance it is necessary to set key performance indicators (KPI). The first stage in setting KPI is to identify the relevant stakeholders and confirm their requirements. These are likely to be:

- technical requirements, such as improving availability or response time;
- financial requirements, such as reducing costs;
- customer service requirements to improve customer satisfaction;
- wider strategic aims to reduce fraud and error.

These needs will typically be reflected in the organisation’s business objectives or in the business case for transforming a service.


## Reporting

This section covers all aspects of reporting from alerting support teams through monitoring systems to providing real-time information on the performance of the system. 

### Automated Alerting

The operational monitoring systems in place described in the previous Section should automatically alert the support team when specified conditions are met. This may include the Service Desk and auto-ticketing should be considered. Typically alerts will be sent via e-mail but it is also possible to set up text alerting if out of hours support cover is provided.

### Capacity Planning

Although the Support Team will have an interest in capacity planning, this is likely to be of interest to a wider audience. Typically measures of resource usage and trend analysis will be included in Management Information so that key Stakeholders have early sight of potential bottlenecks and where further investment to increase capacity may be needed.

### Management Information

In addition to resource usage measures and trends, key stakeholders are likely to be interested in the performance of the system. The performance measures and KPIs identified as discussed in the previous section should be reported at agreed regular intervals as part of a Management Information pack. The format will be agreed with the key Stakeholders but is likely to include such information as:

- Availability of the service;
- Support incident analysis;
- Resource usage;
- Number of users using the service;
- Number of successful/aborted visits;
- How the service is being accessed.

These are indicative measures which should be reported at the specified interval and include trend analysis from previous intervals. This is by no means prescriptive and will be compiled in line with the needs of the key Stakeholders in the service.

### Reporting Media

The alerting methods for operational monitoring are discussed above but consideration should also be given to the use of dashboards for real-time monitoring and alerting. 

The use of high level dashboards and selected graphical data based on KPIs should be considered. Real time and historical data could be disseminated through web pages or by screens in public areas of the office so that the team and any visitors or interested Stakeholders can quickly see how the service is performing.
