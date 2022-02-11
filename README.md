## Simple cpanel plugin to allow cpanel users to whitelist IP's in /etc/hosts.allow file & NFT Firewall.

to install:

*note: must have root privileges to install cpanel plugins*


copy `master.zip` to cpanel server.

```
wget https://github.com/crnagora/cpanel_ssh_whitelist/archive/refs/heads/master.zip 
unzip master.zip && cd cpanel_ssh_whitelist-master/ 
chmod +x install.sh
./install.sh
```

To uninstall:

use the uninstall script. 

```
chmod +x uninstall.sh
./uninstall.sh
```

If plugin is already installed and you just want to update to the latest release, use update sript to preserve all User IP's

```
chmod +x update.sh
./update.sh
```

Submit issues for bugs.


