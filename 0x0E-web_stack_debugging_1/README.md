# Web stack debugging #1
This was the second installment in a series of web stack debugging projects.
In this project, I was presented with malfunctioning or buggy web stacks confined
within isolated containers, and my assignment was to restore them to a functional state.
For each assignment, I authored a script that automated the required commands to rectify
the web stack.

## Description of Project Tasks

* **0. Nginx likes port 80**
  * [0-nginx_likes_port_80](./0-nginx_likes_port_80): Bash script that
  configures Nginx to run and listen to port 80 on all of a server's active IPv4's.

* **1. Make it sweet and short**
  * [1-debugging_made_short](./1-debugging_made_short): Bash script that
  configures Nginx to listen to port 80 without running on all of a server's
  active IPv4's.
