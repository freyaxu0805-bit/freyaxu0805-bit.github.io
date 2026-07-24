# 个人网站 — Freya Xu

> 互联网商业化与金融背景 · AI 工具应用探索 · 管理科学与工程硕士在读

基于 Modern Resume Theme 构建的个人简历网站，托管于 GitHub Pages。

**正式链接：** https://freyaxu0805-bit.github.io

---

## 项目简介

面向实习招聘方的个人简历网站，展示 Freya Xu 的教育背景、实习经历、项目经验与技能，传递"愿意尝试新技术、紧跟时代发展"的个人品牌形象。

## 模板来源

- 模板：Modern Resume Theme (MIT License)
- 原模板演示：https://sproogen.github.io/modern-resume-theme/

## 主要修改内容

| 项目 | 修改说明 |
|------|----------|
| 个人信息 | 替换为 Freya Xu 的姓名、职位、简介 |
| 头像 | AI 生成插画风格小猫头像 |
| 实习经历 | 新浪微博 + 浦发银行 两段实习 |
| 教育背景 | 深圳大学 管理科学与工程 硕士 |
| 项目经历 | 量化分析、市场调研、创协项目 |
| 技能清单 | 软件技能、英语能力、兴趣方向 |
| 社交链接 | 仅保留 GitHub，其余清空 |
| 目录结构 | 按作业要求组织 docs/ report/ screenshots/ |

## 本地预览

1. 确保已安装 Ruby 和 Jekyll
2. 在项目目录运行 bundle install 和 bundle exec jekyll serve
3. 浏览器打开 http://localhost:4000

## 部署方式

本仓库已启用 GitHub Pages（Settings > Pages > 从 main 分支构建），推送后自动部署。

## 隐私声明

- 本仓库不含任何密码、API Key、Token、私钥等敏感信息
- 不包含个人手机号、家庭住址、身份证号等隐私数据
- .gitignore 已配置常见排除规则

## 项目结构

```
网站源文件与资源/     # 模板完整源码备份
docs/                 # 作业文档（PRD / Design / Checklist）
report/               # 最终报告
screenshots/          # 验证截图
images/               # 头像与配图
_config.yml           # 核心配置
index.md              # 首页入口
README.md             # 本文件
```

## 项目截图

- homepage-desktop.png
- homepage-mobile.png
- github-pages.png
- checklist.png
