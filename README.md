# BXS 战队网站

基于Astro+tailwindcss的静态网站

## 🚀 项目结构

```text
vigorous-venus/
├── public/                     # 静态资源目录
│   ├── logo.svg               # 战队Logo
│   └── kabo.png               # 装饰图片
├── src/
│   ├── layout/                # 布局组件目录
│   │   ├── Layout.astro       # 基础HTML布局组件
│   │   ├── Navbar.astro       # 导航栏组件
│   │   └── MainLayout.astro   # 主页面布局组件
│   ├── pages/                 # 页面文件目录
│   │   ├── index.astro        # 首页
│   │   ├── blog.astro         # 博客列表页
│   │   ├── team_memeber.astro # 战队成员页
│   │   └── blog/
│   │       └── [slug].astro   # 动态博客文章页面
│   ├── blogs/                 # Markdown 博客文件
│   │   ├── 1.md               # 示例博客文章
│   │   ├── 1 copy.md
│   │   └── 1 copy 2.md
│   └── styles/
│       └── global.css         # 全局样式文件
├── astro.config.mjs           # Astro 配置文件
├── tailwind.config.mjs        # Tailwind CSS 配置
├── tsconfig.json              
└── package.json               # 项目依赖和脚本
```

大概就这样，先写这么多