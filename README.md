# develop_environment
> 电脑的快速配置文件，兼容 windows, linux, mac ox

# before use
1. you should install `Git` (linux & mac os already exist)
[Download Git with windows](https://git-scm.com/downloads)
2. you have a skill of `git command` [Such as follow]
```bash
$ ssh-keygen -t rsa -b 4096 -C "youremail@hotmail.com"
# set github ssh-key as home
$ id_rsa_home 
# set gitlab ssh-key as default
$ id_rsa 
```
1. to use mutiple account of Git repo, you should set `config` file in `~/.ssh`
```bash
$ mkdir ~/.ssh/
$ vim config
```
write this in the `config` file
```
#oschina  
Host git.coding.net
    HostName git.coding.net
    IdentityFile ~/.ssh/id_rsa_coding
    PreferredAuthentications publickey
    User 564265135@qq.com

#github
Host github.com
    HostName github.com
    IdentityFile ~/.ssh/id_rsa_home
    PreferredAuthentications publickey
    User zhangchao564265135@hotmail.com
#gitlab
Host gitlab.com
    HostName gitlab.com
    IdentityFile ~/.ssh/id_rsa
    PreferredAuthentications publickey
    User zhangchao564265135@hotmail.com
```

# context
1. `vscode` config file
1. office 365 (only windows & mac os)
1. chrome stable & chrome canary
1. node.js
1. 7z
1. office active tools
1. WinRAR
1. yarn-1.3.2
1. ThunderVIP

# record 
1. 2018年2月6日15点31分: 添加 `vscode` 配置文件
