# virtualbox (Centos 7)

```
yum install qt5-qttools-libs-help
yum install qt5-qtx11extras
yum install vulkan
yum install gcc
yum install kernel-devel

rpm -i Virtualbox***

```


```bash
yum search virtualbox
sudo yum install kernel-devel kernel-devel-$(uname -r) kernel-headers kernel-headers-$(uname -r) make patch gcc
sudo wget https://download.virtualbox.org/virtualbox/rpm/el/virtualbox.repo -P /etc/yum.repos.d
yum search virtualbox
yum update
sudo yum search virtualbox
sudo yum install VirtualBox-6.1
systemctl status vbox*
sudo yum install VirtualBox-6.1
systemctl status vboxdrv
sudo systemctl enable vboxdrvA
systemctl status vbox*
```
