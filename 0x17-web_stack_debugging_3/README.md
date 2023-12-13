# Web stack debugging #3

This project marked the fourth installment in a sequence of web stack debugging assignments.
In each of these projects, I was presented with malfunctioning or buggy web stacks encapsulated
within isolated containers. My objective was to rectify and restore the web stack to a functional
state. For every task, I devised a script that automated the execution of the requisite commands 
needed to address and resolve the issues within the web stack.

## Tasks

* **0. Strace is your friend**
  * [0-strace_is_your_friend.pp](./0-strace_is_your_friend.pp): Puppet manifest
  that fixes a typo error causing a WordPress application being served by an Apache
  web server to fail.
  * Usage: `puppet apply 0-strace_is_your_friend.pp`
