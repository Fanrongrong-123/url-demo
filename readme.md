## 浅析URL

## 1、URL

    URL=协议+域名/IP+端口号+路径+查询字符串+锚点
    协议：http协议默认端口（80）
         https默认端口（443）
    域名：是对IP的别称
    IP：定位一台设备
    端口号：用来定位一台设备的服务
    路径：指定机器上的页面
    查询字符串：指定机器上的内容
    锚点：指定页面内容的哪一块

## 2、DNS作用

    DNS(Domain Name System)：用来对应域名和IP

## 3、nslookup命令

    作用：通过DNS查询域名对应的IP
    用法：nslookup+域名 例：nslookup bidu.com

## 4、ping命令

    作用：查看网络是否通畅，查看IP地址

## 5、域名

    作用：域名就是对应IP的别称
    com顶级域名
    baidu.com二级域名（俗称一级域名）
    www.baidu.com三级域名（俗称二级域名）
    一个域名可对应多个IP（负载均衡）
    一个IP对应多个域名（共享主机）
