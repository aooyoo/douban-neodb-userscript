# 豆瓣 NeoDB 助手

一个简单的用户脚本，用于在豆瓣电影页面添加 NeoDB 链接。让你可以快速查看和对比在 NeoDB.social 上的相关条目。

## 功能特点

- 在豆瓣电影页面右侧自动添加 NeoDB 搜索链接
- 使用电影标题和年份进行精确匹配
- 保持豆瓣原有界面风格
- 轻量级实现，不影响页面加载速度

## 安装步骤

1. 首先需要安装一个用户脚本管理器。推荐使用以下任意一个：
   - [Tampermonkey](https://www.tampermonkey.net/)（支持 Chrome、Microsoft Edge、Safari、Opera Next 和 Firefox）
   - [Violentmonkey](https://violentmonkey.github.io/)（支持 Chrome、Microsoft Edge、Firefox）

2. 安装用户脚本管理器后，点击下面的链接安装本脚本：
   [安装豆瓣 NeoDB 助手](https://github.com/aooyoo/douban-neodb-userscript/douban-neodb-userscript.js)

## 使用方法

1. 安装完成后访问任意豆瓣电影页面
2. 在右侧栏中可以看到新增的 "NeoDB" 区块
3. 点击链接即可跳转到 NeoDB 查看对应影片信息

## 兼容性

- 支持的浏览器：Chrome, Firefox, Edge, Safari
- 支持的网站：豆瓣电影页面 (movie.douban.com/subject/*)

## 常见问题

Q: 为什么某些页面没有显示 NeoDB 链接？  
A: 确保你已经安装了脚本管理器，并且正确安装了该脚本。如果问题仍然存在，可以尝试刷新页面。

Q: 链接跳转到了错误的电影？  
A: 脚本使用电影标题和年份进行搜索，在极少数情况下可能会出现匹配错误。你可以手动修改搜索关键词来找到正确的影片。

## 开发计划

- [ ] 支持豆瓣图书页面
- [ ] 支持豆瓣音乐页面
- [ ] 添加 NeoDB 评分显示
- [ ] 提供更多定制化选项

## 贡献指南

欢迎提交 Issue 和 Pull Request！如果你有任何改进建议，请随时联系我们。

## 许可证

本项目采用 [MIT](LICENSE) 许可证。

## 致谢

- 感谢 [NeoDB](https://neodb.social/) 提供优秀的媒体数据库服务
- 感谢 [9KB](https://9kb.me/) 提供 Fediverse 实例账号
- 感谢所有贡献者的支持

## 更新日志

### v0.4 (2024-12-20)
- 修复重复显示问题
- 优化样式表现

### v0.3 (2024-12-20)
- 改进显示位置
- 优化样式设计

### v0.2 (2024-12-19)
- 添加样式
- 修复插入位置

### v0.1 (2024-12-18)
- 初始版本发布
