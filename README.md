# MyRules

 - 自己用的一些Surge&Clash配置文件。**包含的服务器均无效，请自行替换服务器。**

 - 包括内网穿透规则,具体方式见 https://github.com/fatedier/frp

   2020年更新起不再更新Surfboard配置文件，因本人已转用 [Clash for Android](https://github.com/Kr328/ClashForAndroid)

 - Surfboard 配置文件支持到 [Ver. 0.8.5.0729 (26)]<br>

 - 具体用法可见如下规则。 

------

## 出国规则<br>
 - Surfboard规则，适用于三星国行手机<br>
    https://github.com/sumsethan/MyRules/raw/master/Rules/Surfboard.conf    


  - Surge规则,基于Scomper http://t.cn/RQo6viU ,添加一些自用规则及自己收集总结的netflix规则。<br>
    https://github.com/sumsethan/MyRules/raw/master/Rules/CrossWall.conf

  - SurgeRecommand规则<br>
    https://github.com/sumsethan/MyRules/raw/master/Rules/SurgeRecommand.conf


  - macServer规则，适用Surge网关<br>
    https://github.com/sumsethan/MyRules/raw/master/Rules/macServer.conf

## 回国规则<br>
 - for Surge
  - 方便妹子翻回国内看视频听音乐用，包括YouTube及Netflix区域选择及国内节点自动测速链接，同时短时间肉身回国时可以选择Location切换默认线路<br>
    https://github.com/sumsethan/MyRules/raw/master/Rules/BacktoChina.conf

------
2020.2.1更新

- 更新Clash规则，适用于 Clash Linux 版及 [Clash for Android](https://github.com/Kr328/ClashForAndroid)

2018.7.29更新

 - 更新Surfboard规则，添加去广告开关、直连线路选择等「适用于Surfboard 0.8.5.0729 (26)及之后版本」。

2018.5.20更新

 - 添加macServer规则。

2018.5.6更新
 - 添加Surfboard规则。
 - 更新其他规则，去除URL Rewrite。

2018.1.18更新
 - 添加SurgeRecommand规则，大幅精简。
 - 增加内网穿透规则，需在内网建一SS服务器后使用内网穿透服务暴露到外网。
 - 增加前置代理规则，方便使用其他代理软件。

2017.12.7
- 初始版本，添加出国/回国规则。
