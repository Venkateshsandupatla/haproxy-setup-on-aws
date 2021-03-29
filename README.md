# haproxy-setup-on-aws
I used roles to configure the setup , The directories are roles.
This repo is for setting up haproxy in aws ec2 instance and connecting ec2-instances as webservers  to our haproxy.
1. we have directory named as ec2instances --> From this you can launch ec2 instances.
2. we have directory named as haproxy ---> From this you can set up haproxy in ec2-instance which we have launched and join the ec2-instances 
3. we have directory named as webserver ---> From this you can able to setup apche webserver in our ec2-instnaces.
4. we have a file named as web.yml --> It is the final playbook for creating entire infrastructure.
