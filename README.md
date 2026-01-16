# 安基昇 (Anjisheng) 官方网站

精准医疗与表观遗传检测服务平台

## 项目简介

安基昇致力于通过前沿的 DNA 甲基化检测与基因组学技术，提供全方位的疾病风险评估与生物年龄管理方案。

## 功能特性

- 🌐 多语言支持（简体中文、繁体中文、英文）
- 📱 响应式设计，支持移动端和桌面端
- 🎨 现代化 UI 设计
- ⚡ 快速加载和流畅动画

## 技术栈

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript

## 本地开发

```bash
# 安装依赖（可选）
npm install

# 启动本地服务器
npm run dev
```

或者使用 Python 简单服务器：

```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

然后在浏览器中访问 `http://localhost:8000`

## 部署到 Vercel

### 方法一：通过 Vercel CLI

1. 安装 Vercel CLI：
```bash
npm i -g vercel
```

2. 在项目根目录运行：
```bash
vercel
```

3. 按照提示完成部署

### 方法二：通过 GitHub 集成

1. 将项目推送到 GitHub 仓库

2. 访问 [Vercel](https://vercel.com)

3. 点击 "New Project"

4. 导入你的 GitHub 仓库

5. Vercel 会自动检测项目并部署

### 方法三：通过 Vercel Dashboard

1. 访问 [Vercel Dashboard](https://vercel.com/dashboard)

2. 点击 "Add New Project"

3. 选择 "Import Git Repository" 或直接拖拽项目文件夹

4. 配置项目设置（通常使用默认设置即可）

5. 点击 "Deploy"

## 项目结构

```
AJS/
├── index.html          # 主页面
├── images/             # 图片资源
│   ├── hero.png
│   ├── epigenetic.png
│   ├── genetic.png
│   └── consult.png
├── vercel.json         # Vercel 配置文件
├── package.json        # 项目配置文件
└── README.md          # 项目说明文档
```

## 环境要求

- 现代浏览器（Chrome, Firefox, Safari, Edge）
- 无需 Node.js（纯静态网站）

## 许可证

MIT License

## 联系方式

- 网站：https://anjisheng.vercel.app
- 邮箱：kennyluck@alum.mit.edu

