# Configuration management

Project to review configuration management that allows one implement a parallel job-execution system to execute commands to one or multiple servers at the same time. One can apply an action to a selected set of servers by applying a filter such as the server’s hostname or any other metadata.

## Tasks
0. Using Puppet, create a file in /tmp.

Requirements:

File path is /tmp/school
File permission is 0744
File owner is www-data
File group is www-data
File contains I love Puppet

1. Using Puppet, install flask from pip3.

Requirements:

Install flask
Version must be 2.1.0

2. Using Puppet, create a manifest that kills a process named killmenow.

Requirements:

Must use the exec Puppet resource
Must use pkill 
