# cnc-fixture-design

数控夹具与加工工艺知识库，是一个可被 Agent Skills 主机加载的技能包。内容整理自 131 篇夹具/机床资料（夹具侠文章、直播回顾、教材、手册）与 110 页《夹具设计实训》课件，覆盖定位、夹紧、液压油路、薄壁变形、零点定位、焊接工装、汽车与 3C 案例。

由 [book-to-skill](https://github.com/virgiliojr94/book-to-skill) 流程生成。

## 安装

```bash
npx skills add https://github.com/<owner>/cnc-fixture-design-skill --skill cnc-fixture-design
```

或直接把本目录复制到你的 Agent Skills 根目录（如 `~/.agents/skills/cnc-fixture-design`）。

## 内容

- `SKILL.md` — 核心框架、章节索引、主题索引
- `chapters/` — 16 章：定位、误差、夹紧、液压、元件材料、设计流程、典型机床夹具、数控工艺、卡盘/涨套/顶尖、真空/磁力/冰冻/液性塑料、薄壁、汽车案例、3C/3D 打印、零点定位、焊接夹具、失效排查
- `glossary.md` — 术语表
- `patterns.md` — 可复用设计模式
- `cheatsheet.md` — 决策表、关键数字、快速验证

## 说明

- 本仓库内容是**合成的知识摘要与设计规则**，不是原始教材/文章的全文，也不包含原始 PDF、视频或图片。
- 原始资料中大量结构图/截图无法转为文本，具体结构请回查原资料。
- 部分来源为 OCR 文本，可能存在错字；关键参数请以原图/原书为准。
- 本技能不替代具体项目的强度、刚度、公差与安全校核。
