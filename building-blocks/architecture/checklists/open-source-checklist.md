# Open Sourcing Checklist

## Purpose

This document provides a checklist of items that should be considered prior to open sourcing a private source code repository.

We should be able to meet all the below checks for a repository, prior to publishing it as open source.

## Checks

- [ ] Has the source code and related documentation been reviewed by a technical architect and an information security officer to confirm that none of the following are included:
    - information or code that, when shared, could allow a breach in our security;
    - 'personal' or 'personal sensitive' data, as defined in the Data Protection Act?
- [ ] Has the code-base been reviewed by a technical architect to ensure it is of an appropriate quality?
- [ ] Have we confirmed with all committers that the source code is their own work and therefore that the source code is exclusively The Scottish Government's intellectual property – i.e. that we haven't copied any portions of code from third parties?
- [ ] Have we confirmed that a README file is present in the root directory and that it is up to date?
- [ ] Have we confirmed that a LICENSE file is present in the root directory and that the license is MIT?
- [ ] Have we confirmed that an OGL file is present in the root directory and that this contains a plain text copy of the Open Government License v3?
- [ ] Does the README file explain that source code is published under the MIT license and all remaining documents are published under the OGL?
- [ ] Does the README clearly assert that all work within the repository is Crown Copyright?
- [ ] Has the code-base been reviewed to confirm that it does not include any passwords, keys, configuration or other sensitive assets?
- [ ] Does the README include an explanation that we are currently running in a "coding in the open" model and, as such, we will not be accepting third party contributions?
- [ ] Do we provide an email address to which questions and (potentially) security notices may be submitted?
- [ ] Have we created a NOTICE file in the root directory that lists all third party dependencies for the source code in the repository and confirmed that the licenses of these dependencies are compatible with the MIT license.
- [ ] Is there sufficient documentation available such that a beginner can get started with the project?
- [ ] Has an appropriate audit schedule been established to reconfirm these items and has an owner been established?

## References

- [Making Your Code Available Under An Open Source Licence](http://oss-watch.ac.uk/resources/opensourceyourcode).
