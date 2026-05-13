# FIRE 生活家 博客

> 🔥 通往 FIRE 之路的个人记录博客

## 📖 项目简介

这是 [FIRE 生活家](https://firelifes.github.io) 的个人博客源代码，基于 Jekyll + Minimal Mistakes 主题搭建，记录财务自由、投资、生活等相关内容。

## 🛠 技术栈

| 技术 | 说明 |
|------|------|
| **Jekyll** | 静态网站生成器 |
| **Minimal Mistakes** | Jekyll 主题 |
| **GitHub Pages** | 自动部署托管 |
| **不蒜子** | 网站访问统计 |

## ✨ 功能特性

- 📝 **分类文章**：项目、知识、随笔等分类
- 🏷️ **标签系统**：文章标签聚合
- 📚 **合集系列**：系列文章目录导航
- 📊 **访问统计**：总访问量、访客数、单篇文章阅读量
- 📱 **响应式设计**：适配桌面和移动端
- 🏷️ **版本标识**：页脚显示构建版本号

## 🚀 本地开发

```bash
# 安装依赖
bundle install

# 启动本地服务器
bundle exec jekyll serve

# 访问 http://localhost:4000
```

## 📁 目录结构

```
firelifes.github.io/
├── _data/           # 数据文件
├── _includes/       # 模板片段 (footer.html 等)
├── _layouts/        # 页面布局模板
│   ├── default.html   # 全站通用布局
│   ├── post.html      # 文章详情页
│   ├── category.html  # 分类列表页
│   └── home.html      # 首页
├── _posts/          # 文章内容
├── assets/          # 静态资源
├── _config.yml      # 站点配置
└── index.md         # 首页
```

## 🌐 在线访问

博客地址：https://firelifes.github.io

## 📝 更新日志

所有改动会自动触发 GitHub Pages 构建，页脚版本号自动更新。

---

💡 本博客使用 Jekyll + GitHub Pages 自动构建部署