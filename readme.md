Approach:
Changes are made here to demonstrate Jenkin-github web-hook functionality
--Master branch is usually the most stable branch as such. Jenkins should pull only when codes are committed to the master branch
I used vagrant to spin up a centos 7 virtual machine
I used Cloudformation to create AWS Resources which include a Amazon Linux EC2 Instance
I logged into the EC2 instance using SSH
Ansible was installed inside the EC2 instance
I used ansible playbook to download wordpress
