# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 仓库性质

这是一个 Obsidian Vault，用于存储和管理 AI 图像生成提示词（GPT Image 2 等）。不是代码仓库，没有构建、测试或 lint 流程。

## 核心工作流

### 添加新提示词

使用 `/collect-prompt` skill 归纳提示词，它会：
1. 创建符合格式的 markdown 文件到 `Prompt Engineering/生图提示词/{分类路径}/`
2. 将例图复制到对应 `样例图片/` 目录

### Git 操作

仅推送 `Prompt Engineering/` 目录到远程仓库（`.gitignore` 已排除 `.obsidian/`、`.claude/` 等配置）。

```bash
cd "/Users/luotao/Code/tools/dev-notes/Dev Notes"
git add "Prompt Engineering/" && git commit -m "message" && git push
```

## 提示词文件格式

每个 `.md` 文件必须包含：

- **Frontmatter**：`title`、`type: prompt`、`modality`（text-to-image / image-to-image）、`domain`、`tags`
- **面包屑导航**：`> 🏠 [[生图提示词]] > [[一级分类]] > [[二级分类]]`
- **提示词正文**：在 ` ``` ` 代码块中
- **样例图片**：`![[标题-1.png]]` wiki-link 格式

## 分类体系

```
生图提示词/
├── 文生图/    → modality: text-to-image
│   ├── 海报类/     → domain: poster-design
│   ├── 插画类/     → domain: illustration
│   ├── 人像摄影类/ → domain: portrait-photography
│   ├── 角色设计类/ → domain: character-design
│   └── UI拟稿类/   → domain: ui-mockup
└── 图生图/    → modality: image-to-image
    └── 建筑/       → domain: architecture
```

## 关联 Skill

- `collect-prompt`：归纳提示词到 Obsidian vault（定义在 `~/.claude/skills/collect-prompt/`）
- `obsidian-markdown`：编辑 Obsidian 风格 Markdown
- `obsidian-cli`：操作 Obsidian vault
