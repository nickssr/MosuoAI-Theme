# MosuoAI Theme

一个现代化的 Astro 博客主题，专为技术内容创作者设计。

## ✨ 特性

- 🎨 **精美设计** - 暗色/亮色主题无缝切换
- 📱 **完全响应式** - 完美适配桌面和移动设备
- 🔍 **内置搜索** - 基于 Pagefind 的全文搜索
- 📝 **Markdown 增强** - 代码高亮、数学公式、自定义容器
- 🏷️ **标签系统** - 灵活的内容分类
- 📊 **多种内容类型** - 资讯、教程、评测、开源、资源
- 🚀 **极速性能** - 基于 Astro 的静态站点生成
- 🎯 **SEO 优化** - 完善的 SEO 配置和 Open Graph 支持

## 🚀 快速开始

### 1. 使用此主题

```bash
# 克隆主题
git clone https://github.com/nickssr/MosuoAI-Theme.git my-blog
cd my-blog

# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 构建生产版本
npm run build
```

### 2. 自定义配置

编辑 `src/config.mjs` 文件来自定义您的网站：

```javascript
export const siteConfig = {
  name: 'Your Blog Name',
  description: 'Your blog description',
  url: 'https://your-domain.com',
  // ...
};
```

### 3. 开始写作

在 `src/content/` 目录下创建 Markdown 文件：

```bash
src/content/news/my-first-post.md
```

## 📁 项目结构

```
├── src/
│   ├── components/     # UI 组件
│   ├── layouts/        # 页面布局
│   ├── pages/          # 页面路由
│   ├── styles/         # 全局样式
│   ├── content/        # Markdown 内容
│   ├── assets/         # 静态资源
│   └── config.mjs      # 网站配置
├── public/             # 公共资源
└── astro.config.mjs    # Astro 配置
```

## 📝 内容类型

主题支持 5 种内容类型：

- **资讯** (`news`) - 行业资讯、新闻动态
- **教程** (`tutorials`) - 技术教程、学习指南
- **评测** (`reviews`) - 产品评测、工具对比
- **开源** (`opensource`) - 开源项目介绍
- **资源** (`resources`) - 资源推荐、工具合集

## 🎨 主题定制

### 颜色主题

编辑 `src/styles/variables.css` 来自定义颜色：

```css
:root {
  --color-primary: #00d4e0;
  --color-primary-dark: #00b8c4;
  /* ... */
}
```

### 组件定制

所有组件都在 `src/components/` 目录下，您可以自由修改。

## 📄 License

MIT License © 2026 MosuoAI

## 🙏 致谢

- [Astro](https://astro.build/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Lucide Icons](https://lucide.dev/)
