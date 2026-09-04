# 胡妍静｜产品经理个人简历网站

基于现有 Resume 项目完成的中文个人简历网站。保留原项目的单页结构、莫兰迪视觉风格、响应式布局、卡片详情弹窗与横向滚动交互，并将作者信息替换为胡妍静的简历内容。

## 内容

- 个人介绍
- 工作经历
- 教育经历
- 项目经历
- 核心优势
- 技能与证书
- 联系方式
- 个人职业照

## 项目结构

```text
.
├── index.html
├── README.md
└── images/
    ├── portrait.jpg
    └── hr-industry.jpg
```

网站使用纯 HTML、CSS 和 JavaScript，无需构建工具。Font Awesome 图标通过 CDN 加载；其余内容均为静态本地资源。

## 本地预览

直接打开 `index.html`，或在项目目录启动任意静态文件服务器。

```bash
python3 -m http.server 8000
```

然后访问 `http://localhost:8000/`。

## GitHub Pages 部署

1. 将本目录内容推送到 GitHub 仓库的 `main` 分支。
2. 在仓库的 **Settings > Pages** 中选择 **Deploy from a branch**。
3. 选择 `main` 分支和 `/ (root)` 目录后保存。
4. 等待 GitHub Pages 完成部署。

## 信息来源

页面内容来自用户提供的《胡妍静-产品经理.pdf》。首页头像来自用户提供的职业照；“深入的行业理解”卡片图片来自 [Mimi Thian / Unsplash](https://unsplash.com/photos/GXEcTqlZHno)，按 Unsplash License 免费使用。
