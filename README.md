# 组件星图 CompAtlas · 设计模板与组件 GitHub Top 50 力量地图

三件套：

| 文件 | 内容 |
|---|---|
| `TOP50-榜单.md` | 50 项实测榜单（GitHub API 快照 2026-10-06/07，合计 2,135,844 Star）+ 遗珠/排除/勘误/风险标注 |
| `PRD.md` | 产品需求文档，核心为 §6「Top 50 能力调用映射表」 |
| `index.html` | 网站本体（零依赖单文件）：#/ 榜单 / PRD / 组件工坊 / 方法论 五页 |

`qa/` 为 Playwright 验收截图（34/34 断言通过），`result.tsv` 为原始采集数据。

本地预览：`python3 -m http.server 8923` 后访问 `/index.html#/`。
