# Firewall

In the context of this project, I employed the `ufw` (Uncomplicated Firewall) utility
to configure and manage the firewall settings on the web servers that were allocated
to me by ALX SE School. The utilization of `ufw` allowed for a streamlined and straightforward
approach to firewall configuration, enhancing the security posture of the deployed web servers.
Through the careful configuration of firewall rules, I aimed to fortify the servers against
unauthorized access and potential security threats, ensuring a robust defense mechanism for the web infrastructure.

## Project Tasks

* **0. Block all incoming traffic but**
  * [0-block_all_incoming_traffic_but](.0-block_all_incoming_traffic_but): Bash
  script that installs a `ufw` firewall to block all incoming traffic except for
  ports `22`, `443` and `80` on a web server.

* **1. Port forwarding**
  * [100-port_forwarding](./100-port_forwarding): `ufw` configuration file that
  configures a firewall to redirect port `8080/TCP` to port `80/TCP`.
