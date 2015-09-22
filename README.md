#Vagrant Setup

##Usage

`vagrant up --provider virtualbox`
`vagrant ssh`

##SharedFoler

The current folder is the shared folder, you can change it in VagrantFile

##VagrantFile

This VagrantFile installs python3.4 and pip

##常用命令

```
$ vagrant init  # 初始化
$ vagrant up  # 启动虚拟机
$ vagrant halt  # 关闭虚拟机
$ vagrant reload  # 重启虚拟机
$ vagrant ssh  # SSH 至虚拟机
$ vagrant status  # 查看虚拟机运行状态
$ vagrant destroy  # 销毁当前虚拟机
```

##Reference

- [使用 Vagrant 打造跨平台开发环境](http://segmentfault.com/a/1190000000264347)
- [vagrant python environment](http://fermi.fantasist.cc/2015/07/31/shi-yong-vagrantda-jian-kua-ping-tai-de-pythonkai-fa-huan-jing/)
- [vagrantfile explained](http://www.sitepoint.com/vagrantfile-explained-setting-provisioning-shell/)

