---
layout: default_md
title: ActiveMQ 3.0 Release 
title-class: page-title-activemq5
type: activemq5
---

[Overview](overview) > [Download](download) > [ActiveMQ 3.2.1 Release](activemq-30-release)

New and Noteworthy
------------------

This new release includes the following

*   a new 'discovery' transport [protocol](FeaturesFeatures/Features/uri-Connectivity/protocols) for a pure client-only peer network - a self discovering cluster which automatically finds the brokers available on the network (as opposed to the 'peer' protocol which is a complete peer based JMS network).
*   migrated from the org.activemq to org.activemq package name hierarchy
*   improved support for more JDBC databases for persistence
*   an optimised wire protocol (which is unfortunately not compatible with 2.x)
*   more test cases and fixes of the [JCA Container](jca-container)
*   various performance enhancements and bug fixes

Download Here
-------------

Download|Description
---|---
[activemq-release-3.0.zip](http://dist.codehaus.org/activemq/distributions/activemq-release-3.0.zip)|Binary Distribution in zip package
[activemq-release-3.0-src.zip](http://dist.codehaus.org/activemq/distributions/activemq-release-3.0-src.zip)|Source Distribution in zip package
[activemq-release-3.0.tar.gz](http://dist.codehaus.org/activemq/distributions/activemq-release-3.0.tar.gz)|Binary Distribution in gz package
[activemq-release-3.0-src.tar.gz](http://dist.codehaus.org/activemq/distributions/activemq-release-3.0-src.tar.gz)|Source Distribution in gz package

Changelog
---------

For a more detailed view of new features and bug fixes, see the [release notes](http://jira.activemq.org/jira/secure/ReleaseNote.jspa?version=11500&styleName=Html&projectId=10520&Create=Create)

You may also want to look at [the previous Changelog](activemq-21-release)

