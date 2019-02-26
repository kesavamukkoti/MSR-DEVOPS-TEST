# MSR-DEVOPS-TEST
Complete Code for the given task

Task I: Created two EC2 Instances in AWS Cloud 

•	Instance Type: t2.micro

•	Operating System:  Ubuntu Server 16.04 LTS

•	Hostname of Instance 1 : MSR-test-Instance-1

•	Hostname of Instance 2 : MSR-test-Instance-2



Task II: To install the following softwares I have created an ansible playbook file (Refere to the playbook1.yml file)

Installed Softwares:

•	NVM – Version 0.33.2

•	Node – 8.12.0

•	Docker – 18.06 or latest

•	Docker Compose – 1.13 or latest

•	Openssl – latest version

•	Git – latest version

We have to launch a new Ec2 machine which is a controlling machine and installing anisible to run the playbook file (Installation.yml)

Installation Steps:

sudo apt-get update

sudo apt-get install software-properties-common

sudo apt-add-repository ppa:ansible/ansible

sudo apt-get update

sudo apt-get install ansible

After Installation of Ansible we will run the ansible playbook file.

ansible-playbook Installation.yml

It will install all the softwares listed in the ploybook in both the hosts

before that we have to configure both the hosts in the ansible/host location.

Task III: I have created a index.html file and deployed using anisible playbook file (Deploy.yml)

To run the playbook: ansible-playbook Deploy.yml

Task IV:I have created a Database.yml file which will install the CouchDB Database and runs the service. 

To run the playbook: ansible-playbook Database.yml


I have tried the best to cover all the details as per my knowledge.





