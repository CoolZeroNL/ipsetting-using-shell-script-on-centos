IP Setting on CentOS7 using Shell Script
======================================

This script will be help to setup ip and hostname on CentOS

First create the script :

```
vi ipsetting.sh
```

Download the scrit file or clone it with the following command(Modify the Hostname and IP information,as per your requirement):

```
https://github.com/CoolZeroNL/ipsetting-using-shell-script-on-centos.git
```

Then set the execute permission for your shell script:

```
chmod +x ipsetting.sh
```

Now, execute the shell script as sudo user:

```
sudo ./ipsetting.sh <hostname> <interface> <baseip> <ipaddress> <gateway/dns>
```

