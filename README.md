
## 2018.4.30 更新
- 添加了从github获取个人开源项目的功能,显示信息更加全面,显示开源项目列表
- Readme 从github动态获取

## 2018.4.29 更新
- 增加个人信息的状态栏
- 修复发图片博文的BUG 

## 简介

博客基于 GitHub Pages 与 Github API 实现无后台，可动态发布博客的系统
博客数据储存于gist 通过Github API 进行增删改查
喜欢的话留下你的星星╭(●｀∀´●)╯╰(●’◡’●)╮

### 特点

- [x] 基于 GitHub Pages 无需服务器
- [x] 改进传统 GitHub Pages 不能动态发布的缺陷
- [x] 使用vue单页面

### 项目源码
[https://github.com/GitHub-Laziji/vblog][3]

### 演示地址
[https://github-laziji.github.io][1]

### 快速使用
搭建博客只需2步
1. 点击github头像旁边的 "+" 号 选择 "Import repository" 克隆地址填"https://github.com/GitHub-Laziji/GitHub-Laziji.github.io" 项目名填 "${你的用户名}.github.io" 
2. 克隆完成后 修改文件 /static/configuration.json 中的 "github-username" 为自己的github用户名


类似演示地址其中 GitHub-Laziji 为我的用户名


现在 ${你的用户名}.github.io 就是你的个人博客了,例如[https://github-laziji.github.io][1]

### 获取Token

在 *github > settings > Developer settings > Personal access tokens*  勾选gist权限 获取Token


------


作者 *Laziji*



  [1]: https://github-laziji.github.io
  [2]: https://github.com/GitHub-Laziji/GitHub-Laziji.github.io
  [3]: https://github.com/GitHub-Laziji/vblog
