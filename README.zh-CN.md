# 🎯 技能商店 - Skill Store

收录最全、更新最快的 AI Agent 技能库，涵盖**文档处理、内容创作、编程开发、机器学习、自动化工作流**等多个领域的精选技能包。

[![官方技能](https://img.shields.io/badge/官方技能-182-blue?style=flat-square)](https://github.com/aspnmy/skill.aspnmy.github.io)
[![本地技能](https://img.shields.io/badge/本地技能-61-green?style=flat-square)](https://github.com/aspnmy/skill.aspnmy.github.io)
[![备份覆盖](https://img.shields.io/badge/备份覆盖-100%25-success?style=flat-square)](https://github.com/aspnmy/skill.aspnmy.github.io)
[![自动更新](https://img.shields.io/badge/更新-每24小时-orange?style=flat-square)](https://github.com/aspnmy/skill.aspnmy.github.io)

> 英文版: [README.md](README.md)

## 📊 统计数据

- **官方技能**: 182 个（来自 awesome-agent-skills，自动爬取）
- **本地技能**: 61 个（25 核心 + 30 子技能 + 6 系统内置）
- **技能总数**: 243 个
- **备份覆盖率**: 100%（71 个压缩包）
- **自动更新**: 每 24 小时自动爬取最新技能

## 🌟 核心特性

### 🤖 自动更新
每 24 小时自动爬取 [awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) 仓库。

### 📦 双重技能库
- **官方技能**: 182 个 — Anthropic、Vercel、Cloudflare、Google Labs、Hugging Face 等顶级团队
- **本地技能**: 61 个 — 内容创作、视频制作、电商营销等中文垂直领域

### 🏷️ 智能分类
按功能、来源等多维度标签分类。

## 🚀 快速开始

```bash
git clone https://github.com/aspnmy/skill.aspnmy.github.io.git
cd skill
pip install -r requirements.txt
python main.py --once    # 立即更新
python main.py --daemon  # 守护进程模式
python main.py --stats   # 数据统计
```

### GitHub Pages 部署

推送 `aspnmy` 分支后自动触发部署：
```bash
git push origin aspnmy
```
站点地址：`https://skill.aspnmy.github.io/`

## 🏷️ 分支说明

- **main**: 原始分支（fork 自 anbeime/skill）
- **aspnmy**: 当前活跃分支，修复 GitHub Pages 兼容性和路径配置问题

## 🛠️ 近期修复

- 修复 `config.py` 中硬编码的绝对路径，改用相对路径
- 修复 `local-skills.html` 的 GitHub Pages 兼容性（fetch 相对路径 + 数据格式对齐）
- 切换 remote 到 `github.com/aspnmy/skill.aspnmy.github.io`

## 📖 文档

- [技能管理数据库](docs/技能管理数据库.md)
- [技能清理与迁移指南](docs/技能清理与迁移指南.md)
- [金融接口技能汇总](金融接口技能汇总.md)

## 🔗 相关链接

- [GitHub 仓库](https://github.com/aspnmy/skill.aspnmy.github.io)
- [在线商店](https://skill.vercel.app)
- [Awesome Agent Skills](https://github.com/VoltAgent/awesome-agent-skills)

## 📝 更新日志

### v2.1 (2026-06-16)
- 🔄 切换 remote 到 aspnmy/skill
- 🌿 创建 aspnmy 分支
- 🐛 修复 config.py 硬编码路径
- 🌐 修复 local-skills.html GitHub Pages 兼容性
- 🚀 添加 GitHub Pages 部署工作流
- 📄 添加 `.nojekyll` + `404.html`
- 🔗 修复全部 HTML/JSON 中 anbeime→aspnmy 链接

### v2.0 (2026-02-11)
- ✨ 新增 12 个本地技能（总数 61）
- 🏷️ 完善分类体系（14 个分类）

### v1.0 (2026-02-09)
- 🎉 初始发布，182 官方 + 49 本地技能

---

**最后更新**: 2026-06-16
**维护者**: aspnmy
**分支**: aspnmy
