# Checklist — 个人网站验证清单

> 每项检查均有明确的验证方式和预期结果。拿到对应证据（截图、链接、日志）后才可标记 [x]。

## Phase 1 — 文档与规划

- [ ] **PRD 完整**：docs/prd.md 包含项目目标、目标用户、内容范围、排除边界、完成标准、隐私边界
  - 证据：在浏览器中打开 docs/prd.md 确认全部 7 个章节均已填写
- [ ] **Design 完整**：docs/design.md 包含页面结构、配色方案、文件映射、修改计划、响应式要求、素材来源
  - 证据：在浏览器中打开 docs/design.md 确认全部 8 个章节均已填写
- [ ] **Checklist 完整**：本文件包含所有可验证项
  - 证据：在浏览器中打开 docs/checklist.md 确认文档结构完整

## Phase 2 — 内容替换与验证

- [ ] **个人信息替换**：_config.yml 中 name、title、email 已替换为 Freya Xu 的真实信息
  - 证据：打开 _config.yml 确认 name 不为"Your Name"
- [ ] **头像替换**：images/ 下已有插画风格头像，_config.yml 中 about_profile_image 指向正确路径
  - 证据：在浏览器中打开网站，About 区域头像显示正常、无裂图
- [ ] **个人简介替换**：_config.yml 中 about_content 已替换为真实简介
  - 证据：网站 About 区域显示个人简介内容，无"Write an awesome description"占位文字
- [ ] **实习经历替换**：_config.yml 中 Experience 部分已替换为新浪微博 + 浦发银行 两段实习
  - 证据：网站 Experience 区域显示两条真实实习记录，公司名、职位、时间、描述均正确
- [ ] **教育背景替换**：_config.yml 中 Education 部分已替换为深圳大学 管理科学与工程 硕士
  - 证据：网站 Education 区域显示正确的学校、专业、学位、时间
- [ ] **项目经历替换**：_config.yml 中 Projects 部分已替换为三个真实项目
  - 证据：网站 Projects 区域显示三个项目卡片，内容与简历一致
- [ ] **技能信息替换**：_config.yml 中"A Little More About Me"已替换为技能清单
  - 证据：网站 Skills 区域显示 Python、Excel、Stata 等技能信息
- [ ] **社交链接清理**：只保留 GitHub + LinkedIn + email，其余（Twitter、Dribbble 等）已删除或置空
  - 证据：网站 Footer 区域只显示保留的社交图标

- [ ] **头像替换**：images/ 下已有插画风格头像，_config.yml 中 about_profile_image 指向正确路径
  - 证据：在浏览器中打开网站，About 区域头像显示正常、无裂图

## Phase 3 — 前端展示验证

- [ ] **桌面端首页完整**：在 1920x1080 分辨率下，所有板块内容完整显示，无重叠、无截断
  - 证据：截图保存为 screenshots/homepage-desktop.png
- [ ] **移动端可读**：在 375x667 视口下，文字可读、卡片自适应、社交图标排列正常
  - 证据：截图保存为 screenshots/homepage-mobile.png
- [ ] **链接可用**：所有链接（GitHub、项目链接、email）点击后跳转至正确页面，无 404
  - 证据：逐个点击确认
- [ ] **头像与配图无裂图**：所有图片资源路径正确，浏览器控制台无 404 资源错误
  - 证据：打开浏览器开发者工具 Console，确认无 Failed to load resource 错误

## Phase 4 — Git 与 GitHub Pages

- [ ] **Git 提交记录**：不少于 4 次提交，提交信息规范（如 docs: / content: / style:）
  - 证据：在 GitHub 仓库页面查看 Commit History，截图保存
- [ ] **GitHub Pages 已部署**：仓库 Settings > Pages 已启用，分支选择正确
  - 证据：访问 https://freyaxu0805-bit.github.io 确认页面正常加载
  - 截图保存为 screenshots/github-pages.png
- [ ] **README 更新**：README.md 包含项目说明、模板来源、主要修改内容、Pages 正式链接、隐私声明
  - 证据：打开 README.md 确认以上内容全部存在
- [ ] **.gitignore 有效**：不包含 .env、密钥、大文件（>10MB）等不应提交的内容
  - 证据：检查 .gitignore 是否存在，确认常见排除规则已覆盖

## Phase 5 — 最终报告与提交

- [ ] **最终报告完成**：report/final-report.md 覆盖项目定位、模板选择、AI 协作过程、验证结果、Pages 链接、反思
  - 证据：打开 report/final-report.md 确认所有章节均填写完整
- [ ] **作业截图齐全**：screenshots/ 下包含 homepage-desktop.png / homepage-mobile.png / github-pages.png / checklist.png
  - 证据：确认四个截图文件存在且非空
- [ ] **TA-Claw 提交成功**：vibe-submit submit 返回 Submitted successfully
  - 证据：终端输出截图
- [ ] **隐私安全终检**：全仓库搜索手机号、身份证号、API Key、Token，确认无泄露
  - 证据：执行 git grep 敏感关键词，结果为空

## 完成统计

- 总检查项：22 项
- 已完成：0 项
- 剩余：22 项
- 进度：0%
