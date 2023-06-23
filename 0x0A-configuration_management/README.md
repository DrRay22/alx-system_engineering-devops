## 0x0A. Configuration management

## Resources
Read or watch:

Intro to Configuration Management
Puppet resource type: file (check “Resource types” for all manifest types in the left menu)
Puppet’s Declarative Language: Modeling Instead of Scripting
Puppet lint
Puppet emacs mode

## Description
In this project, I started working with Puppet as a configuration management tool. I practiced writing Puppet manifest files to create a file, install a package, and execute a command.

### Tasks 📃
0. Create a file

0-create_a_file.pp: Puppet manifest file that creates a file school in the /tmp directory.
File permissions: 0744.
File group: www-data.
File owner: www-data.
File content: I love Puppet.
1. Install a package

1-install_a_package.pp: Puppet manifest file that install flask from pip3.
2. Execute a command

2-execute_a_command.pp: Puppet manifest file that kills the process killmenow.
