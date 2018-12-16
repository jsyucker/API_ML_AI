# API_ML_AI
 |||
 |--|--|
 |Target release|2018年12月|
 |Epic|记住师兄姐—小程序|
 |Document Status|梁剑舜|
 |Document owner|梁剑舜|
 |Designer|梁剑舜|
 |Developer|梁剑舜|
 |QA|梁剑舜|

## 目的:做一个能随时认识师兄姐的小程序
## 背景: 
毕业季时，舍友聊起‘学班们’，指着手机的照片说出很多‘学班’的名字，我看着图片一脸懵，只认识自己的‘学班’，其他人可是同一学院的‘学班’，还介绍过自己的，我没记忆<Br/>
## 目标:
- 前期：
1. 建立人脸库,有分类搜索、相似人脸搜索这俩基本功能
2. 分享刚认识的师兄姐的图片，长按可以弹出‘识别师兄姐’的提示
---
- 后期
1. 增加一些小游戏，例如图片--信息匹配、图片-图片匹配等，完成游戏后分享出去，邀请别人也来玩，加强互动
## 核心价值: 
在校学生/已毕业校友想要了解自己专业、社团或班级等不同团体的师兄姐/同级同学，提供基本的毕业生资料（姓名、学号、专业、年级）,分享这些照片，制造话题，成为加强互动的小工具
## 加值宣言:
运用了人脸识别的人脸搜索API，找出与照片相同或相似的人脸，用户可以多认识几个人；也运用了辅助API组，帮助建立人脸库
## 用户
在校学生 毕业校友
## 用户需求
- 毕业季，拍了好多照片，但有很多师兄姐是不认识的
- 群里闲聊，突然有人发出照片，他知道这是师兄姐，但不知道名字
- 就想找个话题去闲聊
## 人工智能概率性与用户痛点: 
- 相似人脸搜索这一功能，用户多用来闲聊，识别错了关系不大
## 需求 Requirements: 
|Title|User Story|Importance|
|--|:--:|--:|
|分类搜索|基本功能|重要|
|分享|用户认识完后需要互动|重要|
|人脸搜索|用户可以用这个功能多认识几位师兄姐|次重要|
## 使用者交互及设计:
- 登录获取权限(低保真)<Br/>
![avatar](https://github.com/jsyucker/API_ML_AI/blob/master/authorization.jpg)
- 分三大功能：<Br/>
1. 我的(低保真)<Br/>
![avatar](https://github.com/jsyucker/API_ML_AI/blob/master/me.jpg)
2. 每日新认识(低保真)<Br/>
-  下拉刷新<Br/>
![avatar](https://github.com/jsyucker/API_ML_AI/blob/master/new_recongnition.jpg)
3. 相似搜寻，可支持上传图片和长按图片弹出识别提示(低保真)<Br/>
- 上传图片(低保真)<Br/>
![avatar](https://github.com/jsyucker/API_ML_AI/blob/master/upload_photo.jpg)
- 长按图片弹出提示(低保真)<Br/>
![avatar](https://github.com/jsyucker/API_ML_AI/blob/master/photo_longpress.jpg)

## API运用：
1.face++:人脸识别-search API 与 百度:人脸识别-search API 结果对比
- 百度search API <Br/>
![avatar](https://github.com/jsyucker/API_ML_AI/blob/master/baidu_searchapi_example.jpg)
- face++ search API <Br/>
![avatar](https://github.com/jsyucker/API_ML_AI/blob/master/face%2B%2Bsearch_api_example.jpg)
- 两者人脸搜索功能结果显示基本一致，较大的区别为：百度人脸搜索'相似度'用百分比来表示；face++的人脸搜索'相似度'用‘高、一般、低’来表示
2. face++：辅助人脸API
- 帮助建立人脸库
```
代码示例
```
3. face++：Search API
- 一对多人脸对比
```
代码示例
```
## 可解决的问题 Questions: 
-	建立人脸库,基本搜索、相似人脸搜索
-	长按弹出识别提示
- 分享

## 不做 Not doing: 
-	互动小游戏

## 清单
- 交互原型：https://github.com/jsyucker/API_ML_AI/tree/master/API_yuanxing
