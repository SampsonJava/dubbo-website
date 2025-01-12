
---
type: docs
title: "FAQ - Frequently Asked Questions"
linkTitle: "FAQ - Frequently Asked Questions"
description: "FAQ - Frequently Asked Questions"
weight: 90
---
### Which version should I choose?

Currently, Apache Dubbo it's maintaining four versions in parallel:

- 3.0.x: requires Java 1.8, compatible with Spring 3.2.x, and added a Kubernetes Service Integration and remarkable performance improvement

- 2.7.x (master): requires Java 1.8, major feature branch.

- 2.6.x: requires Java 1.6, minor feature & bugfix branch, GA, production ready.

- 2.5.x: requires Java 1.6, maintenance branch, only accept security vulnerability and critical bugfix, the support will end on 2019-6-15, please upgrade to 2.6.x as soon as possible.

For contributors, please make sure all changes on the right branch, that is, most of the pull request should go to 2.7.x, and be backported to 2.6.x and 2.5.x if necessary. If the fix is specific to a branch, please make sure your pull request goes to the right branch.

For committers, make sure select the right label and target branch for every PR, and don't forget to back port the fix to lower version is necessary.

### Where is dubbo-admin?

The dubbo-admin has been moved from core repository to https://github.com/apache/dubbo-admin since 2.6.1


### How to register IP correctly in Docker?

Dubbo supports specifying IP/port via system environment variables, examples can be found [here](https://github.com/apache/dubbo-samples/tree/master/dubbo-samples-docker).



