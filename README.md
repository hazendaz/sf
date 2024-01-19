# Salesforce Cli Compiled Distro #

[![Java CI](https://github.com/hazendaz/sf/workflows/Java%20CI/badge.svg)](https://github.com/hazendaz/sf/actions?query=workflow%3A%22Java+CI%22)
[![Maven central](https://maven-badges.herokuapp.com/maven-central/com.github.hazendaz.sf/sf/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.hazendaz.sf/sf)
[![BSD-3](http://img.shields.io/badge/license-BSD%203-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

![hazendaz](src/site/resources/images/hazendaz-banner.jpg)

This project compiles salesforce cli for distribution using maven central.

For more information on salesforce developer experience, please see [sf](https://developer.salesforce.com/developer-centers/developer-experience)

# Motivation #

Salesforce does not currently provide a maven central distribution of the project.  This project aims to solve that by providing users an alternative location to pull distribution for linux.

This project further provides alternative bundle for windows that does not require an install.

# Use Case #

Maven based storage of distribution in common location to offer more secure download location.  This is the compiled copy thus meaning no time wasted getting up and running the sf cli.

# Windows #

To utilize windows bundle in this, install it to windows from https://developer.salesforce.com/tools/salesforcecli# using 64-bit copy.  The build then points to the expected default windows location of c:\Program Files\sf\client
