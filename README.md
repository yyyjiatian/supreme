# supremeBot，nikeBot，抢鞋bot，palaceBot 
supreme nike 技术交流QQ:80258153
## 背景：

​           随着潮鞋、潮牌的风靡、本程序员准备入手一套supreme，palace、nike；耐于总是抢不到，无奈之下耗时N久，准备手写一套抢购supreme nike palace的工具；从此开始了漫漫长路....；

## **功能支持：**

| 平台        | 是否支持基础抢购 | 是否支持跳过排队 |
| ----------- | ---------------- | ---------------- |
| supreme日本 | 支持             | 支持             |
| Nike        |                  |                  |
| supreme美国 | 支持             | 支持             |
| palace      | 支持             | 支持             |


### **软件功能支持：**

| 功能                                                         | 是否支持 |
| ------------------------------------------------------------ | -------- |
| 登录                                                         | 支持     |
| 添加删除抢购任务                                             | 支持     |
| 添加、修改抢购人信息                                         | 支持     |
| 自动打码（这里是核心技术、因为传统的打码平台，完全能被对方给识别出来） | 支持     |
| 抢购状态                                                     | 支持     |
| 打包成exe\dmp                                                | 支持     |

ps:目前这个基本上已经达到商业的级别；



[**演示视频](https://www.bilibili.com/video/BV1j4411K7vj?from=search&amp%3Bseid=9871111040487730515)：**

[点完观看抢购效果](https://www.bilibili.com/video/BV1j4411K7vj?from=search&amp%3Bseid=9871111040487730515)



### **主页面**：

![image-20200603134353313](https://s1.ax1x.com/2020/06/04/tw2CwT.png)



### 抢购成功邮件：

![image-20200603135616982](https://s1.ax1x.com/2020/06/04/twgXWj.png)



## **支持平台：**window & mac



### **抢购原理：**

​              分析抢购流程，模拟http协议发包技术，模拟抢购流程。通过特殊连接跳过排队流程，实施抢购，平均3秒之内可以抢到；

### **日常采坑：**

- **遇到日常可以抢购，但是热品的时候抢不到？这个我也是被卡住了3个月才突破关键技术**；
- 日常都抢不到，尝试过浏览器模式，抓包模式等。最终发现浏览器方式太不靠谱了。
- 模拟数据包，平时都抢不到。那你还差得远。

### **核心技术组件：**

- javaFX
- httpclient
- springboot
- mysql
- 代理技术
- 次要技术：正则、抓包、UI、ps ,js 等

### 本地开发运行部署

部署：

- 开启mysql、配置好程序连接信息，程序将自动创建表；

- 客户端配置服务端接口ip地址；即可运行

- 目前已经配置好打包流程，可直接运行maven命令 打包成 exe或 mac系统的 dmg 可运行文件；

- 这里是示例打包后的可运行程序，链接: https://pan.baidu.com/s/1_J6WUYeltjx3zOG-atayRw 提取码: v8ra

- （因为没有部署数据库，所以您下载的可运行程序无法登陆，部署比较麻烦，烦请您如果想运行还是要源码）

  

## [获取详细文档](http://www.hxdwe.cn:8001/product/supreme)



技术交流QQ:80258153

未经授权不得商业、源码仅供交流学习使用；

源码本身已经包含了核心代码，交流学习已经够用了；
-----------------------------------------------
下面晒一些nike bot 的东西；
![Bcmw0U.png](https://s1.ax1x.com/2020/11/04/Bcmw0U.png)
![BcmUXV.png](https://s1.ax1x.com/2020/11/04/BcmUXV.png)
![Bcmtlq.png](https://s1.ax1x.com/2020/11/04/Bcmtlq.png)
![BcmN60.png](https://s1.ax1x.com/2020/11/04/BcmN60.png)
![BcmdmT.png](https://s1.ax1x.com/2020/11/04/BcmdmT.png)
![Bcm07F.png](https://s1.ax1x.com/2020/11/04/Bcm07F.png)

QQ:80258153



