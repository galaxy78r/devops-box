1- install virtualbox
2- Install vagrant
3- clone the project 
4- RUN  >>>> vagrant up
5- RUN  >>>  vagrant ssh-config
the command  will show you the IP,username,port and 
Use file """"""""key file path""""""""  you can use this key to ssh to this machine
5- Make a new ssh session and use the data provided from previous step to login to this machine
6- To use "ubuntu" user copy the .ssh folder from vagrant home to ubuntu home and change permissions
>>>> sudo cp -r .ssh/ /home/ubuntu/
>>>> sudo chown ubuntu:ubuntu /home/ubuntu/


# DevOps box
* A vagrant project with an ubuntu box with the tools needed to do DevOps

# tools included
* Terraform
* AWS CLI
* Ansible
* ibmcloud CLI
* kubectl
* KOPS


