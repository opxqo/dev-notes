# Prompt Engineering 提示词库

基于 GPT Image 2 等 AI 图像生成模型的提示词集合，按风格和用途分类整理，配合 Obsidian 使用。

## 目录结构

```
Prompt Engineering/
├── 生图提示词/
│   ├── 文生图/
│   │   ├── 海报类/        # 城市宣传、旅行、极简线稿等海报
│   │   ├── 插画类/        # 3D微缩、皮克斯、国风工笔等插画风格
│   │   ├── 人像摄影类/    # 胶片人像、美妆人像
│   │   ├── 角色设计类/    # 机甲、卡牌等角色设计
│   │   └── UI拟稿类/      # 概念UI、发布会现场
│   ├── 图生图/
│   │   └── 建筑/          # 冰箱贴、插画海报、矢量风格等
│   └── GPT Image 2 提示词写作原则.md
├── UI设计提示词/           # （待补充）
└── 工作流提示词/           # （待补充）
```

## 提示词格式

每个提示词包含：

- **Frontmatter** — 标题、分类、标签等元数据，支持 Obsidian Dataview 查询
- **提示词正文** — 完整的英文/中文提示词，可直接复制使用
- **样例图片** — AI 生成的效果示例

## 样例展示

<table>
<tr>
<td align="center"><img src="Prompt%20Engineering/%E7%94%9F%E5%9B%BE%E6%8F%90%E7%A4%BA%E8%AF%8D/%E6%96%87%E7%94%9F%E5%9B%BE/%E6%B5%B7%E6%8A%A5%E7%B1%BB/%E6%A0%B7%E4%BE%8B%E5%9B%BE%E7%89%87/%E9%BB%84%E9%B9%A4%E6%A5%BC%E5%9B%BD%E6%BD%AE%E6%B3%A2%E6%99%AE%E6%B5%B7%E6%8A%A5-1.png" width="200"><br>黄鹤楼国潮波普</td>
<td align="center"><img src="Prompt%20Engineering/%E7%94%9F%E5%9B%BE%E6%8F%90%E7%A4%BA%E8%AF%8D/%E6%96%87%E7%94%9F%E5%9B%BE/%E6%B5%B7%E6%8A%A5%E7%B1%BB/%E6%A0%B7%E4%BE%8B%E5%9B%BE%E7%89%87/%E6%AD%A6%E6%B1%89%E6%97%85%E8%A1%8C%E6%B5%B7%E6%8A%A5-1.png" width="200"><br>武汉旅行海报</td>
<td align="center"><img src="Prompt%20Engineering/%E7%94%9F%E5%9B%BE%E6%8F%90%E7%A4%BA%E8%AF%8D/%E6%96%87%E7%94%9F%E5%9B%BE/%E6%B5%B7%E6%8A%A5%E7%B1%BB/%E6%A0%B7%E4%BE%8B%E5%9B%BE%E7%89%87/%E5%B9%BF%E5%B7%9E%E5%A1%94%E6%9E%81%E7%AE%80%E6%B5%B7%E6%8A%A5-1.png" width="200"><br>广州塔极简海报</td>
</tr>
<tr>
<td align="center"><img src="Prompt%20Engineering/%E7%94%9F%E5%9B%BE%E6%8F%90%E7%A4%BA%E8%AF%8D/%E5%9B%BE%E7%94%9F%E5%9B%BE/%E5%BB%BA%E7%AD%91/%E6%A0%B7%E4%BE%8B%E5%9B%BE%E7%89%87/%E9%AB%98%E7%AB%AF%E6%8F%92%E7%94%BB%E6%B5%B7%E6%8A%A5-1.png" width="200"><br>高端插画海报</td>
<td align="center"><img src="Prompt%20Engineering/%E7%94%9F%E5%9B%BE%E6%8F%90%E7%A4%BA%E8%AF%8D/%E5%9B%BE%E7%94%9F%E5%9B%BE/%E5%BB%BA%E7%AD%91/%E6%A0%B7%E4%BE%8B%E5%9B%BE%E7%89%87/%E5%9B%BD%E6%BD%AE%E5%87%A0%E4%BD%95%E6%8F%92%E7%94%BB-1.png" width="200"><br>国潮几何插画</td>
<td align="center"><img src="Prompt%20Engineering/%E7%94%9F%E5%9B%BE%E6%8F%90%E7%A4%BA%E8%AF%8D/%E5%9B%BE%E7%94%9F%E5%9B%BE/%E5%BB%BA%E7%AD%91/%E6%A0%B7%E4%BE%8B%E5%9B%BE%E7%89%87/%E5%86%B0%E7%AE%B1%E8%B4%B4%E8%AE%BE%E8%AE%A1-1.png" width="200"><br>冰箱贴设计</td>
</tr>
</table>

## 风格速览

| 类别 | 代表作品 |
|------|----------|
| 海报 | 黄鹤楼国潮波普、城市极简线稿、双重曝光 |
| 插画 | 皮克斯3D、宋代工笔画、柴犬概念店、锦鲤星云 |
| 摄影 | 柯达胶片人像、高级感美妆 |
| 角色 | 机甲少女、黄金十二宫卡牌 |
| UI | 宋朝朋友圈、iPhone发布会 |
| 建筑 | 冰箱贴设计、多巴胺插画、国潮几何 |

## 使用方式

1. 用 Obsidian 打开本仓库
2. 在 `生图提示词/` 下按分类浏览
3. 复制提示词正文，粘贴到 ChatGPT / DALL-E / Midjourney 等平台使用

## 查询示例

在 Obsidian 中使用 Dataview 插件：

```dataview
TABLE modality, domain
FROM "Prompt Engineering/生图提示词"
WHERE type = "prompt"
SORT file.name ASC
```
