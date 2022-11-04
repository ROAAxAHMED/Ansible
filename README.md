# Ansible
## Lab 1

[![N|Solid](https://upload.wikimedia.org/wikipedia/commons/0/05/Ansible_Logo.png)](https://docs.ansible.com/)






## Question 1

> Provision 3 EC2s on your AWS account, each with a different AMI (one with Ubuntu AMI, one with RHEL 8 AMI, and one with Amazon Linux AMI). 
Choose one of them as your control node and the rest will act as the managed nodes as can be seen in the figure below:


- Install Ansible on your control node.
- Configure SSH key based login on your setup.
- User ‘ansible’ is used for all of your nodes.
- Create ‘lab1’ directory as your first Ansible project.
- Follow best practices by setting up inventory, and ansible.cfg. Note: your ansible.cfg must be configured for sudo privilege escalation
- Add ‘servers’ as your inventory group.
- Use hostnames as shown in the figure below.
- Verify that your control node can connect to your managed nodes by using ping module in an ad-hoc command.
- Use ad-hoc command to add a user with the following properties:
• Name: greenie
• UID: 4000
- Verify that ‘greenie’ has been added on your managed nodes using ad-hoc command
Dillinger is a cloud-enabled, mobile-ready, offline-storage compatible,
AngularJS-powered HTML5 Markdown editor.
