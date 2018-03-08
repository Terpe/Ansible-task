# Ansible-task
Using the virtualization tooling of your choice, provide code that creates (and destroys) two Linux virtual machines, named mysql1.local and backup1.local. The virtual machines must run on a developer workstation and not require cloud hosting services.
Implement Ansible code that installs, configures and starts mysql on mysql1.local.
Implement Ansible code that schedules a nightly backup of the mysql data files on mysql1.local. The backup data files must ultimately be stored on backup1.local. Assume there is adequate disk space on both virtual machines to perform this backup.
Provide one or more test cases to verify the backup.
As a bonus, automated one or more test cases.

