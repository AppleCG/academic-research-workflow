---
name: academic-research-workflow
description: 可成长的社科人文研究认知外挂。用research-distiller从学术材料中蒸馏研究框架，用topic-problematization诊断选题，用research-execution诊断执行层，用research-contribution诊断贡献收敛，用research-architecture诊断研究阶段。思考脚手架，非论文生产线。三层四步架构完整。
version: 1.0.0
tags: [research, academic-writing, social-sciences, humanities, workflow, distillation]
---

# 科研诊断工作流 (Academic Research Workflow)

## 定位

这是一个**可成长的社科人文研究认知外挂**，不是论文生产流水线。

它不替你思考，但帮你记住、组织和连接你读过的一切——让你在需要思考时站在更高的起点上。

| 子技能 | 角色 | 做什么 |
|--------|------|--------|
| `research-distiller` | 蒸馏引擎（基石） | 从学术材料中提取研究框架。工作流的所有方法论知识从这里生长 |
| `topic-problematization` | 选题问题化（诊断） | 基于9份权威材料的四步选题框架，诊断选题驱动类型、检验问题质量、辩护选题价值 |
| `research-execution` | 执行层诊断 | 理论推导（从问题到假设结构）→ 方法辩护（为什么用这个方法），文献对话贯穿全程 |
| `research-contribution` | 贡献收敛诊断 | 判断和建构研究贡献：类型定位→六路径建构诊断→Discussion表述→局限真诚性 |
| `research-architecture` | 研究架构（诊断） | 基于蒸馏出的三层四步架构，诊断研究阶段、提出正确的问题 |

**设计哲学**：
- **可成长**：每投喂一份新材料，框架就可能被更新。材料越多，系统越丰富——不是"学得更准"，而是"看到更多变体"
- **思考脚手架，非思考替代品**：架构告诉你"你现在应该问自己什么问题"，但答案必须由你给出
- **不可替代的部分**：conceptualize、"什么值得研究"的判断、学科交界处的直觉——这些留在你的脑子里，工作流不碰

## 触发方式

用户通过以下方式启动子技能：

**调用 research-distiller（蒸馏）**：
- "蒸馏这篇/这些材料"
- "提取这篇论文的研究框架"
- "分析这个学者的论证结构"
- 投喂材料 + 声明蒸馏意图

**调用 topic-problematization（选题）**：
- "我卡在选题了"
- "帮我看看我的研究问题"
- "我的选题有问题吗"
- "怎么判断这个问题好不好"

**调用 research-execution（执行层）**：
- "我确定了选题，接下来怎么设计研究"
- "我的研究问题需要什么方法"
- "怎么论证我选的方法是对的"
- "我的理论推导逻辑有没有问题"

**调用 research-contribution（贡献收敛）**：
- "我觉得论文贡献不够，帮我看看"
- "怎么判断我的研究有没有理论贡献"
- "审稿人说我的Discussion太弱"
- "我的局限写作是不是太模板化了"

**调用 research-architecture（指导）**：
- "帮我看看我的论证结构"
- "我的论文改不下去了"
- "我在研究方法上纠结"

## 首次使用建议

如果你刚接触这个工作流，建议按以下顺序使用：

1. **如果你有想分析的材料** → 先调用 `research-distiller`（"蒸馏这篇材料"），把材料的结构提取出来。这是工作流的知识输入口。
2. **如果你卡在选题** → 调用 `topic-problematization`，它会用四步框架诊断你的研究问题。
3. **如果你确定了选题，不知道怎么做研究设计** → 调用 `research-execution`，它会诊断你的理论推导→方法辩护完整链。
4. **如果你的研究做完了，不确定贡献是否足够** → 调用 `research-contribution`，它会用四步框架诊断你的贡献类型、建构质量、表述有效性和局限真诚性。
5. **如果你不知道卡在哪** → 调用 `research-architecture`，它会先定位你的研究阶段，再引导到对应的深度诊断。
6. **如果你想全面理解一个研究领域** → 先投喂3-5篇该领域的核心材料到 distiller 蒸馏，再考虑是否需要创建新的子技能。

所有子技能不替你写内容——它们给你正确的问题，答案必须由你来给出。

## 子技能间的协作

1. **先蒸馏，后指导**：research-distiller 积累足够的框架后，topic-problematization、research-execution 和 research-contribution 的指导才更充实
2. **指导中发现缺口**：诊断子技能发现某维度缺乏材料支撑 → 触发新一轮蒸馏
3. **横向定位 + 纵向深入**：
   - `research-architecture`（横向广度）——覆盖选题→执行→收敛全流程，帮你定位"现在在哪一步"
   - `topic-problematization`（纵向深度）——专攻第一层（锚定/选题）
   - `research-execution`（纵向深度）——专攻第二层（执行/设计），覆盖理论推导→方法辩护完整链
   - `research-contribution`（纵向深度）——专攻第三层（收敛/贡献），诊断贡献类型→建构→表述→局限
   - 用户说"卡在选题"→ architecture 定位 + problematization 深入；用户说"不知道怎么设计研究"→ architecture 定位 + execution 深入；用户说"不确定贡献够不够"→ architecture 定位 + contribution 深入
4. **蒸馏产出统一记录**：所有蒸馏结果追加到 `compendium.md`，所有子技能共享

## 关键约束

1. 指导建议必须可追溯到蒸馏材料 — "这个标准来自李怀祖的YYY"
2. 不做无来源的普遍性断言
3. 蒸馏前必须声明意图（Step 0）
4. 具体问题具体分析，不套用固定模板
