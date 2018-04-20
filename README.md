# Training17
Academy trainings

-------------------------
EASY

1. Create account 'administrator' with following settings:
UID: 1000
GID: 1000
GECOS: system administrator
Shell: /bin/bash

2. Generate SSH key for account 'administrator';

3. Add account 'administrator' to 'wheel' group;

4. Allow all accounts, which are in 'wheel' group to execute all commands from all accounts through sudo;

5. Customer is complaining that user 'account' cannot execute 'cat' command. Please fix this problem;

6. Find and install locally placed rpm package, which is called package.rpm;

------------------------------------
MEDIUM

1. Customer is asking to install httpd service. Service should listen on 8888 port. Also port forwarding should be configured so port 80 should be redirected to port 8888. SELinux should stay in Enforced mode.

2. Drop packets from IP range !!!Define!!!, which are trying to reach port 80 and port 8888. All dropped packets should be logged into /var/log/dropped.log and /var/log/messages should not have duplicate log entries. For security reasons packets should be forwarded to external logs server !!!IP!!! via TCP protocol.

3. Create new partition in LVM for NFS mount which should be under /mnt/nfs. It should survive reboot. Use /dev/sdc all disk space for this task.

4. Export /mnt/nfs to !!!IP!!!

5. !!!Configure SAR and use cron to send SAR stats!!!

-----------------------------------
HIGH

1. You have a broken disk in /dev/sdb, you need to retreive file contents. File can be found under LVM volume.

2. User is complaining that server is running slow.

3. !!!Create stats using RRD!!! 
