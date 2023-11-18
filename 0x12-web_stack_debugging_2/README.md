# Web Stack Debugging #2

This marked the third installment in a sequence of web stack debugging projects.
Within these endeavors, I was presented with malfunctioning or bug-ridden web stacks
encapsulated within isolated containers. My responsibility involved rectifying these
issues to restore the web stack to a functional state. For every assignment, I crafted
a script that automated the requisite commands for resolving the web stack issues.

## Project Tasks

* **0. Run software as another user**
  * [0-iamsomeonelese](./0-iamsomeonelese): Bash script that runs the command
  `whoami` under the user passed as argument.
  * Usage: `./0-iamsomeonelese <user>`

* **1. Run Nginx as Nginx**
  * [1-run_nginx_as_nginx](./1-run_nginx_as_nginx): Bash script that fixes a
  web server to run Nginx listening on port `8080` as the `nginx` user.

* **2. 7 lines or less**
  * [100-fix_in_7_lines_or_less](./100-fix_in_7_lines_or_less): Bash script
  that fixes a web server to run Nginx listening on port `8080` as the `nginx`
  user.
  * 7 lines long.
