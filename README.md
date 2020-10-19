# interviewtest
This has been created for the 3 part interview Technical Test
Please find parts 1, 2 and 3 here

Usage:
I have created Vagrant files for Virtualbox which you can find inside each directory.
I used Ubuntu desktop 20 with vagrant, ansible and virtualbox to create the dec environment.
To run the projects as you well know just cd into the project folder then 'vagrant up'.
Any variables that need to be set can be found in roles/"taskname"/vars/.

Ansible vault would normally be used to to store sensitive config files or password combos,
but in this case thought that simplicity is sometimes best.

# Changelog
 16/10/2020 updated orig code to use pure ansible instead of docker-compose.
 16/10/2020 added mysqlcluster code.
 16/10/2020 added reddis cluster code.
