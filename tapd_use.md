---
title: "tapd使用手册"
date: "2020-07-20"
author: "韩倩云"
output: 
  html_document: 
    fig_caption: yes #fig_caption 控制是否使用标题呈现数字
    highlight: haddock #highlight指定语法高亮样式
    keep_md: yes #在渲染后保留Markdown文件的副本
    number_sections: yes #number_sections选项将标题编号添加到标题
    theme: united #theme指定用于页面的Bootstrap主题（主题来自Bootswatch主题库）
    toc: yes #toc选项添加目录（TOC）
    toc_depth: 6 #用该选项指定它应用的标题深度toc_depth，默认为3（意味着所有级别1,2和3标头将包含在目录中）
    toc_float: #指定将toc_float目录浮动到主文档内容左侧的选项，即使滚动文档，浮动目录也始终可见
      collapsed: false #collapsed（默认为TRUE）控制TOC是否仅显示顶级（例如H2）标题。如果最初崩溃，TOC会在必要时自动扩展内联
      smooth_scroll: false #smooth_scroll（默认为TRUE）控制在通过鼠标单击导航到TOC项目时是否为页面滚动设置动画
---

# 注册登录

## 注册
登录完美邮箱, 找到「tapd邀请」的邮件, 点击链接进入注册页面.

- step1: 填写完美个人邮箱
- step2: 填写本人姓名
- step3: 设置登录tapd密码
- step4: 填写个人手机号
- step5: 填写验证码
- step6: 点击「阅读并同意」
- step7: 点击「注册」

## 登录
https://www.tapd.cn/company/participant_projects?from=left_tree2

# 使用

## 项目分类
- 大数据内部协作: 用于开发、分析内部协作
- 大数据开发组: 用于开发组同学记录需求
- 大数据分析组: 用于分析组同学记录需求

## 需求创建、管理
- 创建<br>
点左上角「创建需求」进入创建页面
- 标题<br>
输入需求标题, 按照“【app名】需求名”创建, 比如【拼音app】(识字)体验课包效果对比分析
- 正文<br>
填写正文内容(可用md格式编辑), 同时更新右上角「需求状态」
  - 记录业务方发起的原始需求, 对应状态<font color='red'>「新」</font>
  - 需求核心目的、分析思路等, 对应状态<font color='red'>「业务确认」</font>
  - 分析需要的数据源, 取数逻辑, 对应状态<font color='red'>「数据源确认」</font>
  - 代码实现过程记录, 可传gitlab, 贴代码地址, 对应状态<font color='red'>「实现中」</font>
  - 填写需求结论, 并交付给相关人员, 对应状态<font color='red'>「交付」</font>
  - 最后填写该项目贡献的价值, 重新做一遍应该做什么, 对应状态<font color='red'>「价值回顾和复盘」</font>
  - 如果到某一步决定拍回需求, 直接把对应状态改成<font color='red'>「已拒绝」</font>
  - 如果到某一步决定暂时不做需求, 直接把对应状态改成<font color='red'>「挂起」</font>
- 基本信息(右侧)<br>
  - 状态(略, 同上)
  - 父需求, 如果没有就不用管
  - 需求分类, 如果没有就不用管
  - 迭代
    - 2020Q3: 需求方发起的需求记录在这里
    - 自发项目: 自发探索性项目
  - 优先级
  - 处理人, 写本人
  - 预计开始
  - 预计结束
- 附件<br>
如有结论报告或者需求相关文档可以上传到这里
- 评论<br>
如需要周知其他人, 可在评论区艾特对方

## 添加项目成员
进入到tapd首页, 点击右上角“+”、「添加项目成员」. 

## 工作状态流修改
不同项目的状态流是独立的, 可手动自定义修改 (目前3个项目的状态流都是一样的)

- 进入到tapd首页, 点击设置按钮, 进入「项目设置」
- 点击「需求-工作流设置」
- 点击「操作-编辑」
  - 基本信息
  - 状态定义
  - 流转设置

# 其他
待更新...