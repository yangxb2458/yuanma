# 简单通用的后台管理系统

## 简介<br/> 
Base Admin一套简单通用的后台管理系统<br/> 
这套Base Admin是一套简单通用的后台管理系统，主要功能有：权限管理、菜单管理、用户管理，系统设置、实时日志，实时监控，API加密，以及登录用户修改密码、配置个性菜单等<br/> 

## 技术栈<br/> 
前端：layui<br/> 
java后端：SpringBoot + Thymeleaf + WebSocket + Spring Security + SpringData-Jpa + MySql<br/> 

## 运行效果图<br/> 
![](https://img2020.cnblogs.com/blog/1353055/202007/1353055-20200717112315040-830760246.png) 

## 常见问题<br/>
0、maven下载jar包长时间无反应？
```text
原因：网络原因连不上maven仓库或其他未知原因导致IDE间接性抽风，导致无法下载联网下载jar包

解决：网络原因自行解决，如果网络没问题就不要一直傻傻的等了，重启IDE，让它重新联网下载
```
1、IDE编译报错，识别不到实体类的set、get方法？
```text
原因：项目使用lombok开发，lombok会在生成class字节码文件帮我们生成set、get等方法，java文件没有set、get等方法，IDE索引不到set、get方法所以编译报错

解决：IDE安装lombok插件即可能识别到对应set、get方法，重启生效
``` 
2、数据库文件在哪？
```text
原因：没有好好看文档，建议先好好看下博客介绍，博客文末“代码开源”处已经早有说明

解决：base_admin.sql文件在resources/static/sql下面
```
3、如何启动程序？
```text
原因：对springboot项目不熟，建议先去了解一下springboot，感兴趣的可以去看我的springBoot开源项目

解决：等待IDE识别成springboot项目后，在BaseAdminApplication.java中运行main函数启动程序
```

## 前往公众号查看详情<br/> 
具体介绍请看我的公众号[《开源一套简单通用的后台管理系统》](https://mp.weixin.qq.com/s/Hnc0F77y10NSISwyIkGksQ)<br/> 

## QQ群<br/>
有事请加群，有问题进群大家一起交流！
QQ群名：IT大佬群
QQ群号：733902044

## 欢迎关注全栈开发私房菜，每天进步一点点
![二维码](https://mmbiz.qpic.cn/mmbiz_jpg/6Nme2xEYxU6TP2Dicn0XEibZgq4jBLYqm3Sb5qP9l4SicWry0LCibch9gkwZ8BMwzwEsgDE4HUicHve6QHAEKQNc5bg/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)
### 扫描二维码关注【全栈开发私房菜】

## 捐献<br/>
请注意，作者五行缺钱，如果喜欢这个项目，请随意打赏！

支付宝<br/>
![](https://mmbiz.qlogo.cn/mmbiz_jpg/6Nme2xEYxU5vpdLchtBYM2UjPdzvjySQZq0sJoVvmbTsjeP6LXLIvEqJz4sOvgPSQszjjJCuMNbg0ZrcSMCyCQ/0?wx_fmt=jpeg) 

微信<br/>
![](https://mmbiz.qlogo.cn/mmbiz_jpg/6Nme2xEYxU5vpdLchtBYM2UjPdzvjySQrzEeGUx4naoTpBHaOW6EicC1NUTIIv1ovJWPgziaXoFiawM4XCRia1CDPA/0?wx_fmt=jpeg) 

