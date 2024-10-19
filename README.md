# ansible-kubeadm
![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

Aims to manage kubeadm based cluster via ansible

What ansible-kubeadm can do:
  - Install kubeadm on a variety of linux distribution
  - lock kubeadm package to avoid upgrade
  - init a cluster and join node in a idempotent manner
  - upgrade a cluster in an indempotent maner (just add +1 to minor version config and your good to go !)

What ansible-kubeadm expect to be done and will not do:
  - Upgrading distro
  - Upgrade the kernel
  - install ntp
  - installing docker (or whatever CRI)
  - disable swap
  - remove unattented-upgrade
  - configure CNI

## Quickstart

see [Quickstart](docs/quickstart.md) 

## Configuration

If you want a customized (ansible-)kubeadm experience there is a number of variables you can use: 

[Variables reference](docs/variables.md)

## Tips and Tricks

[Tips&Tricks](tips_tricks.md)

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟