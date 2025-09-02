# BXS 战队网站

基于 Astro + Tailwind CSS 的现代化静态战队网站，采用组件化架构设计。

## 🚀 项目结构

```text
proj/
├── public/                    # 静态资源目录
│   ├── kabo.png              # 装饰图片
│   └── logo.svg              # 战队Logo
├── src/
│   ├── layout/               # 布局组件目录
│   │   ├── Layout.astro      # 基础HTML布局组件
│   │   ├── MainLayout.astro  # 主页面布局组件
│   │   └── Navbar.astro      # 导航栏组件
│   ├── pages/                # 页面文件目录
│   │   ├── index.astro       # 主页
│   │   ├── index_clean.astro # 简洁版主页
│   │   ├── blog.astro        # 博客列表页（带搜索功能）
│   │   ├── blog_clean.astro  # 简洁版博客页
│   │   ├── team_memeber.astro    # 战队成员页
│   │   ├── team_memeber_new.astro # 新版战队成员页
│   │   └── blog/
│   │       └── [slug].astro  # 动态博客文章页面
│   ├── data/                 # 数据文件目录
│   │   └── team_members.yml  # 战队成员信息数据
│   ├── blogs/                # Markdown 博客文件目录
│   │   ├── 1.md              # 示例博客文章
│   │   ├── 1 copy.md         # 示例博客文章
│   │   └── 1 copy 2.md       # 示例博客文章
│   └── styles/
│       └── global.css        # 全局样式文件
├── .gitignore                # Git 忽略文件配置
├── astro.config.mjs          # Astro 框架配置文件
├── tailwind.config.mjs       # Tailwind CSS 配置
├── tsconfig.json             # TypeScript 配置
├── package.json              # 项目依赖和脚本
├── pnpm-lock.yaml           # PNPM 包管理器锁定文件
└── README.md                # 项目说明文档
```

## 需要下载的前置插件

在使用前请先使用
```
pnpm install
```

## 