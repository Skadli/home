# 个人主页/起始页项目

## 项目简介
这是一个基于 Vue.js 构建的个人主页或起始页项目。它旨在提供一个美观、可定制的浏览器起始页，集成了天气、每日一言、音乐播放、社交链接等多种实用功能。

## 主要功能
- **动态背景**: 支持自定义背景图片。
- **天气显示**: 集成天气信息展示。
- **每日一言**: 展示随机的一句话。
- **音乐播放器**: 内置简单的音乐播放功能。
- **社交链接**: 方便快捷地访问常用社交平台。
- **时间胶囊/待办事项**: 可能包含时间管理或备忘功能。
- **网站导航**: 快速访问常用网站。
- **自定义设置**: 提供个性化配置选项。

## 技术栈
- Vue.js (前端框架)
- Vite (构建工具)
- Sass (CSS 预处理器)
- Axios (HTTP 客户端)

## 安装与运行

### 1. 克隆仓库
```bash
git clone [你的仓库地址]
cd home # 进入项目目录
```

### 2. 安装依赖
```bash
bun install # 或者 npm install / yarn install
```

### 3. 运行项目
```bash
bun dev # 或者 npm run dev / yarn dev
```
项目将会在本地启动，通常访问 `http://localhost:3000` 即可预览。

### 4. 构建生产版本
```bash
bun build # 或者 npm run build / yarn build
```
构建后的文件将生成在 `dist` 目录下，可部署到静态文件服务器。

## 项目结构概览
```
.
├── public/                       # 静态资源，如字体、图片、图标
├── src/                          # 核心源代码
│   ├── api/                      # API 请求相关
│   ├── assets/                   # 静态资源，如JSON数据
│   ├── components/               # 可复用组件
│   ├── store/                    # Vuex 状态管理
│   ├── style/                    # 全局样式
│   ├── utils/                    # 工具函数
│   ├── views/                    # 页面视图
│   ├── App.vue                   # 根组件
│   └── main.js                   # 项目入口文件
├── index.html                    # HTML 模板
├── package.json                  # 项目依赖及脚本
└── vite.config.js                # Vite 配置
```


