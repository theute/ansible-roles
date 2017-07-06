# Overview

This repository constains a basic WildFly ansible role for starting and
stopping WildFly and for generating a JDR report.

Example [playbook](wildfly-playbook.yml) and [inventory](wildfly-inventory)
files are provided. The provided example playbook starts a server, generates
the JDR report and stops the server. 

Available role variables are listed in [inventory](wildfly-inventory) file.
Default values can be seen at the [defaults
file](roles/wildfly/defaults/main.yml). There are some other variables listed,
but should be considered as private variables.

# Attributions

This work is mostly based on [jmazzitelli
work](https://github.com/jmazzitelli/hawkular-services/commit/5fad2ecc80de73bc3246c1a4c86f44000d5baf4b)
and [pilhuhn work](https://github.com/pilhuhn/hawkular-agent-ansible).

Also, some ideas were taken from [jboss-standalone role from ansible-examples
repository](https://github.com/ansible/ansible-examples/tree/master/jboss-standalone).
