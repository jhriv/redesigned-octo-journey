Redesigned Octo Journey
===

A simple application as a Proof of Concept for basic application monitoring.

Requirements:
* Requires a databased (pgsl)
* Requires a queue (redis)
* Served as a webapp (8080)

Future Growth:
* Webserver for proxy (apache)
* (External) Load Balancer (haproxy)

This app is not distributed; that is not its purpose. This app is the endpoint to be monitored, along with its dependencies.

Out of scope:
* Failover
