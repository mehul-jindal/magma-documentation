---
layout: page
---
## AGW 5G DOC

Before starting the deployment activity, lets update our box using the bellow commands


sudo apt-get update && sudo apt-get upgrade -y


```
Su
Git clone https://github.com/magma/magma/
wget https://raw.githubusercontent.com/magma/magma/v1.8/lte/gateway/deploy/agw_install_ubuntu.sh
bash agw_install_ubuntu.sh
```

The machine will reboot but the installation is not finished yet; the script is still running in the background. You can follow the output using the following command.

```
journalctl -fu agw_installation
```


When you see "AGW installation is done.", it means that your installation is complete. You can make sure magma is running by executing.

```
service 'magma@*' status
```


## Post-install check
Make sure you have the control_proxy.yml file in directory ```/var/opt/magma/configs/``` before running the post-install script


```
bash /root/agw_post_install_ubuntu.sh
```