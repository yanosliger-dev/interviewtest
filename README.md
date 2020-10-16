# interviewtest
This has been created for the 3 part interview Technical Test
Please find parts 1, 2 and 3 here

Vagrant file is here for each part
The Docker and Ansible with Vagrant is quite new to me really enjoyed these tasks.
I have been working on Puppet for a long time with KVM and VMWare so change has been nice,
it is like riding a bike :)
I think there is a lot of room for improvement with the coding especially with the VM creation in rabbitmq, 
that could be done on the fly instead of using docker-compose file,
but sadly I didn't want to run out of time and not have something finished for you.

To run the projects as you well know just cd into the project folder then 'vagrant up'

Any variables that need to be set can be found in roles/taskname/vars/

Should use ansible vault to secure these for any playbooks used in the open


# Changelog
16/10/2020 updated orig code to use pure ansible instead of docker-compose
16/10/2020 added mysqlcluster code 
16/10/2020 added reddis cluster code
