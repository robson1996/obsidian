 #### AWS
 
 
 068174609777
bC!=+M(^_Bo*4}


scalefusion - 1Q1@GtesAG3%7[


### Manage Cluster in GF


```
asadmin list-clusters --port 9048
asadmin list-instances --port 9048
```

```
asadmin start-cluster UICluster --port 9048
asadmin start-instance trac|adaptor| --port 9048
```

## Manage Standalone Instances in GF

```
asadmin list-domains 
asadmin start-domain
asadmin stop-domain
```



Medfit
asiwawa@dxcentre.com--- Pi5c52611

AIMPP
robson@mobipay.com.na: 7215Nketa9#


### Setup GitHub for SSH authentication


```
ssh-keygen
ssh -T git@github.com

git remote add github git@github.com:robson1996/maas.git
```


enable repos acces
subscription-manager config --rhsm.manage_repos=1

Fix corrupt dracut

dracut --regenerate-all -f && grub2-mkconfig -o /boot/grub2/grub.cfg

Rollback corrupt kernel

Check the default kernel:

grubby --default-kernel


check kernel indexes

grubby --info=ALL


Set the kernel to a different kernel
grubby --set-default=

changeit@2023

Proxmox

U: Robson
P: Xhaka1975...#


VDB

idaas/ i9a7V6f5W3qk
idaasext/ i9a7V6f5W3qd
idaasnotification/ i9a7V6f5W3qe
SID: ORCL

PDB
mwcore/mwcore
SID: ORCL


MFUATDB

mfsadmin/MTC_MFS_2023##

servicename: MFSUATDB

MV2 Setup


MFS 

DAS UAT - admin
DAT PROD - same as verifi T@....


DOCKER

**********************************************************************************************************************************

docker run -itd --name mfsuat --privileged=true --hostname mfsuat --volume mfsuat:/home --add-host mtcuatmfsdas01.maris.com.na:172.19.171.254 --add-host mtcuatmfsproxy01.maris.com.na:172.19.174.147 --add-host mtcuatmfsproxy02.maris.com.na:172.19.174.247  --add-host mtcuatmfsldap01.maris.com.na:172.19.171.71  --add-host mtcuatmfsldap02.maris.com.na:172.19.171.154 --add-host mtcuatmfschannel01.maris.com.na:172.19.171.36 --add-host mtcuatmfschannel02.maris.com.na:172.19.171.15 --add-host mtcuatmfsui01.maris.com.na:172.19.171.206 --add-host mtcuatmfsui02.maris.com.na:172.19.171.98 --add-host mtcuatmfsws01.maris.com.na:172.19.171.41 --add-host mtcuatmfsws02.maris.com.na:172.19.171.86 --add-host mtcuatmfsproton01.maris.com.na:172.19.171.197 --add-host mtcuatmfsproton02.maris.com.na:172.19.171.174 --add-host mtcuatmfsadapt01.maris.com.na:172.19.171.48 --add-host mtcuatmfsadapt02.maris.com.na:172.19.171.132 --add-host mtcuatmfscore01.maris.com.na:172.19.171.157 --add-host mtcuatmfscore02.maris.com.na:172.19.171.167 centosbase:7 /usr/sbin/init

docker run -itd --name mfs-master --privileged=true --hostname mfs-master --volume mfsuat:/root --add-host mtcuatmfsdas01.maris.com.na:172.19.171.254 --add-host mtcuatmfsproxy01.maris.com.na:172.19.174.147 --add-host mtcuatmfsproxy02.maris.com.na:172.19.174.247  --add-host mtcuatmfsldap01.maris.com.na:172.19.171.71  --add-host mtcuatmfsldap02.maris.com.na:172.19.171.154 --add-host mtcuatmfschannel01.maris.com.na:172.19.171.36 --add-host mtcuatmfschannel02.maris.com.na:172.19.171.15 --add-host mtcuatmfsui01.maris.com.na:172.19.171.206 --add-host mtcuatmfsui02.maris.com.na:172.19.171.98 --add-host mtcuatmfsws01.maris.com.na:172.19.171.41 --add-host mtcuatmfsws02.maris.com.na:172.19.171.86 --add-host mtcuatmfsproton01.maris.com.na:172.19.171.197 --add-host mtcuatmfsproton02.maris.com.na:172.19.171.174 --add-host mtcuatmfsadapt01.maris.com.na:172.19.171.48 --add-host mtcuatmfsadapt02.maris.com.na:172.19.171.132 --add-host mtcuatmfscore01.maris.com.na:172.19.171.157 --add-host mtcuatmfscore02.maris.com.na:172.19.171.167 --add-host mtcuatmfsdb01.maris.com.na:172.19.171.152 --add-host mtcdevmfs01.maris.com.na:172.19.170.68 centosbase:7 /usr/sbin/init


docker run -itd --name mfs-prod --privileged=true --hostname mfs-prod --volume mfsprod:/root --add-host mtcprdmfsdas01.maris.com.na:172.19.172.134 --add-host mtcprdmfsldap01.maris.com.na:172.19.172.25 --add-host mtcprdmfsldap02.maris.com.na:172.19.172.113 --add-host mtcprdmfschannel01.maris.com.na:172.19.172.241 --add-host mtcprdmfschannel02.maris.com.na:172.19.172.49 --add-host mtcprdmfsui01.maris.com.na:172.19.172.207 --add-host mtcprdmfsui02.maris.com.na:172.19.172.200 --add-host mtcprdmfsws01.maris.com.na:172.19.172.160 --add-host mtcprdmfsws02.maris.com.na:172.19.172.5 --add-host mtcprdmfsproton01.maris.com.na:172.19.172.70 --add-host mtcprdmfsproton02.maris.com.na:172.19.172.109 --add-host mtcprdmfsadapt01.maris.com.na:172.19.172.18 --add-host mtcprdmfsadapt02.maris.com.na:172.19.172.103 --add-host mtcprdmfscore01.maris.com.na:172.19.172.21 --add-host mtcprdmfscore02.maris.com.na:172.19.172.102 --add-host mtcprdmfsproxy01.maris.com.na:172.19.174.107 --add-host mtcprdmfsproxy02.maris.com.na:172.19.174.138 --add-host mtcprdmfsdb01.maris.com.na:172.19.173.70 --add-host mtcprdmfsdb01.maris.com.na:172.19.175.70 --add-host mtcprdmfsdb02.maris.com.na:172.19.173.111 --add-host mtcprdmfsdb02.maris.com.na:172.19.175.111 centosbase:7 /usr/sbin/init

[mfs]
mtcuatmfsdas01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfsproxy01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfsproxy02.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfsldap01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfsldap02.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfschannel01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfschannel02.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfsui01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfsui02.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfsws01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfsws02.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfsproton01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfsproton02.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfsadapt01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfsadapt02.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfscore01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfscore02.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'


[dev]
mtcdevmfs01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'

[das]
mtcuatmfsdas01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'

[proxies]
mtcuatmfsproxy01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfsproxy02.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'

[ldap]
mtcuatmfsldap01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfsldap02.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'

[channel]
mtcuatmfschannel01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfschannel02.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'

[ui]
mtcuatmfsui01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfsui02.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'

[ws]
mtcuatmfsws01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfsws02.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'

[proton]
mtcuatmfsproton01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfsproton02.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'

[adaptors]
mtcuatmfsadapt01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfsadapt02.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'

[core]
tmfscore01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'
mtcuatmfscore02.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'

[db]
mtcuatmfsdb01.maris.com.na ansible_ssh_common_args='-o StrictHostKeyChecking=no' ansible_user=robson ansible_ssh_pass='Xhaka1975...#'


***************************************************EC2 User and Meta Data ************************************
#By default, ec2 user-data does not run after the initial instance launch cycle. Even if you stop and modify the user-data attributes, cloudinit will not run the script. You would have to run it manually from withing the instance using
sh /var/lib/cloud/instances/user-data.txt

#You can also change the mime multi-part file

Content-Type: multipart/mixed; boundary="//"
MIME-Version: 1.0

--//
Content-Type: text/cloud-config; charset="us-ascii"
MIME-Version: 1.0
Content-Transfer-Encoding: 7bit
Content-Disposition: attachment; filename="cloud-config.txt"

#cloud-config
cloud_final_modules:
- [scripts-user, always]

--//
Content-Type: text/x-shellscript; charset="us-ascii"
MIME-Version: 1.0
Content-Transfer-Encoding: 7bit
Content-Disposition: attachment; filename="userdata.txt"

#!/bin/bash
/bin/echo "Hello World" >> /tmp/testfile.txt
--//--



#Disable instance meta-data
aws ec2 modify-instance-metadata-options --instance-id i-07166735edaefaf3c --http-endpoint disabled
*************************************************************************************************************



************************************************Environment Variables*************************************************

#change the following files on user home directory: .bashrc (no login shell) .bash_profile (login shell)


export PATH=$PATH:/opt/glassfish4/glassfish/bin/:/opt/jdk1.8.0_191/bin/:/opt/apacheds-2.0.0.AM26/bin/
export JAVA_HOME=/opt/jdk1.8.0_191
export JRE_HOME=/opt/jdk1.8.0_191/jre
export HISTTIMEFORMAT="%d/%m/%y %T "
export HISTSIZE=10000


******************************MFS Dev Access******************************************************

https://172.19.30.200:7081/mw-scm/protected/startscreen.xhtml?v=x31jvb
https://172.19.30.200:7081/mw-aim/protected/startscreen.xhtml?v=x31jvb
https://172.19.30.200:7081/mw-ftm/protected/startscreen.xhtml?v=x31jvb
https://172.31.4.28:7081/mw-ftm/protected/startscreen.xhtml?v=x31jvb


MFS DEV ACCESS NEW

https://172.19.170.68:7081/mw-scm/protected/startscreen.xhtml?v=x31jvb
https://172.19.170.68:7081/mw-aim/protected/startscreen.xhtml?v=x31jvb
https://172.19.170.68:7081/mw-ftm/protected/startscreen.xhtml?v=x31jvb


**************************Verifi Firewall*******************************************

https://54.217.95.44:8112/login?redir=%2F



***********************LAC Public IPs********************************************



LDR


luderitz.dyndns-web.com 30566



OPE



ERG, port 30566

TN 41.182.255.20 *
MTN 196.31.245.118:30566






****************************************************************
CoW, port 30566

TN 196.20.16.5
MTN 10.4.0.5 *



*************Add routes*************************************

ip route add 172.31.5.14/32 via 172.16.20.156 dev eth0



********************************************************
************************Firewalld**********************

firewall-cmd --list-all
firewall-cmd --zone=public --permanent --add-port=8008/tcp --add-port=9000-9100/tcp --add-port=7000-9100/tcp
firewall-cmd --reload

firewall-cmd --zone=public --permanent --add-port=10389/tcp


The credentials for MFS servers are as follows:

Username: root
Password: MTC_MFS2023##





**********************Importing a 3rd Party Cert*******************

Importing 3rd Party SSL certificate



Login to DAS and change directory to: /opt/glassfish4/glassfish/domains/das/config

copy the SSL certificate you received from 3rd party to DAS VM into the location mentioned above and run this command: 

keytool -importcert -keystore cacerts.jks -alias "ADD YOUR Alias NAME Here" -file " Certificate file NAme you uploaded"


Remember to rename the allias name to your preffered name. 
when prompted for a password type in: changeit


To confirm that the certficate was imported successfully run the following command: 

keytool -list -keystore cacerts.jks -alias "Your Alias Name" -v

keytool -importkeystore -deststorepass changeit -destkeystore keystore.jks -srckeystore mobivend2023.p12 -srcstoretype PKCS12 -srcstorepass changeit  -srcalias mobivend -destalias mobivend2023

keytool -importcert -keystore cacerts.jks -trustcacerts  -file mobivend2023.cer -alias mobivend2023


**********GF Commands*********************************************************
asadmin stop-domain
asadmin start-domain

*************************OpenSSL commands****************
Checking the certificate

openssl s_client -servername [hostname] -connect [hostname]:443
openssl s_client -servername [hostname] -connect [hostname]:443 | openssl x509 -noout -dates

Reading the CSR

openssl req -in [completed certificate request].csr -noout -text


Checking if the key and the certificate match

openssl x509 -in [certificate name].crt -noout -modulus | openssl sha1
openssl rsa -in [private key].key -noout -modulus | openssl sha1


Check if Issuer and Cert match

openssl verify -CAfile [issuer] [certificate]

eg.. openssl verify -CAfile DigiCertCA.crt mobivend_mobipay_com_na.crt



Combining the private key and certificate
openssl pkcs12 -export -in name_of_the_certificate_file.cer -inkey mobivend.key -name mobivend -out mobivend.p12


*****************************************************************************************************************************************
Uploading Mobivend certificate on Paypulse DAS;

1. copy the new certification onto PP DAS to this location: /opt/glassfish4/glassfish/domains/das/config/
2. login to DAS via putty and change directory to:  /opt/glassfish4/glassfish/domains/das/config/
3. Comibine the new certificate with the private key using this command:
	 openssl pkcs12 -export -in name_of_the_certificate_file.cer -inkey mobivend.key -name mobivend -out mobivend.p12
	When prompt to enter a password, please set this password "changeit" no Caps
4.Once you comibined the certificate & the private key, you can now go ahead and import the certificate into GF using the command below
	keytool -importkeystore -deststorepass changeit -destkeystore keystore.jks -srckeystore mobivend.p12 -srcstoretype PKCS12 -srcstorepass changeit  -srcalias mobivend -destalias mobivendjune2022
4. Run the command below to confirm if the certificate was imported successfully
	keytool -list -keystore keystore.jks -alias mobivendjune2022 -v
5. Now stop and start DAS using the commands below
	asadmin stop-domain
	asadmin start-domain
6. Once DAS has been restarted, Login to DAS console and restart Adaptors.


THAT IS ALL, YOU HAVE SUCCESSFULLY UPLOADED THE NEW CERTIFICATE ON DAS!!!

*****Changing GF Port

asadmin set server.http-service.http-listener.admin-listener.port=9048

asadmin set configs.config.server-config.network-config.network-listeners.network-listener.admin-listener.port=9048



****************************Swap **************************************************

sudo dd if=/dev/zero of=/swapfile count=16384 bs=1MiB


ls -lh /swapfile

sudo chmod 600 /swapfile
sudo mkswap /swapfile
sudo swapon /swapfile
swapon -s
free -m

modify the VM to auto mount the file even after restarts 

vi /etc/fstab
/swapfile   swap    swap    sw  0   0


optimisation of swap

cat /proc/sys/vm/swappiness
The swappiness parameter determines how often your system swaps data out of memory to the swap space. This is a value between 0 and 100 that represents the percentage of memory usage that will trigger the use of swap.

With values close to zero, the system will not swap data to the drive unless absolutely necessary
sudo nano /etc/sysctl.conf
vm.swappiness = 10



***********************************Extending Size of EBS Volume **************************

lsblk 

growpart /dev/[device name] [partition number]

xfs_growfs [mount point] or [device with partition number]
mkfs 

****************************************************************************************
Verifi Credentials

Production

Admin - robsonchirara

DEV
sup - robsonchirara
bo  - robsonc
admin - allen


###How to to repair corrupt mysql table

[root@support ~]# myisamchk -s /var/lib/mysql/osticketdb/ost_session.MYI
myisamchk: error: 140 when opening MyISAM-table '/var/lib/mysql/osticketdb/ost_session.MYI'
[root@support ~]# systemctl stop httpd
[root@support ~]# systemctl stop mysqld
[root@support ~]# myisamchk -s /var/lib/mysql/osticketdb/ost_session
myisamchk: MyISAM file /var/lib/mysql/osticketdb/ost_session
myisamchk: warning: Table is marked as crashed
myisamchk: warning: 4 clients are using or haven't closed the table properly
myisamchk: error: Record at pos: 382362148 is not remove-marked
myisamchk: error: record delete-link-chain corrupted
myisamchk: error: Found 362 keys of 361
myisamchk: error: Wrong bytesec: 119-115-32 at linkstart: 382362148
MyISAM-table '/var/lib/mysql/osticketdb/ost_session' is corrupted
Fix it using switch "-r" or "-o"
[root@support ~]# myisamchk -r --update-state /var/lib/mysql/osticketdb/ost_session
- recovering (with sort) MyISAM-table '/var/lib/mysql/osticketdb/ost_session'
Data records: 361
- Fixing index 1
Wrong bytesec: 119-115- 32 at  382362148; Skipped
- Fixing index 2
- Fixing index 3
Data records: 360
[root@support ~]# myisamchk -s /var/lib/mysql/osticketdb/ost_session
[root@support ~]# systemctl start httpd
[root@support ~]# systemctl start mysqld




firewall-cmd --zone=public --permanent --add-port=1521/tcp


172.19.172.134     mtcprdmfsdas01.maris.com.na
172.19.172.25      mtcprdmfsldap01.maris.com.na
172.19.172.113     mtcprdmfsldap02.maris.com.na
172.19.172.241     mtcprdmfschannel01.maris.com.na
172.19.172.49      mtcprdmfschannel02.maris.com.na
172.19.172.207     mtcprdmfsui01.maris.com.na
172.19.172.200     mtcprdmfsui02.maris.com.na
172.19.172.160     mtcprdmfsws01.maris.com.na
172.19.172.5       mtcprdmfsws02.maris.com.na
172.19.172.70      mtcprdmfsproton01.maris.com.na
172.19.172.109     mtcprdmfsproton02.maris.com.na
172.19.172.18      mtcprdmfsadapt01.maris.com.na
172.19.172.103     mtcprdmfsadapt02.maris.com.na
172.19.172.21      mtcprdmfscore01.maris.com.na
172.19.172.102     mtcprdmfscore02.maris.com.na
172.19.174.107     mtcprdmfsproxy01.maris.com.na
172.19.174.138     mtcprdmfsproxy02.maris.com.na
172.19.173.70      mtcprdmfsdb01.maris.com.na
172.19.175.70      mtcprdmfsdb01.maris.com.na
172.19.173.111     mtcprdmfsdb02.maris.com.na
172.19.175.111     mtcprdmfsdb02.maris.com.na


******************************Setting the Password Policy and Expiry***************

Option-1: Modify the /etc/pam.d/system-auth
#Replace the line that contains pam_pwquality.so

password    requisite     pam_pwquality.so try_first_pass local_users_only retry=3 authtok_type= minlen=8 lcredit=-1 ucredit=-1 dcredit=-1 ocredit=-1 enforce_for_root

Option-2: Modify the /etc/security/pwquality.conf
minlen = 7
ucredit = -1
lcredit = -1
ocredit = -1
enforce_for_root


Guide

-at least 1 lower-case : lcredit=-1

-at least 1 upper-case : ucredit=-1

-at least 1 digit in the password : dcredit=-1

-at least 1 special characters : ocredit=-1

– Minimum length of a password : minlen=8




 /opt/jdk1.8.0_191/bin/keytool -import -trustcacerts -file MCN2023.crt -alias mfsecure2023 -keystore cacerts.jks

/opt/jdk1.8.0_191/bin/keytool --importcert -keystore keystore.jks -alias sbnservices2023 -file SERVICESUAT.crt


Install Java and GF dependancies
#############copy the packages########################
sudo cp -rf /home/itadmin/software/jdk-8u191-linux-x64.tar.gz /opt
sudo cp -rf  /home/itadmin/software/glassfish-4.1.zip /opt/

###############change the software directory #################
cd /opt

################# Extract packages #############################

sudo tar xfv jdk-8u191-linux-x64.tar.gz
sudo unzip glassfish-4.1.zip

#######################Grant Ownership ############################

sudo chown itadmin:support -R jdk1.8.0_191/
sudo chown itadmin:support -R glassfish4/

###############Clean up packages #################################

sudo rm -rf jdk-8u191-linux-x64.tar.gz
sudo rm -rf glassfish-4.1.zip


################################ Install Java packages ###########
sudo alternatives --install /usr/bin/java java /opt/jdk1.8.0_191/bin/java 2
sudo alternatives --config java
sudo alternatives --install /usr/bin/jar jar /opt/jdk1.8.0_191/bin/jar 2rsync -av mobiwand/ itadmin@172.31.6.66:/home/itadmin/mobiwand
sudo alternatives --install /usr/bin/javac javac /opt/jdk1.8.0_191/javac 2
sudo alternatives --set jar /opt/jdk1.8.0_191/bin/jar
sudo alternatives --set javac /opt/jdk1.8.0_191/bin/javac

#############check##########################
java -version
javac -version



Install Java- Tested Steps


sudo alternatives --install /usr/bin/java java /opt/jdk1.8.0_191/bin/java 2
sudo alternatives --config java
sudo alternatives --install /usr/bin/jar jar /opt/jdk1.8.0_191/bin/jar 2
sudo alternatives --install /usr/bin/javac javac /opt/jdk1.8.0_191/bin/javac 2
sudo alternatives --set jar /opt/jdk1.8.0_191/bin/jar
sudo alternatives --set javac /opt/jdk1.8.0_191/bin/javac


https://uptime.mobipay.com.na/login
itadmin
*L0cKM3*786/

https://dashboard.maris.com.na/login
*L0cKM3*786/

Trac
rsync -av mobiwand/ itadmin@172.31.6.66:/home/itadmin/mobiwand




keytool -importcert -alias datapower2024 -file BV17102024.pem -storepass changeit -keystore cacerts.jks
keytool -importcert -alias datapower2024 -file BV17102024.pem -storepass changeit -keystore keystore.jks

keytool -importcert -alias DigicertCA1 -cacerts -file Digicert2024.pem -storepass changeit
keytool -delete -keystore cacerts.jks -alias datapower2023 -storepass changeit
sbnservices2023

keytool -importcert -alias bioid2025 -file bioid2025.crt -storepass changeit -keystore cacerts.jks



moun efs on amazon2023- dnf install -y amazon-efs-utils






