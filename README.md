# SeaBot

[![GitHub issues](https://img.shields.io/github/issues/B1ue1nWh1te/SeaBot.svg?style=flat-square)](https://github.com/B1ue1nWh1te/SeaBot/issues)
[![GitHub forks](https://img.shields.io/github/forks/B1ue1nWh1te/SeaBot.svg?style=flat-square)](https://github.com/B1ue1nWh1te/SeaBot/network)
[![GitHub stars](https://img.shields.io/github/stars/B1ue1nWh1te/SeaBot.svg?style=flat-square)](https://github.com/B1ue1nWh1te/SeaBot/stargazers)
[![GitHub license](https://img.shields.io/github/license/B1ue1nWh1te/SeaBot.svg?style=flat-square)](https://github.com/B1ue1nWh1te/SeaBot/blob/master/LICENSE)

SeaBot是一个前后端分离且支持多平台推送的消息机器人服务。你可以用它实现很多有趣的小功能。

项目整体使用Python语言编写,后端(各功能的API接口)使用Flask框架搭建,基于requests的json数据解析及正则解析实现数据的提取;前端(消息收发控件)基于各平台的消息推送接口实现对消息的接收和发送,通过消息回调服务,实现了按照用户指令访问后端API获得已预处理好的json格式数据,并按照预设的格式推送回复用户。通过gevent实现接口高并发,信息的获取、处理与分发速度显著提升。

# 目前支持的平台

- 企业微信
- 微信(借助企业微信的应用插件,实现消息转发,无需下载企业微信APP即可在微信接收对应消息)

# 目前支持的功能

- Bilibili各分区排行榜查询(图文卡片消息 不支持分区:番剧/国产动画/纪录片/电影/电视剧)
- 网易云音乐排行榜查询(图文卡片消息 支持分区:热歌/原创/飙升/新歌)
- 天气情况查询(文本消息)
- 知乎热榜查询(图文卡片消息)
- 微博热搜/要闻榜查询(图文卡片消息)
- 同花顺快讯获取(文本卡片消息)
- 疫情数据查询(文本消息、图文卡片消息)
- 深海之眼最新文章查询(图文卡片消息)

# 使用教程
图文教程: [SeaBot 消息机器人使用教程](https://www.seaeye.cn/archives/308.html)

# 开源许可

The GNU General Public License v3.0

Copyright 2021 B1ue1nWh1te
