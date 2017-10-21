## 重要声明
此次的app启动广告确实费了很大精力,请尊重作者辛苦制作,不接受用来做商业盈利!
同时请您在转载修改时标注作者并说明出处并附带网址，如发现其他规则有此次更新内容，没有标明出处的，规则今后将不做发布!


  
### 使用要求

 - Surge 版本高于2.5.0;
 - Surge 开启MITM;
> 因现在大部分APP升级后协议基本为HTTPS，所以开启了MITM，并不会对各位的手机安全造成影响，大可放心使用，如果还保持有疑虑，请自行生成并安装证书即可！

### 规则介绍

一直没有写过介绍，那也正式介绍下逗bi极客的规则优点，其实用上了应该就很了解功能：

```sh
* 爱奇艺过滤首家发布；
* APP启动广告首家发布；
* 更快速智能的分流；
* 两种规则适配更灵活；
* 屏蔽统计站点获取数据；
* 规避商家、站点、软件隐私获取；
* 屏蔽运营商web页面浏览流量提醒；
* 自定义DNS方案抗干扰；
* 黑白名单更快速识别；
* 各大网盘支持;
* 其他的不多BB,好不好用自己试试;
```

### 规则区分

`iOS.conf`

[全能规则]
包含黑白名单，适配所有机型;

`iOS_S.conf`

[精简规则]
包含白名单,节省内存占用适配越狱机型；

`iOS_S_China.conf`

[回国规则]
针对海外朋友适配的回国规则，国内朋友请不要使用；


### 使用教程

###### 1.将下方链接复制后贴入Surge连接中即可

精简规则
```sh
https://raw.githubusercontent.com/tudi1909/Surge_rules/master/iOS_S.conf
```


全能规则
```sh
https://raw.githubusercontent.com/tudi1909/Surge_rules/master/iOS.conf
```

回国规则
```sh
https://raw.githubusercontent.com/tudi1909/Surge_rules/master/iOS_S_China.conf
```

###### 2.配置线路

如果是日常的HTTP,HTTPS,SS5的线路自己按照选项填写即可，下方针对SS来进行配置说明

线路名称 = custom,服务器IP或者域名,对应端口,对应密码类型,密码,Surge module地址(可以使用我提供的模块！)
```sh
🇰🇷 KR-SERVER = custom,yeshigeek.com,12345,rc4-md5,password,https://cdn.qingjie.me:443/surge/ss.module
```

###### 3.开启！

###### 怎样开通MITM?
下载小视频,即可学会
```sh
https://raw.githubusercontent.com/tudi1909/Surge_rules/master/IMG_0094.MP4
```

## 捐赠
  感谢各位使用，由于后期的抓包和去广告更耗时耗力，欢迎各位多多请喝茶！
![QR Code](https://raw.githubusercontent.com/tudi1909/Surge_rules/master/q.png)
