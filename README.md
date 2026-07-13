# 前言

欢迎来到基于SSM的餐饮点餐系统设计与实现的项目介绍。随着互联网技术的快速发展，餐饮行业也逐渐实现了线上线下一体化，极大的方便了消费者和商家。本项目正是基于这样的背景，运用主流的开发技术和框架，设计并实现了一套餐饮点餐系统。

# 内容介绍

本系统主要实现了用户点餐、菜品管理、订单管理、营业统计等核心功能。用户可以通过直观的界面进行点餐，商家可以方便的管理菜品和订单，后台管理人员可以查看营业数据，实现智能化的餐饮管理。

# 技术介绍

## 语言：Java

## 使用框架：Spring Springmvc，MyBatis

## 前端技术：JS、Vue、CSS3

## 开发工具：IDEA/Eclipse

## 数据库：MySQL 5.7/8.0

## 数据库管理工具：phpStudy/Navicat

## JDK版本：JDK 1.8

## Maven：Apache-Maven 3.8.1-bin

## 前端环境：Node.js 12\14\16

# 核心代码

以下为系统中的一部分核心代码，展示了如何实现菜品查询的功能。

```java
// 使用MyBatis进行菜品查询
public List<Dish> findDishesByName(String dishName) {
    DishExample example = new DishExample();
    example.createCriteria().andDishNameLike("%" + dishName + "%");
    return dishMapper.selectByExample(example);
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

![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/329679/27/12648/110795/68c4092cFdb1dc4ff/44439decec24362a.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/340736/7/9908/37186/68c4091bFb70a99c6/2ede0b7911e065e0.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/329304/40/12552/38064/68c4091bF1dd4dbb9/6556687707598795.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/339999/14/8559/40086/68c4091cFe854eb6f/7de8e3f1b8f45beb.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/344748/10/2639/42449/68c4091cF002b4ecc/3275f51413877223.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/336557/3/9970/48449/68c4091dF69dac2f2/8cbe55ea10223aae.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/344737/30/2666/55139/68c4091dF658f59fd/cb063a9c3fe2b2d4.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/324807/25/19298/24275/68c4091eFf20f3831/fa6843db5fffc0d7.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/336132/27/10021/42728/68c4091eFef26e72c/0cfc0ed1b45b4c77.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/338461/13/10063/71763/68c4091eF6a2a23e7/301c0d844dc090c0.jpg)
