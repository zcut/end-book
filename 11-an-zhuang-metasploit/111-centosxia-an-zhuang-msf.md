##### 0x00 导读

以下将描述如何在linux平台安装metasploit（以下简称“msf”）。此次安装的是开源metasploit框架，通俗的说就是免费版。

系统：centos7，已关闭防火墙、selinux

##### 0x01 下载msf

1. 访问[msf官网](https://www.metasploit.com/)，点击下载。

![](/Users/s/Documents/9-gitbook/Import/end-book/assets/BCDFF35D-05F3-4E33-A0DD-86563F33CD48.png)

2.跳转到github，选择对应的系统，复制对应脚本。

![99b6fe41e63030863e846b174ee9c6d7.png](evernotecid://49BEAE14-0D13-4E66-AE98-0F19E6E6BF15/appyinxiangcom/21771266/ENResource/p141)

1. 在系统命令行粘贴脚本，并回车执行，会自动开始安装msf。 

![9addd515eac6cfc3966cb45db1697ffd.png](evernotecid://49BEAE14-0D13-4E66-AE98-0F19E6E6BF15/appyinxiangcom/21771266/ENResource/p143)

等装完就可以了

![c43066bd9d71a944ed1ff3d6a823e97c.png](evernotecid://49BEAE14-0D13-4E66-AE98-0F19E6E6BF15/appyinxiangcom/21771266/ENResource/p145)

1. centos下运行msf，不能直接使用root账号。先添加一个普通账号 mmsf/mmsf 

```
useradd mmsf 

passwd mmsf
```

1. 切换到mmsf下运行，msfconsole 

5.1 初次运行会让你添加一个数据库，选择输入yes，然后输入数据库的账号和密码，这里同样设置为mmsf/mmsf

![1fbffbdb8d22ee9cf9dfb4486c0473b2.png](evernotecid://49BEAE14-0D13-4E66-AE98-0F19E6E6BF15/appyinxiangcom/21771266/ENResource/p148)

5.2 等数据库设置完毕后，msf就能正常启动了

![a8f76c988057b853e78dd4d5789aed4a.png](evernotecid://49BEAE14-0D13-4E66-AE98-0F19E6E6BF15/appyinxiangcom/21771266/ENResource/p150)

