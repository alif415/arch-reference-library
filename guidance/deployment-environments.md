# Deployment Environments

The infrastructure design should support at least three categories of environment, namely Development, Test and Production. Each of these environments should be segregated at the network level and traffic between networks should be restricted. The environments should be as similar as possible.

## Development

This environment will be used to develop and unit test applications. While there should be controls over access and permissions, this environment will allow a greater degree of flexibility to Development teams whilst ensuring that all code and system configurations are subject to configuration management.

## Test

This environment will be used to perform various categories of testing such as

-   System testing
-   Integration testing
-   Performance testing
-   Regression testing
-   User Acceptance Testing

While it may be possible to use an environment for more than one type of testing, it is unlikely that a single environment will satisfy all of the above requirements and that multiple environments will be needed. These environments will be more tightly controlled than Development.

The Test strategy will define the processes for populating test environments with relevant data. This may involve taking copies of Live data and the processes for governance should be specified where this is the case. Backup, rollback and restore of data should also be considered.

## Production

This environment hosts the live service.

## Governance

All environments should be subject to change control. The focus of change control tends to be the Production environment and all changes deployed to production should be approved by the appropriate authority. It is important, however, to exert a degree of control over non-production environments, particularly where these may impact on the work of a number of teams. The Change Control mechanisms should be established covering details of the composition of the Change Authority together with procedures for submission, approval and implementation of change.

Part of the Change Control process will cover Configuration Management. In an agile environment this is particularly important where a continuous delivery strategy is implemented (see also the Section on Provisioning/Configuration Management).
