# 安装Git

## 官网下载git安装包安装

## 本地配置用户信息

```shell
1. git config                                     #查看本机是否配置了个人信息
2. git config --global user.name “name”           #定义全局的用户名
3. git config --global user.email “qwer@qq.com”   #定义全局的邮件地址
4. git config --list                              #查看配置信息
```

## 生成SSH Key

```shell
ssh-keygen -t rsa -C “qwer@qq.com”
```

## 添加公钥到Github上

将id_rsa.pub中的内容复制到Github的SSH处
