0x07. Networking basics #0
DevOps     Network

Resources
Read or watch:

OSI model
Different types of network
LAN network
WAN network
Internet
MAC address
What is an IP address
Private and public address
IPv4 and IPv6
Localhost
TCP and UDP
TCP/UDP ports List
What is ping /ICMP
Positional parameters
man or help:

netstat
ping
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

OSI Model
What it is
How many layers it has
How it is organized
What is a LAN
Typical usage
Typical geographical size
What is a WAN
Typical usage
Typical geographical size
What is the Internet
What is an IP address
What are the 2 types of IP address
What is localhost
What is a subnet
Why IPv6 was created
TCP/UDP
What are the 2 mainly used data transfer protocols for IP (transfer level on the OSI schema)
What is the main difference between TCP and UDP
What is a port
Memorize SSH, HTTP and HTTPS port numbers
What tool/protocol is often used to check if a device is connected to a network

Requirements
General
Allowed editors: vi, vim, emacs
All your Bash script files will be interpreted on Ubuntu 20.04 LTS
All your files should end with a new line
A README.md file, at the root of the folder of the project, is mandatory
All your Bash script files must be executable
Your Bash script must pass shellcheck without any error
The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
The second line of all your Bash scripts should be a comment explaining what is the script doing
More Info
The second line of all your Bash scripts should be a comment explaining what is the script doing

For multiple choice question type tasks, just type the number of the correct answer in your answer file, add a new line for every new answer, example:

What is the most important position in a software company?

Project manager
Backend developer
System administrator
sylvain@ubuntu$ cat foo_answer_file
3
sylvain@ubuntu$
Source for question 1 here

Tasks
0. OSI model
mandatory
OSI (Open Systems Interconnection) is an abstract model to describe layered communication and computer network design. The idea is to segregate the different parts of what make communication possible.

It is organized from the lowest level to the highest level:

The lowest level: layer 1 which is for transmission on physical layers with electrical impulse, light or radio signal
The highest level: layer 7 which is for application specific communication like SNMP for emails, HTTP for your web browser, etc
Keep in mind that the OSI model is a concept, it’s not even tangible. The OSI model doesn’t perform any functions in the networking process. It is a conceptual framework so we can better understand complex interactions that are happening. Most of the functionality in the OSI model exists in all communications systems.



In this project we will mainly focus on:

The Transport layer and especially TCP/UDP
On the Network layer with IP and ICMP
The image bellow describes more concretely how you can relate to every level.



Questions:

What is the OSI model?

Set of specifications that network hardware manufacturers must respect
The OSI model is a conceptual model that characterizes the communication functions of a telecommunication system without regard to their underlying internal structure and technology
The OSI model is a model that characterizes the communication functions of a telecommunication system with a strong regard for their underlying internal structure and technology
How is the OSI model organized?

Alphabetically
From the lowest to the highest level
Randomly
Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x07-networking_basics
File: 0-OSI_model
