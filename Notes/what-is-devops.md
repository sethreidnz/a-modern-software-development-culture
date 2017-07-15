# What is DevOps

This file is a catch all for research on what DevOps actually is.

## Wikipedia

From [https://en.wikipedia.org/wiki/DevOps](https://en.wikipedia.org/wiki/DevOps)

- A software development process that emphasizes communication and collaboration between product management, software development and operations professionals.
- DevOps also automates the software integration, testing, deployment and infrastructure.

### DevOps Toolchain

Typically a DevOps process will include these high level steps:

- Code - version control tools
- Build - Continuous integration tools, build status etc
- Test - Continuous testing tools that provide feedback on business risks
- Package - Artifact repository, application pre-deployment staging
- Release - Change management, release approvals, release automation
- Configure - Infrastructure configuration and management, infrastructure as code tools
- Monitor - Application performance monitoring, end-user experience

One goal of DevOps is to establish an environment where releasing more reliable application, faster and more frequently, can occur.

Often continuous delivery and DevOps are confused. They are similar but DevOps has a wider scope and involves the whole culture in the organization and getting greater levels of collaborations between parts of a business in delivering on I.T. goals.

### Goals of DevOps

- Faster time to market
- Lower failure rate of new releases
- Shortened lead time between fixes
- Faster mean time to recovery in case of release crashing or breaking the system

### DevOps and achitecture

There a number of requirements that a software application needs to have to be able to practice DevOps such as:

- Deployability
- Testability
- Monitorability

Any architecture can be used but micro-services are becoming the defacto approach among DevOps adherents.