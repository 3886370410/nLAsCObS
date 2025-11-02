# 前言

随着互联网技术的不断发展，线上购物已经成为人们日常生活的重要组成部分。药品在线销售系统作为一种便捷、高效的购药方式，得到了广泛的应用。本项目基于SSM（Spring、SpringMVC、MyBatis）框架，采用Java语言开发，旨在为广大用户提供一个安全、可靠的药品在线购买平台。

# 内容介绍

本项目主要包括以下功能模块：用户模块、商品模块、购物车模块、订单模块、支付模块等。用户可以在系统中浏览药品信息、添加药品至购物车、提交订单、在线支付等。系统后台管理方面，提供了药品管理、订单管理、用户管理等功能，方便管理员进行系统维护和数据处理。

# 技术介绍

## 语言：Java

## 使用框架：Spring、SpringMVC、MyBatis

## 前端技术：JS、Vue、CSS3

## 开发工具：IDEA/Eclipse

## 数据库：MySQL 5.7/8.0

## 数据库管理工具：phpstudy/Navicat

## JDK版本：jdk1.8

## Maven：apache-maven 3.8.1-bin

## 前端环境：Node.Js 12\14\16

# 核心代码

以下是一段关于查询药品列表的核心代码：

```java
@RequestMapping("/getDrugList")
public List<Drug> getDrugList() {
    DrugExample example = new DrugExample();
    example.createCriteria().andDrugNameIsNotNull();
    return drugMapper.selectByExample(example);
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/330793/24/4453/103477/68ad53f2Faa4a8f3d/fba051e91cd88425.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/340399/10/1948/30566/68ad53cdF366dad3a/13b2d4840825fd04.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/325097/38/11247/31142/68ad53ceF86d03640/7c46b2caa1a93ef2.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/339145/7/1947/34891/68ad53d5Fc692ac1e/6c84877d4045c546.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/331156/20/4344/69310/68ad53d5F06d8d772/cf21205791fa16b0.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/302080/8/23230/79824/68ad53d6Fa81b3f14/b2a3047c34f6ea07.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/338081/3/1917/87935/68ad53d6Fa5c99a97/4088873247e3b691.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/327850/39/11186/70992/68ad53d7F1fe597df/f1ef1ae66bfcb2f1.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/326368/9/11248/49792/68ad53d7F8ca51b10/e832c826c3616ecc.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/331613/40/4400/69556/68ad53d8Ff38f12eb/387c1ad8d1eb0ee4.jpg)

