gibbot
======

Growable IRC Bash Bot

Gibbot is a set of utility functions for writing irc bots in bash.

Usage
=====

To use simply:
 Set $BOTPATH
 Source gibbot into a script.
 Overwrite the functions you want from gibbot_overrides
 Call:   bot_run $0 $@
 
Examples
========
templatebot -s myircserver -c chat
logbot -s myircserver -c chat 
rotabot -s myircserver -c chat 
