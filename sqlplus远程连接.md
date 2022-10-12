```bash
#先执行这个
$ sqlplus /nolog

# 再执行这个
# SQL> connect 用户名/密码@IP:端口/库名字
SQL> connect user/pasw@192.168.230.128:1521/BASETABLE
```



mac安装sqlplus

```bash
#依次执行下面命令即可 ， 10.14测试过
$brew tap InstantClientTap/instantclient
$brew install instantclient-basic  
$brew install instantclient-sqlplus     
$brew install instantclient-tools
```

