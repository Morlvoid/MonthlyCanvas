# 年度绘画总结表格-MonthlyCanvas
A simple, browser-based tool to upload and showcase your monthly artwork — perfect for creating a visual year-in-review.<br>
一个轻量级简约黑白线条风格的年度绘画总结表格网页应用，专为画师记录年度创作。所有文字可实时编辑，图片可上传并智能压缩，最终可将整个表格保存为精美的总结图片，轻松制作属于你的年度艺术回顾。<br>
当然也可以用来记录任何年度总结，这里提供了12个相片与灵感空位，可以用来作为旅行总结、宠物成长、等等等等。

[![在线演示](https://img.shields.io/badge/在线演示-点击体验-blue)](http://monthly.morlvoid.pro/)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML](https://img.shields.io/badge/语言-HTML/CSS/JS-orange)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

<img width="1965" height="1335" alt="image" src="https://github.com/user-attachments/assets/6ba397aa-18a1-4d1c-b638-9f23652ee862" />

## ✨ 特性亮点

🎨 简约设计
- 黑白线条风格，无渐变色设计
- 浅色方格背景，高级感构成
- 使用画笔、画框等艺术符号装饰


📝 智能编辑
- **文字可编辑**：所有文字区域点击即可编辑
- **实时保存**：点击空白处自动保存到浏览器存储
- **图片上传**：点击图片区域上传创作作品
- **智能压缩**：自动压缩大尺寸图片，支持20MB以内文件

 💾 数据管理
- 浏览器本地存储，无需注册
- LRU智能存储管理，自动清理旧图片
- 手动清理选项，灵活管理空间

📤 导出功能
- 一键导出为高质量PNG图片
- 自动生成带日期的时间戳文件名
- 支持键盘快捷键(Ctrl+S)快速保存

# 🚀 快速开始

在线使用
直接访问[【年度绘画总结表格在线使用】](http://monthly.morlvoid.pro/)即可开始使用。

 本地运行
1. 克隆或下载本仓库
2. 在浏览器中打开 `index.html` 文件
3. 开始创建你的年度绘画总结

```bash
git clone https://github.com/Morlvoid/MonthlyCanvas.git
cd MonthlyCanvas
# 直接用浏览器打开 index.html
```

# 📖 使用指南
基础操作
编辑文字：点击任何文字区域（月份、感想）进行编辑

上传图片：点击图片区域上传你的绘画作品

自动保存：点击空白处或切换焦点自动保存

导出图片：点击底部"保存为图片"按钮导出完整总结

高级功能
图片智能压缩：系统自动将大图片压缩优化

存储空间管理：自动清理最旧的图片保证存储空间

键盘快捷键：使用 Ctrl+S 快速导出总结图片

注意事项
所有数据保存在浏览器本地存储中

建议定期导出总结图片备份

不同浏览器存储配额可能不同

# 🛠️ 技术栈
前端：HTML5, CSS3, JavaScript (ES6+)

核心库：html2canvas 用于HTML转图片

存储：浏览器 LocalStorage API

压缩算法：Canvas API 图片压缩

# 🏗️ 项目结构

```
text
年度绘画总结/
├── index.html          # 主页面
├── README.md           # 项目说明
├── LICENSE             # 开源协议
```
# 🧩 功能实现细节
图片处理流程
上传检测：验证文件类型和大小(≤20MB)

智能压缩：根据文件大小动态调整压缩参数

二次优化：必要时进行二次压缩确保存储安全

本地存储：使用LRU算法管理存储空间

存储管理策略
文字内容：直接存储，体积小

图片数据：压缩后存储，自动清理最旧图片

时间戳记录：实现LRU(最近最少使用)算法

# 🌟 设计特色
视觉设计
黑白极简：纯粹的黑白线条，无干扰色

网格背景：浅色方格背景，专业绘画风格

符号点缀：使用✎、❖、◈、✦等艺术符号装饰

交互设计
即时反馈：悬停效果，点击反馈

进度提示：大文件处理显示进度

通知系统：操作结果即时提示

# 🔧 开发相关
本地开发
本项目为纯前端项目，无需构建步骤：

直接编辑HTML/CSS/JS文件

在浏览器中实时预览

使用浏览器开发者工具调试

浏览器兼容性
Chrome 60+ ✓

Firefox 55+ ✓

Safari 11+ ✓

Edge 79+ ✓

注：由于使用LocalStorage和Canvas API，需要现代浏览器支持

# 🤝 贡献指南
欢迎提交Issue和Pull Request！

Fork 本仓库

创建功能分支 (`git checkout -b feature/MonthlyCanvas`)

提交更改 (`git commit -m 'Add some MonthlyCanvas'`)

推送分支 (`git push origin feature/MonthlyCanvas`)

开启 Pull Request


# 📄 开源协议
本项目采用 MIT License 开源协议。

# 📞 联系与支持
提交 Issue 报告问题
通过 Pull Request 贡献代码
Star ⭐ 本项目表示支持

# 🙏 致谢
感谢所有为这个项目提供灵感和帮助的人。
所有测试用户和贡献者
让每一幅创作都被记录，让每一份努力都有总结
为画师打造的年度创作记录工具

最后更新：2025年12月
