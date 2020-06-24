# awx

These playbooks 

- create, stop, and terminate AWS EC2s;
- install and configure ntp 
- stop, start, enable, disable, restart a linux service
- configure EC2s 

# examples of the following ansible modules


get_url		- java playbook
lineinfile	- ec2_config/tasks/cre8afile.yml.v7, ec2_config/tasks/permitrootlogin.yml.v4
package		- ntp/tasks/main.yml.v2, java/tasks/Oracle.yml
service		- ntp/tasks/main.yml.v2, ec2_config/tasks/service.yml.v2
shell		- ec2_config/tasks/cre8afile.yml.v7, shell/tasks/enable.yml
template	- ntp/tasks/main.yml.v6




This is a sample of my directory layout:

root@awx /var/lib/awx/projects/AWS# ls -la *.yml
-rw-r--r--. 1 root root 232 Jun  8 10:45 ansible-localhost.yml
-rw-r--r--. 1 root root 244 Jun 12 16:09 checkssh.yml
-rw-r--r--. 1 root root  81 Jun 12 18:11 ec2_config.yml
lrwxrwxrwx. 1 root root  24 Jun 11 14:14 ec2_instance_info.yml -> ec2_instance_info.yml.v1
-rw-rw-r--. 1 root root 109 Jun  1 11:17 ec2_manage.yml
lrwxrwxrwx. 1 root root  11 Jun 19 14:09 java.yml -> java.yml.v2
lrwxrwxrwx. 1 root root  10 Jun 19 09:51 ntp.yml -> ntp.yml.v2
lrwxrwxrwx. 1 root root  45 Jun 10 18:57 permitrootlogin.yml -> roles/ec2_config/tasks/permitrootlogin.yml.v4
lrwxrwxrwx. 1 root root  18 Jun 11 10:27 regionfacts.yml -> regionfacts.yml.v2
-rw-r--r--. 1 root root  76 Jun 22 13:43 shell.yml
lrwxrwxrwx. 1 root root  13 Jun 11 17:36 showme.yml -> showme.yml.v4



root@awx /var/lib/awx/projects/AWS/roles# ls -la
total 8
drwxrwxr-x. 8 root root  214 Jun 24 12:56 .
drwxrwxr-x. 4 root root 4096 Jun 24 13:23 ..
drwxr-xr-x. 5 root root   47 Jun 10 08:45 ec2_config
-rw-r--r--. 1 root root 2556 Jun 16 12:30 ec2_config.tar.2020-06-16.gz
drwxrwxr-x. 5 root root   47 May 27 15:50 ec2_manage
lrwxrwxrwx. 1 root root    5 Jun 24 12:28 get_url -> java/
drwxr-xr-x. 9 root root  122 Jun 19 12:44 java
lrwxrwxrwx. 1 root root   11 Jun 24 12:56 lineinfile -> ec2_config/
drwxr-xr-x. 9 root root  140 Jun 18 12:43 ntp
lrwxrwxrwx. 1 root root    4 Jun 24 12:28 package -> ntp/
drwxr-xr-x. 5 root root   61 May 29 11:40 required_vars
lrwxrwxrwx. 1 root root    4 Jun 24 12:54 service -> ntp/
drwxr-xr-x. 4 root root   35 Jun 22 13:36 shell
lrwxrwxrwx. 1 root root    4 Jun 24 12:54 template -> ntp/


