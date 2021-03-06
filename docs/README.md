Welcome to IntelMQ!
===================

![IntelMQ](https://raw.githubusercontent.com/certtools/intelmq/master/docs/images/Logo_Intel_MQ.png)

[![Build Status](https://travis-ci.org/certtools/intelmq.svg?branch=master)](https://travis-ci.org/certtools/intelmq)
[![Coverage Status](https://coveralls.io/repos/github/certtools/intelmq/badge.svg?branch=master)](https://coveralls.io/github/certtools/intelmq?branch=master)
[![codecov.io](https://codecov.io/github/certtools/intelmq/coverage.svg?branch=master)](https://codecov.io/github/certtools/intelmq?branch=master)


**IntelMQ** is a solution for CERTs for collecting and processing security 
feeds, pastebins, tweets and log files using a message queuing protocol. 
It's a community driven initiative called **IHAP** (Incident Handling 
Automation Project) which was conceptually designed 
by European CERTs during several InfoSec events. Its main goal is to 
give to incident responders an easy way to collect & process threat 
intelligence thus improving the incident handling processes of CERTs.

IntelMQ's design was influenced by 
[AbuseHelper](https://bitbucket.org/clarifiednetworks/abusehelper), 
however it was re-written from scratch and aims at:

* Reduce the complexity of system administration
* Reduce the complexity of writing new bots for new data feeds
* Reduce the probability of events lost in all process with persistence functionality (even system crash)
* Use and improve the existing Data Harmonization Ontology
* Use JSON format for all messages
* Integration of the existing tools (AbuseHelper, CIF)
* Provide easy way to store data into Log Collectors like ElasticSearch, Splunk
* Provide easy way to create your own black-lists
* Provide easy communication with other systems via HTTP RESTFUL API

It follows the following basic meta-guidelines:

* Don't break simplicity - KISS
* Keep it open source - forever
* Strive for perfection while keeping a deadline
 * Reduce complexity/avoid feature bloat
 * Embrace unit testing
 * Code readability: test with unexperienced programmers
* Communicate clearly


## Table of Contents

1. [How to Install](#how-to-install)
2. [Developers Guide](#dev-guide)
3. [IntelMQ Manager](#control-platform)
4. [Incident Handling Automation Project](#incident-handling-automation-project)
5. [Data Harmonization](#data-harmonization)
6. [How to Participate](#how-to-participate)
6. [Licence](#licence)


<a name="how-to-install"></a>
## How to Install

See [UserGuide](docs/User-Guide.md).


<a name="dev-guide"></a>
## Developers Guide

See [Developers Guide](docs/Developers-Guide.md).

<a name="control-platform"></a>
## IntelMQ Manager

Check the [tool](https://github.com/certtools/intelmq-manager) and manage easily IntelMQ system.


<a name="incident-handling-automation-project"></a>
## Incident Handling Automation Project

* **URL:** http://www.enisa.europa.eu/activities/cert/support/incident-handling-automation
* **Mailing-list:** ihap@lists.trusted-introducer.org


<a name="data-harmonization"></a>
## Data Harmonization

IntelMQ use the Data Harmonization. Check the following 
[document](docs/Data-Harmonization.md).

<a name="how-to-participate"></a>
## How to participate

  * Subscribe to the Intelmq-dev Mailing list: https://lists.cert.at/cgi-bin/mailman/listinfo/intelmq-dev (for developers)
  * Watch out for our regular developers conf call
  * IRC: server: irc.freenode.net, channel: #intelmq
  * Via github issues 
  * Via Pull requests (please do read help.github.com first)
  

<a name="licence"></a>
## Licence

This software is licensed under GNU Affero General Public License version 3
