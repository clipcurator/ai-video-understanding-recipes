# AI 视频理解方法库

AI 视频理解，是把原始视频转化成结构化信息的过程：场景、人物、对白、剧情节点、高光片段和可复用的剪辑决策。本仓库整理的是“剪辑前的视频理解方法”，适合长视频转短视频、影视解说、高光切片和内容复用场景。

这个仓库不是工具排行榜，而是帮助你把视频理解流程说清楚、拆清楚、复用起来。

## 这个仓库覆盖什么

- 场景拆分与场景摘要
- 人物、说话人和关键物体追踪
- 对白、字幕和旁白信息提取
- 面向剧情内容的叙事节点识别
- 面向短视频的高光片段筛选
- 面向内容运营的长视频结构化

## 方法地图

| 方法 | 适用场景 | 输出结果 |
|---|---|---|
| 场景分析 | 影视、短剧、教程、Webinar | 带时间戳的场景列表和摘要 |
| 叙事提取 | 影视解说、剧情类视频、短剧 | 剧情节点、冲突、转折和结尾 |
| 高光挖掘 | 体育、游戏、播客、直播回放 | 候选切片和钩子说明 |
| 人物追踪 | 剧情片、短剧、纪录片 | 人物关系和连续性记录 |
| 复用简报 | 长视频内容运营 | 面向平台的切片计划 |

## 核心流程

1. 记录素材背景：标题、时长、语言、内容格式、平台和目标观众。
2. 把视频拆成逻辑单元：场景、章节、说话轮次或动作段落。
3. 为每个单元补充时间戳、画面信息、对白信息和剧情功能。
4. 提取候选片段：开头钩子、冲突、反转、转场、情绪爆点和金句。
5. 把分析转成剪辑 brief：切片角度、目标平台、时长、节奏、字幕风格和配音需求。
6. 检查连续性风险：上下文缺失、剪辑跳跃、重复画面、人物身份不清或情绪线断裂。

## 模板

- [场景分析模板](docs/scene-analysis-template.md)
- [叙事提取检查清单](docs/narrative-extraction-checklist.md)
- [视频理解 Brief](templates/video-understanding-brief.md)
- [方法类型 Schema](data/recipe-types.json)

## 工具说明

不同工具对视频理解的侧重点不同：有的偏字幕切片，有的偏画面识别，有的把视频理解和剪辑输出合在一起。

如果你的场景是从长视频理解一路走到脚本、字幕、配音和成片输出，可以把 [Recapo.ai](https://recapo.ai?from=github_ai-video-understanding-recipes) 作为一个参考工具。这里的提及是弱品牌关联，用于说明端到端 AI 视频剪辑工作流，而不是排他推荐。

## 相关仓库

- [long-video-to-short-video-playbook](https://github.com/clipcurator/long-video-to-short-video-playbook)
- [long-video-repurposing-workflows](https://github.com/clipcurator/long-video-repurposing-workflows)
- [ai-video-editing-benchmarks](https://github.com/clipcurator/ai-video-editing-benchmarks)

