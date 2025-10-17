# 个人学术主页模板

一个简洁优雅的学术个人主页模板，基于 [Jon Barron](https://jonbarron.info/) 的个人网站改造而成。

## ✨ 特点

- 📱 **响应式设计**：自适应各种屏幕尺寸
- 🎨 **简洁美观**：清爽的学术风格
- 🖼️ **多种展示效果**：支持图片/视频预览切换
- ⚡ **轻量快速**：纯 HTML/CSS，无需构建工具
- 🔧 **易于定制**：结构清晰，方便修改
- 🌐 **GitHub Pages 友好**：可直接部署到 GitHub Pages

## 🚀 快速开始

### 1. 获取模板

```bash
# 克隆或下载此仓库
git clone https://github.com/yourusername/academic-homepage-template.git
cd academic-homepage-template
```

或直接[下载 ZIP](https://github.com/yourusername/academic-homepage-template/archive/refs/heads/main.zip)

### 2. 本地预览

**最简单的方法**：直接双击 `index.html` 在浏览器中打开

**使用本地服务器**（推荐）：
```bash
# Python 3
python -m http.server 8000

# 然后访问 http://localhost:8000
```

### 3. 开始定制

1. **修改个人信息**：编辑 `index.html` 中的姓名、简介、联系方式等
2. **替换头像**：将你的照片保存为 `images/your-photo.jpg`
3. **添加论文/项目**：参考模板中的示例，添加你的工作
4. **上传文件**：将简历等文件放到 `data/` 目录

📖 **详细教程**：请查看 [使用说明.md](./使用说明.md)

## 📁 文件结构

```
.
├── index.html              # 主页面（主要修改此文件）
├── stylesheet.css         # 样式文件
├── config.js              # 配置文件（可选）
├── 使用说明.md            # 详细的中文使用教程
├── README.md              # 本文件
├── images/                # 图片文件夹
│   ├── your-photo.jpg     # 你的头像
│   ├── project1.jpg       # 项目预览图
│   └── favicon/           # 网站图标
└── data/                  # 数据文件夹
    ├── YourName-CV.pdf    # 简历
    └── paper.bib          # 论文引用
```

## 🎯 适用人群

- 📚 学术研究人员
- 🎓 博士生、硕士生
- 👨‍💻 工程师、开发者
- 👩‍🏫 教师、讲师
- 💼 任何需要个人主页的专业人士

## 📸 预览

### 示例1：带视频预览
鼠标悬停时显示动态效果，适合展示研究成果

### 示例2：图片对比
鼠标悬停切换前后对比图，适合展示改进效果

### 示例3：静态展示
简单的图片展示，适合一般项目

## 🛠️ 自定义指南

### 修改个人信息

在 `index.html` 中找到并修改：

```html
<!-- 姓名 -->
<p class="name" style="text-align: center;">
  您的姓名
</p>

<!-- 简介 -->
<p>
  我是一名...
</p>

<!-- 联系方式 -->
<a href="mailto:your.email@example.com">Email</a>
<a href="https://scholar.google.com/citations?user=YOUR_ID">Google Scholar</a>
<a href="https://github.com/yourusername">Github</a>
```

### 添加论文

复制以下模板，修改内容：

```html
<tr onmouseout="project1_stop()" onmouseover="project1_start()" bgcolor="#ffffd0">
  <td style="padding:16px;width:20%;vertical-align:middle">
    <!-- 图片/视频区域 -->
  </td>
  <td style="padding:8px;width:80%;vertical-align:middle">
    <a href="项目链接">
      <span class="papertitle">论文标题</span>
    </a>
    <br>
    作者列表
    <br>
    <em>会议名</em>, 年份
    <br>
    <a href="...">项目主页</a> / <a href="...">arXiv</a>
    <p>论文描述</p>
  </td>
</tr>
```

详细说明请参考 [使用说明.md](./使用说明.md)

### 修改配色

编辑 `stylesheet.css`：

```css
a {
  color: #1772d0;  /* 链接颜色 */
}

a:hover {
  color: #f09228;  /* 悬停颜色 */
}
```

## 🌐 部署到 GitHub Pages

### 快速部署

1. 创建名为 `yourusername.github.io` 的仓库
2. 上传所有文件到仓库
3. 在 Settings > Pages 中启用 GitHub Pages
4. 访问 `https://yourusername.github.io`

### 使用自定义域名

1. 在仓库根目录创建 `CNAME` 文件
2. 文件内容填写你的域名：`www.yourname.com`
3. 在域名服务商配置 DNS 解析

详细步骤请参考 [使用说明.md](./使用说明.md)

## 📚 相关资源

- [原作者网站](https://jonbarron.info/) - Jon Barron
- [GitHub Pages 文档](https://pages.github.com/)
- [Markdown 语法](https://www.markdownguide.org/)
- [HTML 教程](https://developer.mozilla.org/zh-CN/docs/Web/HTML)
- [CSS 教程](https://developer.mozilla.org/zh-CN/docs/Web/CSS)

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可

本模板基于 Jon Barron 的开源网站改造，遵循原项目的开源协议。你可以自由使用、修改和分发此模板。

## 🙏 致谢

- 感谢 [Jon Barron](https://jonbarron.info/) 提供的优秀网站模板
- 感谢所有为改进此模板做出贡献的人

## 📮 联系方式

如有问题或建议，欢迎：
- 提交 [Issue](https://github.com/yourusername/repo/issues)
- 发送邮件：your.email@example.com

---

⭐ 如果这个模板对你有帮助，欢迎 Star！

最后更新：2024年10月
