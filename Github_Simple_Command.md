# Github的常用命令

***

###目录
> [**Git环境设置**](#setting)
>
> [**Git创建操作**](#create)
> 
> [**Git远程提交**](#push)
> 
> [**Git Pro**](#pro)


***

## <a name="setting"></a>Git环境设置

####Linux

```
sudo apt-get install git-core
#Linux 安装 git命令
```

####Mac


* 使用Terminal，需要下载[Git](http://jaist.dl.sourceforge.net/project/git-osx-installer/git-2.10.1-intel-universal-mavericks.dmg)包.

* 使用[Github Desktop](https://mac-installer.github.com/mac/GitHub%20Desktop%20222.zip).


####Window

* 使用[git bush](https://github.com/git-for-windows/git/releases/download/v2.10.1.windows.1/Git-2.10.1-32-bit.exe)



## <a name="setting"></a>Git创建操作

###Step 1:初始化信息

```
#git config --global user.name "your_name"
#git config --global user.email "your_address@mail.com"

```

###Step 2:生成密钥

```
#ssh-keygen -t rsa -C "your_address@mail.com"
```

###Step 3:复制密钥

####Linux

```
#sudo apt-get install xclip
#xclip -sel clip < ~/.ssh/id_rsa.pub
```

####Mac

```
pbcopy < ~/.ssh/id_rsa.pub
```

####Windows

```
clip < ~/.ssh/id_rsa.pub
```

* 如果以上方法不好用的话，情尝试以下方法,直接复制密钥

```
vi < ~/.ssh/id_rsa.pub
```

###Step 4:关联Terminal与GitHub





