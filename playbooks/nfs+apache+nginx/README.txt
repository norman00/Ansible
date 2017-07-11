
- - - - - - - - - - - - - - - - - - - - - - - - - - - - -
               EPAM-ACM Export Program

         Maintainer eduardo_rascon@fakedomain.com
                     1-11-2017
- - - - - - - - - - - - - - - - - - - - - - - - - - - - -

This playbook configures and secure the following hosts
previosly declared on /etc/ansible/host file

[loadbalancers]
nginx ansible_host=192.168.56.109

[nfs]
nfs ansible_host=192.168.56.108

[webservers]
web2 ansible_host=192.168.56.106
web1 ansible_host=192.168.56.105

- - - - - - - - - - - - - - - - - - - - - - - - - - - - -

Execute instructions:
ansible-playbook play.yml

- - - - - - - - - - - - - - - - - - - - - - - - - - - - -

