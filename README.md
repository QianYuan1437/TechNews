# 📡 科技日报

每日自动抓取科技圈精选资讯，由 GitHub Actions 驱动，发布于 GitHub Pages。

🌐 **访问地址**：[https://qianyuan1437.github.io/TechNews](https://qianyuan1437.github.io/TechNews)

## 功能特性

- 每天北京时间 **早 8:00** 自动更新
- 聚合 8 个主流科技媒体 RSS 源
- 静态网站，无需服务器，加载极快
- 支持历史存档查阅（最近 30 天）
- 深色主题，响应式布局

## 新闻来源

| 来源 | 分类 |
|------|------|
| 🔶 Hacker News | 综合科技 |
| 📱 The Verge | 科技资讯 |
| 🚀 TechCrunch | 创业科技 |
| ⚡ Wired | 科技文化 |
| 🔬 MIT Technology Review | 前沿技术 |
| 🖥️ Ars Technica | 深度科技 |
| 🇨🇳 36氪 | 国内科技 |
| 📲 少数派 | 数字生活 |

## 项目结构

```
TechNews/
├── .github/workflows/
│   └── daily-news.yml    # GitHub Actions 工作流
├── scripts/
│   ├── fetch_news.py     # 新闻抓取脚本
│   └── generate_site.py  # 静态网站生成脚本
├── assets/
│   ├── style.css         # 样式文件
│   └── app.js            # 前端交互
├── data/news/            # 新闻数据（自动生成）
├── docs/                 # 网站文件（自动生成，GitHub Pages 源）
├── requirements.txt
└── README.md
```

## 手动触发

在 GitHub 仓库的 **Actions** 页面，选择 `每日科技新闻更新` 工作流，点击 **Run workflow** 即可手动触发。
