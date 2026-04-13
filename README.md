# AI Agent 工作台 Demo

抖店服务市场 AI Agent 工作台交互演示，包含5个会话场景。

## 部署到 Vercel

### 方式一：通过 Vercel CLI（推荐）

```bash
# 1. 安装 Vercel CLI
npm i -g vercel

# 2. 进入项目目录
cd vercel-demo

# 3. 部署（首次会要求登录）
vercel

# 4. 部署到生产环境
vercel --prod
```

### 方式二：通过 GitHub + Vercel 网页端

1. 在 GitHub 新建一个仓库（如 `ai-agent-demo`）
2. 把 `index.html`、`vercel.json`、`package.json` 推送到仓库
3. 登录 [vercel.com](https://vercel.com)，点击 **Add New Project**
4. 选择刚创建的 GitHub 仓库，点击 **Deploy**
5. 等待几秒，部署完成后会给你一个 `xxx.vercel.app` 的链接

### 方式三：直接拖拽部署

1. 登录 [vercel.com](https://vercel.com)
2. 把解压后的整个文件夹直接拖拽到 Vercel 控制台
3. 自动部署完成

## 项目结构

```
vercel-demo/
├── index.html      # 主页面（完整Demo）
├── vercel.json      # Vercel 部署配置
├── package.json     # 项目信息
└── README.md        # 本文件
```
