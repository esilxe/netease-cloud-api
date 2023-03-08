## 网易云音乐升级API

<p align="center">
    <a href="https://github.com/ZainCheung"><img alt="Author" src="https://img.shields.io/badge/author-ZainCheung-blueviolet"/></a>
    <img alt="PHP" src="https://img.shields.io/badge/code-PHP-success"/>
    <img src="https://github-visitor-badge.glitch.me/badge?page_id=ZainCheung.netease-cloud-api"/>
</p>
这是一个通过调用官方接口，能够提供网易云音乐每日听满300首歌曲的基于PHP语言的API项目。

强烈建议配合python全自动脚本项目使用更佳：https://github.com/ZainCheung/netease-cloud

## 灵感来自

[Binaryify/NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi)

## 功能特性

1. 登录
2. 签到
3. 查询用户信息
4. 听完300首歌曲
5. 刷单曲播放次数

## 安装部署

https://zaincheung.gitee.io/netease-cloud/#/api/

## 接口文档

https://zaincheung.gitee.io/netease-cloud/#/document/

## 声明

本项目的所有脚本以及软件仅用于个人学习开发测试，所有`网易云`相关字样版权属于网易公司，勿用于商业及非法用途，如产生法律纠纷与本人无关。

### Get Api Location

 1. Fork this githutb repo —— https://github.com/esilxe/netease-cloud-api
 2. Register a [Glitch](https://glitch.com) account >>> New project
 3. Import from github —— https://github.com/esilxe/netease-cloud-api.git
 4. Settings >>> Edit project detais  >>> Change project's name
 5. Api location —— https://project-name.glitch.me

## Instruction

-  Downlaod repo then unzip it —— https://github.com/ZainCheung/netease-cloud
 - Edit init.config under the folder netease-cloud
 ```
 # Phone or email
 account =
 
 # Country code (China:86)
 countrycode = 
 
 # plaintext or MD5 password (when md5Switch = false)
 password
 
 # Customized api location
 api = https://project-name.glitch.me
 
 # Set TRUE to apply to Multiple accounts with account.json
 peopleSwitch = false
 ```
