# Claude Code 生态系统完整指南

> 精美的静态网站，深度解析Claude Code生态系统的所有核心模块

## 📁 项目结构

```
claude-code-intro/
├── index.html                  # 主索引目录页面
├── memory-management.html      # 记忆管理系统（Claude-Mem/Neo4j/Graphiti）
├── browser-automation.html     # 浏览器自动化（Chrome/DevTools MCP）
├── lsp-serena.html            # LSP vs Serena 深度对比
├── ralph-wiggum.html          # Ralph Wiggum 自动迭代插件
├── output-styles.html         # Output Styles 风格系统
├── plugins.html               # 插件系统完整指南
├── skills.html                # Skills 技能系统
├── auxiliary-tools.html       # 辅助工具生态
└── README.md                  # 本文件
```

## 🚀 快速开始

### 方法1：直接在浏览器中打开

```bash
# macOS
open /Users/mask/PycharmProjects/Claude\ Code\ AI/claude-code-intro/index.html

# Windows
start claude-code-intro/index.html

# Linux
xdg-open claude-code-intro/index.html
```

### 方法2：使用本地服务器（推荐）

```bash
# Python 3
cd /Users/mask/PycharmProjects/Claude\ Code\ AI/claude-code-intro
python -m http.server 8000

# 然后访问 http://localhost:8000
```

### 方法3：部署到静态网站托管

#### GitHub Pages
1. 将项目推送到GitHub仓库
2. 在仓库设置中启用GitHub Pages
3. 选择主分支作为源
4. 访问 `https://yourusername.github.io/repository-name`

#### Vercel
```bash
# 安装Vercel CLI
npm i -g vercel

# 部署
cd claude-code-intro
vercel
```

#### Netlify
```bash
# 拖拽文件夹到 Netlify Drop
# 或使用 Netlify CLI
npm i -g netlify-cli
netlify deploy
```

## 📚 内容概览

### 1. 记忆管理系统 (`memory-management.html`)
- **Claude-Mem**：轻量级插件方案
- **Neo4j MCP**：图数据库持久化
- **Graphiti MCP**：时序感知知识图谱
- 详细对比表格、配置示例、最佳实践

### 2. 浏览器自动化 (`browser-automation.html`)
- **Claude for Chrome**：原生浏览器集成
- **Chrome DevTools MCP**：高级调试能力
- 功能对比、应用场景、实战案例

### 3. LSP vs Serena (`lsp-serena.html`)
- 代码审查双雄深度对比
- 相同点与差异点分析
- 组合使用策略

### 4. Ralph Wiggum (`ralph-wiggum.html`)
- 自动迭代核心概念
- 使用方法和参数说明
- 四大最佳场景
- 避坑指南

### 5. Output Styles (`output-styles.html`)
- 三大内置风格介绍
- 自定义风格创建
- 实战案例展示

### 6. 插件系统 (`plugins.html`)
- 四大核心组件详解
- 快速上手指南
- 代码审查插件实战
- 插件市场生态

### 7. Skills系统 (`skills.html`)
- Skills vs 插件 vs Agents
- 常用Skills介绍
- 自定义Skill创建

### 8. 辅助工具 (`auxiliary-tools.html`)
- **Auto-Claude**：自动化脚本管理
- **Vibe-Kanban**：看板项目管理
- 其他社区工具介绍

## 🎨 设计特色

- ✨ **精美视觉**：渐变背景、卡片阴影、悬停动画
- 📱 **响应式设计**：完美适配桌面和移动设备
- 🔄 **流畅动画**：淡入淡出、卡片悬浮效果
- 🔗 **清晰导航**：每个页面都有返回目录按钮
- 📊 **信息层次**：卡片、表格、列表多种展示方式

## 🛠️ 技术栈

- **纯HTML5**：语义化标签，结构清晰
- **CSS3**：Flexbox、Grid、动画、渐变
- **JavaScript**：交互效果（可选）
- **零依赖**：无需安装任何包
- **跨浏览器**：支持所有现代浏览器

## 📖 使用建议

### 个人学习
1. 从 `index.html` 开始，了解整体架构
2. 根据需求跳转到感兴趣的模块
3. 参考配置示例进行实践

### 团队分享
1. 部署到内网服务器或GitHub Pages
2. 在团队会议中演示
3. 作为新人培训材料

### 持续更新
- Claude Code生态系统在快速发展
- 建议定期检查官方文档
- 根据最新版本更新内容

## 🔗 参考资源

- 📖 [Claude Code官方文档](https://docs.anthropic.com/claude-code)
- 🎬 [AI超元域博客](https://www.aivi.fyi)
- 💻 [Claude Code GitHub](https://github.com/anthropics/claude-code)
- 💬 [Discord社区](https://discord.gg/claude-code)

## 📝 内容来源

本网站内容基于以下资料整理：

- Output Styles: https://www.aivi.fyi/aiagents/introduce-ClaudeCode-Outputstyles
- Graphiti MCP: https://www.aivi.fyi/aiagents/introduce-Graphiti-MCP-Server
- Plugins: https://www.aivi.fyi/llms/introduce-Claude-Code-Plugins
- Chrome DevTools MCP: https://www.aivi.fyi/aiagents/introduce-Chrome-DevTools-MCP
- Claude for Chrome: https://www.aivi.fyi/aiagents/introduce-Claude-Code-for-Chrome
- Ralph Wiggum: https://www.aivi.fyi/llms/introduce-ralph-wiggum

## 🎯 待办事项

- [ ] 添加搜索功能
- [ ] 添加深色模式切换
- [ ] 添加打印样式优化
- [ ] 添加多语言支持（英文版）
- [ ] 添加视频教程嵌入
- [ ] 添加互动式代码示例

## 📄 许可证

本项目内容基于 CC BY-NC-SA 4.0 许可证

## 🙏 致谢

感谢 Anthropic 团队开发 Claude Code
感谢 AI超元域 提供的详细教程
感谢 Claude Code 社区的贡献者

---

**让AI为你打工，从重复劳动中解放出来！** 🚀
