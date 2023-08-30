# WiFi-Attendance
基于wifi Wi-Fi定位的考勤系统，通过Wi-Fi信息完成签到、考勤、公告发布、请假等功能，主要有手机签到端和服务器端

[![](https://img.shields.io/badge/Video-%E6%BC%94%E7%A4%BA-yellow)](https://www.bilibili.com/video/BV1po4y127Cc/)
[![](https://img.shields.io/badge/author-GXW-green)]()

## 详细代码及论文请联系Q:2262604603


## 概要
考勤在企业管理的过程中是一项重要的工作，目前常见的考勤方式是采用指纹打卡和射频卡考勤，这些考勤方式存在一定的不足，那就是上下班高峰期会面临耗时长、排队等现象，尤其是目前处于疫情期间，传统的通过考勤机的方式可能造成病毒的传播，不利于疫情的控制。本项目是通过Wi-Fi指纹的方式来对员工进行考勤，主要分为手机签到端和服务器端，在使用手机签到端时，系统会自动收集当前环境下的Wi-Fi数据信息进行签到，如果在当前区域则签到成功，如果不在，则不能进行签到；在使用服务器端时，管理员可以方便的管理用户和查询用户的签到信息，除了上述的功能，本系统还拥有公告管理、请假管理、通讯录等功能。

本系统主要的特点是：简单易用、方便可靠
## 主要功能
![系统功能图](https://img-blog.csdnimg.cn/20210514211910754.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2J1Z19tb3Zl,size_16,color_FFFFFF,t_70#pic_center)
## 技术栈

 - Java
 - Android
 - Springboot
 - Vue
 - mysql
## 系统实现
### 手机签到端
主要功能有登陆和签到

<img src="https://img-blog.csdnimg.cn/20210514212103448.png" width="40%;" />  <img src="https://img-blog.csdnimg.cn/20210514212258130.png" width="33%;" />

### 服务器端
#### 登陆：

<figure class="half">
    <img src="https://img-blog.csdnimg.cn/2021051422260418.png" width="80%">
</figure>

#### 首页：
<figure class="half">
    <img src="https://img-blog.csdnimg.cn/20210514214231860.png" width="80%">
</figure>

#### 人员管理：
<figure class="half">
    <img src="https://img-blog.csdnimg.cn/20210514214110771.png" width="80%">
</figure>

#### 公告功能：
<figure class="half">
    <img src="https://img-blog.csdnimg.cn/2021051421433451.png" width="80%">
</figure>

#### Wi-Fi信息设定：
<figure class="half">
    <img src="https://img-blog.csdnimg.cn/20210514214630923.png" width="80%">
</figure>

#### 考勤功能：
<figure class="half">
    <img src="https://img-blog.csdnimg.cn/2021051421442562.png" width="80%">
</figure>

#### 请假功能：
<figure class="half">
    <img src="https://img-blog.csdnimg.cn/20210514214504653.png" width="80%">
</figure>

#### 通讯录功能：
<figure class="half">
    <img src="https://img-blog.csdnimg.cn/20210514214543626.png" width="80%">
</figure>
