## 前言

在当前的互联网时代，旅游推荐系统已经成为旅游行业的一个重要组成部分。为了满足用户个性化需求，提高用户体验，我们开发了基于协同过滤算法的旅游推荐系统。本系统采用Java语言开发，使用Spring Boot框架，前端技术包括JS、Vue和CSS3，数据库使用MySQL 5.7/8.0，数据库管理工具为phpstudy/Navicat，JDK版本为1.8，Maven版本为3.8.1，前端环境为Node.js 12/14/16。

## 内容介绍

本系统主要包括用户注册、登录、信息管理、个性化推荐、景点查找、景点收藏评论和后台管理等功能模块。用户可以通过注册和登录系统，管理个人信息，查询和收藏感兴趣的景点，并对景点进行评论和评分。系统会根据用户的历史行为和其他用户的行为，计算出用户之间的相似度，并根据相似度给出推荐结果。后台管理模块包括用户管理、景点管理、评论管理等功能，方便管理员进行系统维护和数据分析。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、css3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.js 12\14\16

## 核心代码

```java
@RequestMapping(value = "/recommend", method = RequestMethod.GET)
public ResponseEntity<List<TouristSpot>> recommendSpots(@RequestParam("userId") Integer userId) {
    List<TouristSpot> recommendedSpots = touristSpotService.recommendSpots(userId);
    return new ResponseEntity<>(recommendedSpots, HttpStatus.OK);
}
```

这段代码是系统的推荐接口，通过传入用户ID，系统会返回该用户可能感兴趣的景点列表。

## 免费源码获取

```
8000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/327845/12/17139/151135/68bc6ed2F27394c17/2edba4de286d02d5.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/331222/18/9957/41570/68bc6eb4Fee72013a/0b7e550497704f57.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/349923/13/485/98826/68bc6eb5Ff1bdf588/4b4c2d698c19849e.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/323641/33/17118/40502/68bc6eb6Fece6b21c/38ecd35a98b6f3a1.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/343710/3/470/83047/68bc6eb7F76be49e5/0ab251ac5af8514f.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/341726/10/429/51891/68bc6eb7Fde314415/6cb72f9313b6c321.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/336998/7/7909/39074/68bc6eb9Fe66c0078/369007db918f8eb6.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/327555/4/17005/84281/68bc6eb8F528d75e5/dfcef8a10856a6b3.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/343110/18/463/27912/68bc6ebaF279d5473/94374be4ab4a4b42.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/336533/22/7707/31035/68bc6ebaFc8f03b7e/06ec2f4f3ab598a8.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
