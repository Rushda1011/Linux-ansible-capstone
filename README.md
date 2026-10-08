 # Linux & Ansible Automation Project

This project demonstrates Linux server automation using Ansible.

## Technologies

- Linux
- Ansible
- Python
- MariaDB

## Project Objectives

- Configure Ansible for Linux server automation
- Verify connectivity between Ansible control node and managed nodes
- Automate Python installation
- Automate MariaDB installation
- Verify successful playbook execution

##  Project Structure

ansible.cfg
inventory
playbooks/
application/
documentation/
project_desc.txt

## Playbooks

- python_install.yml
Installs python3 on the managed Linux systems and verifies the installation.

- mariadb_install.yml
Installs mariadb on the managed Linux systems and verifies the service status.

## Verification

- Ansible ping connectivity was tested successfully.
- Python playbook execution was  successful.
- MariaDB playbook execution was successful.
- Python3 version was verified.
- Ansible PLAY RECAP showed successful execution with failed=0.

## Documentation
The project documentation is available as a PDF in this repository.


## Conclusion

This project demonstrates how Ansible can automate common Linux administration tasks and provide a repeatable approach to server configuration.

