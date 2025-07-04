## 项目概述

**项目名称**：计算机学院竞赛推荐微信小程序


**目标用户**：计算机学院在校学生、对竞赛感兴趣的学弟学妹以及相关教师

**项目背景**：
- 学院竞赛种类繁多，学生对各类竞赛信息了解不全面  
- 学生选赛、准备赛时缺乏集中化信息平台  
- 传统公众号推送效率低、互动形式单一  

**项目目标**：
- 为计算机学院学生提供一站式竞赛信息浏览、筛选与推荐服务  
- 根据学生兴趣与能力智能推荐合适竞赛  
- 提供赛程管理、备赛资源与交流社区功能  

---

## 主要功能需求
###底部有两个按钮
- **首页** 展示计算机竞赛推荐
- **我的**管理自己的东西
### 1. 用户注册与登录
- **功能描述**：支持微信扫码/微信授权登录，获取基本用户信息（学号、姓名、专业、年级）    
- **成功标准**：新用户完成首次登录后进入个人中心，老用户可直接进入首页  
### 2. 竞赛信息管理
- **功能描述**：后台管理员可录入、编辑、删除竞赛信息，包括竞赛名称、类型（算法、应用、设计等）、主办方、报名时间、赛程时间、报名链接、赛题回顾、获奖展示等  
- **展示要求**：前端以卡片或列表形式分页展示；支持关键字搜索、类型筛选、时间排序  
### 3. 智能推荐引擎
- **功能描述**：根据用户注册时的学科背景、兴趣标签及历史浏览/报名行为，采用协同过滤或内容推荐算法，推荐最匹配的竞赛  
- **技术要求**：后台定时计算推荐列表，前端首页展示“为你推荐”模块，支持刷新与“看更多”  
### 4. 赛程管理
- **功能描述**：用户可将感兴趣的竞赛加入个人赛程，微信自定义消息推送重要节点（如报名截止、初赛/复赛时间）  
- **业务规则**：可在“我的赛程”中查看/删除；推送方式通过微信订阅消息接口  

### 5. 备赛资源
- **功能描述**：提供竞赛历届赛题、解析视频、讨论帖链接等备赛资料；支持按竞赛分类、年份、难度筛选下载  

### 6. 互动社区
- **功能描述**：用户可在小程序内发布讨论帖，分享备赛攻略、经验答疑；帖子支持点赞、评论、收藏  

### 7. 消息中心
- **功能描述**：集中展示系统消息、推荐通知、社区互动提醒；用户可标记已读与删除  

### 6. 页面和使用感觉要求
- **界面样子**：
 *必须使用**TDesign Weixin**这个现成的界面包来做，让小程序的按钮，列表，输入框等看起来风格统一，好看，（参考：https://tdesign.tencent.com/miniprogram/getting-started）
