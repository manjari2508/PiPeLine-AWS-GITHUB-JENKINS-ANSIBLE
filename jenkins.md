JENKINS

. Our jenkins server will be setup through an Amazon Web Service (AWS) EC2 Instance AMI(AMAZON MACHINE IMAGE) of RedHat Enterprise Linux.
on which all the basic and patch files of jenkins was installed through (sudo yum install jenkins)command using our putty application to configure settings of our Jenkins server.

.For the complete and successful deployment of the job on the web server this stage is instrumental for successful building of the source code and then pushing the result on the playbook.yml file on the Ansible server which inturn gets pushed on the web server for the end user to receive.

.This was followed by opening and logging into the jenkins through the public ip address of this machine as the url with port number 8080 where our Pipeline project was created
