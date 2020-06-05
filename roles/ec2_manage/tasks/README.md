create links to the correct playbooks;

for example:

[root@awx tasks]# ll
total 48
-rw-r--r--. 1 root root 165 Jun  5 13:25 absentAll.yml
-rw-r--r--. 1 root root 206 Jun  5 13:38 absentX.yml
lrwxrwxrwx. 1 root root  13 Jun  5 13:27 absent.yml -> absent.yml.v3
-rw-rw-r--. 1 root root 163 Jun  4 17:51 absent.yml.v1
-rw-r--r--. 1 root root 205 Jun  5 09:08 absent.yml.v2
-rw-r--r--. 1 root root 181 Jun  5 13:36 absent.yml.v3
lrwxrwxrwx. 1 root root  13 Jun  5 09:27 launch.yml -> launch.yml.v1
-rw-rw-r--. 1 root root 888 Jun  4 14:23 launch.yml.v1
lrwxrwxrwx. 1 root root  11 Jun  5 09:27 main.yml -> main.yml.v1
-rw-rw-r--. 1 root root 238 Jun  5 09:27 main.yml.v1
-rw-r--r--. 1 root root 110 Jun  5 13:25 stoppedAll.yml
-rw-r--r--. 1 root root 151 Jun  5 13:32 stoppedX.yml
lrwxrwxrwx. 1 root root  14 Jun  5 13:27 stopped.yml -> stopped.yml.v3
-rw-r--r--. 1 root root 109 Jun  5 08:46 stopped.yml.v1
-rw-rw-r--. 1 root root 144 Jun  5 08:49 stopped.yml.v2
-rw-r--r--. 1 root root 183 Jun  5 13:33 stopped.yml.v3

