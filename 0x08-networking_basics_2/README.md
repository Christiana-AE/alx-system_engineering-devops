# Networking Basics
Project reveiwing the basics of networking

Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
- What is localhost/127.0.0.1
- What is 0.0.0.0
- What is /etc/hosts
- How to display your machine’s active network interfaces

Read the manual or help (man):

ifconfig
telnet
nc
cut

## Tasks
0. Write a Bash script that configures an Ubuntu server with the below requirements.

Requirements:

localhost resolves to 127.0.0.2
facebook.com resolves to 8.8.8.8.

1. Write a Bash script that displays all active IPv4 IPs on the machine it’s executed on.
Obviously, the IPs displayed may be different depending on which machine you are running the script on.

Note that we can see our localhost IP

## Advanced

2. Write a Bash script that listens on port 98 on localhost.

Terminal 0

Starting my script.

Terminal 1

Connecting to localhost on port 98 using telnet and typing some text.

Terminal 0

Receiving the text on the other side.

For the sake of the exercise, this connection is made entirely within localhost. This isn’t really exciting as is, but we can use this script across networks as well. Try running it between your local PC and your remote server for fun!

