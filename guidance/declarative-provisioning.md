# Provisioning & Configuration


## Declarative Provisioning

Managing infrastructure in a virtualised environment has become increasingly complex, just as the expectations for rapid deployment of new services has increased. Many IT organisations rely on manual processes, custom scripts, and golden images to accomplish repetitive tasks. In large environments, or with multiple team members, these methods are difficult to scale, track and maintain, and can create several issues, including virtual sprawl, configuration drift and non-compliance. The manual nature of the process and the need to track configurations across multiple environments decreases productivity and responsiveness. As dependencies may change over time, building a new server from scratch will involve either manually removing packages, or throwing the server away and repeating the installation process by hand. The installation could be automated using custom scripts but, as calls are made to the native OS package manager, these will only run on the operating system of choice and would not support portability.

In order to support an agile approach to deploying services it is critical that configuration management is enforced. While this has been widely enforced in developing, testing and deploying application code for some time, orchestration tools now allow the same discipline to be imposed on the infrastructure configuration. Automated provisioning of server configurations across a number of machines and environments also provides the rapid and repeatable provisioning necessary to support continuous delivery as part of an agile approach.

Configuration management/orchestration tools provide a generic and operating system agnostic way to install packages, meaning scripts can be run on different operating systems without modification. Additionally, those same scripts can be used to provision the machine, meaning that the development, test and production machines will be practically identical. The need to enforce configuration management and apply change rapidly and in a controlled manner to multiple servers across a number of environments dictates the use of a declarative provisioning tool.


## Puppet

There are a number of open source tools available with their own relative strengths and weaknesses including Puppet, Chef, Salt and a number of others.

Puppet is the most mature product and has the largest user base. It's the most complete in terms of available actions, modules, and user interfaces. Puppet represents the whole picture of data centre orchestration, encompassing just about every operating system and offering deep tools for the main operating systems. Initial setup is relatively simple, requiring the installation of a master server and client agents on each system that is to be managed.

The CLI (command-line interface) is straightforward, allowing module downloads and installation via the puppet command. Then, changes to the configuration files are required to tailor the module for the required task, and the clients that should receive the instructions will do so when they check in with the master or via a push that will trigger the modifications immediately.

There are also modules that can provision and configure cloud server instances and virtual server instances. All modules and configurations are built with a Puppet-specific language based on Ruby, or Ruby itself, and thus will require programming expertise in addition to system administration skills.
