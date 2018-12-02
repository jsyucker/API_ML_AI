﻿# API_ML_AI
 |||
 |--|--|
 |Target release|2018年12月|
 |Epic|记住师兄姐—小程序|
 |Document Status|梁剑舜|
 |Document owner|梁剑舜|
 |Designer|梁剑舜|
 |Developer|梁剑舜|
 |QA|梁剑舜|

### Goals: 
做成小程序，显示照片，放大，人脸追踪，显示人物信息<Br/>
![avatar](https://img-blog.csdn.net/20180610090434684)<Br/> 
### Background and strategic fit: 
- Background:毕业季时，舍友聊起‘学班们’，指着手机的照片说出很多‘学班’的名字，我看着图片一脸懵，只认识自己的‘学班’，其他人可是同一学院的‘学班’，还介绍过自己的。<Br/> 
- strategic fit:做成微信小程序，方便同学们识别不知名的人脸是否是自己的师兄姐。<Br/> 
### Assumptions: 
- 用户可以识别朋友圈、微信群的照片，如识别二维码一样弹出提示.
- 用户想搜索师兄姐其他的毕业照片；想到师兄姐的名字但忘了其样子；想不到名字和样貌，可以浏览，看到照片突然记起来.
- 小程序设置‘每日认识5个’功能，随机刷新5个照片，进行图片--词语匹配，增强记忆。
- 分享刚认识的师兄姐，邀请群里的同学也去认识
- 技术：Detect API Search API 辅助API组（face++）<Br/> 
### 需求 Requirements: 
|Title|User Story|Importance|Notes|
|--|:--:|--:|--|
|搜索|用户需要这个基本功能|重要|暂时没|
|下拉随机刷新|用户可以通过该功能认识师兄姐|重要|暂时没|
|图片--词语匹配|用户可以通过该功能增强自己的记忆|重要|暂时没|
|分享|记忆完后，用户分享自己当天认识到的师兄姐，增强交互|重要|暂时没|
### 使用者交互及设计:
- 低保真
![avatar](https://github.com/jsyucker/API_ML_AI/blob/master/API_Axure.jpg)<Br/>  
- 流程图
![avatar](https://github.com/jsyucker/API_ML_AI/blob/master/API_Flow%20chart.jpg)
### 可解决的问题 Questions: 
-	建立人脸库,可搜索
-	长按弹出识别提示
- 分享<Br/> 
### 不做 Not doing: 列出诗论及记录过的功能，超出范围的功能，下一版再改进的功能，都放在这
-	图片--词语匹配<Br/> 

