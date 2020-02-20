# linux常用命令总结

- 执行需要多次交互的脚本
```
$ echo -e "Y\nYINSHENG.STUDIO\n" | apt-get install krb5-kdc krb5-admin-server
```
When users attempt to use Kerberos and specify a principal or user
name without specifying what administrative Kerberos realm that
principal belongs to, the system appends the default realm.  The
default realm may also be used as the realm of a Kerberos service
running on the local machine.  Often, the default realm is the
uppercase version of the local DNS domain.

Default Kerberos version 5 realm: `YINSHENG.STUDIO`

Enter the hostnames of Kerberos servers in the YINSHENG.STUDIO
Kerberos realm separated by spaces.

Kerberos servers for your realm: `adminserver`

Enter the hostname of the administrative (password changing) server
for the YINSHENG.STUDIO Kerberos realm.

Administrative server for your Kerberos realm: `adminserver2`

