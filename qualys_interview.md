# Qualys Interview
## Linux
1. In `top` cmd what is the meaning of value in front of load averages: `load average: 0.12, 0.45, 0.30`
2. how to create file which can not delete by user root, do not use sticky bit
3. what are important files in linux
4. If i give you fresh linux machine, how will you secure the system
5. how to make possible that, sshd process has access only with particular user. no other user
6. what is suid, guid, sticky bit
7. what is acl, In what condition it is applied?
8. dhcp,mac binding, DORA process
9. write a script that user will take two number and display larger number
10. from `/etc/passwd` file whose uid<500 , display the username only
	* `awk -F: '{if ($3 < 500) {print $1} }' /etc/passwd`
11. how to grep mobile number from file
12. after creating new user which files are changes
13. explain *iptables*
14. what is difference b/w encoding and encryption
15. what contains in */etc/passwd* file and */etc/shadow* file ? and */etc/shadow* file which algorithm uses for encryption?
16. which algorithm is best for encryption and security for now in market?
17. what is port no of ssh? explain ssh? flag `-i` explain properly, `-i` use for with help of private key we can login thr ssh
18. one user is created, password is set, after a while password is expired for that user. so how to set password, how to extend expiry? `chage` cmd
19. `chattr` cmd , explain
20. how to install packages in linux, explain with flavors, apt, yum, dpkg, rpm
21. how to remove dependecies in linux: debian, rhel..
22. `grep ditiss file1.txt` and give output as how many time ditiss word occured using grep  
* *  *
## Windows
1. What are the registry hives? list out
2. what is mean WMI
3. what is GPO, list group policies, how to set group policy for 30 users.
4. In GPO difference b/w *Computer configuration and user configuration*
5. what is active directory? what are the steps to create it
6. Steps to add one machine in already created domain
7. what are user attributes
8. what is user permissions
9. what are win+run shortcuts like *gpedit.msc*
10. what contains in *secpol.msc*
11. how find installed program's version without opening it. and how to find out program files of that program? *cmd line and gui both methods*
12. which protocol is used in active directory, and what is ldap
13

* *  *
## Networking
1. what is collision domain
2. what is broadcast domain
3. what is subnet mask of `192.168.10.10/27`

