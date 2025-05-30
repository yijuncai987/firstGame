# Monster Survivors - 游戏网站

这是一个为"Monster Survivors"在线游戏创建的响应式网站，针对SEO进行了优化，适用于PC和移动设备。

## 特点

- 响应式设计，在PC和移动端有良好的适配性
- 优化的SEO元素，包括标题、描述、关键词和canonical URL
- 苹果风格的配色方案
- 结构化的HTML语义标记，包含H1和多个H2标签
- 集成游戏iframe，允许用户直接在网站上玩游戏
- 全屏游戏选项
- 清晰的游戏介绍和操作指南

## 文件结构

- `index.html` - 主网页文件
- `styles.css` - 样式表文件，包含自定义样式
- `README.md` - 项目说明文档

## 技术栈

- HTML5
- CSS3
- Tailwind CSS (通过CDN)
- JavaScript (基础交互功能)

## SEO优化

该网站包含以下SEO元素：
- 语义化HTML结构
- 优化的title和meta description
- 关键词meta标签
- 规范链接(canonical URL)
- 响应式设计（移动友好性）
- 结构化内容层次

## 部署说明

1. 将所有文件上传到您的网络服务器
2. 确保域名 `myfirstgame.com` 指向该网站
3. 测试网站在不同设备和浏览器上的显示效果

## 自定义

如需修改：
- 更改颜色：编辑 `styles.css` 中的 `:root` 变量
- 更新游戏内容：编辑 `index.html` 中的相关部分
- 更改游戏源：更新iframe的src属性

## 域名和托管

该网站设计用于在 `myfirstgame.com` 域名上托管。

## 浏览器兼容性

- Chrome (最新版)
- Firefox (最新版)
- Safari (最新版)
- Edge (最新版)
- 主流移动浏览器

## 许可

版权所有 © 2023

## 项目更新日志

### 2025-01-27
- **Added artwork attribution**: Added artwork attribution to pinkbackground.app in the footer section
- **SEO optimization**: Added dofollow external link with anchor text "Pink Background"
- **User experience**: External link opens in new window with target="_blank", doesn't interrupt user gaming experience
- **Technical implementation**: 
  - Link location: Footer copyright area
  - Link attributes: rel="dofollow" target="_blank"
  - Styling: Uses existing footer-link CSS class
  - Language: English attribution text to match website language 