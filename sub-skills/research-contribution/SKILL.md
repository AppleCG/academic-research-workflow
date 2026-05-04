---
name: research-contribution
description: 基于8份权威材料蒸馏的贡献收敛诊断引擎。诊断研究贡献的类型定位、六路径建构质量、Discussion/Conclusion表述有效性、局限真诚性。三层四步第三层——判断"果实是否甜，为何甜，如何更甜"。
version: 1.0.0
parent: academic-research-workflow
tags: [contribution, discussion, conclusion, limitations, theory-building, convergence]
---

# 贡献收敛诊断 (Research Contribution)

## 定位

这是一个**诊断+指导工具**。它基于8份覆盖管理学/医学教育/社会科学方法论的权威材料的深度蒸馏，帮助社科人文研究者在"研究做完了"之后回答四个核心问题：

- **果实有没有价值？** → 你的贡献属于什么类型？在同一类型中够"够"吗？
- **果实的甜度从哪来？** → 你的贡献建构走了哪条路径？有没有掉进常见陷阱？
- **果实的品相好不好？** → 你的Discussion/Conclusion是真诚的对话，还是三大陷阱的受害者？
- **果实的局限是否被如实呈现？** → 你的局限讨论是通过四要素检验，还是三句套话？

**它不是**：
- 贡献自动生成器（好贡献来自你对材料的理解和与文献的对话，不是框架填空）
- "好论文"的固定标准（不同期刊对"贡献"的定义不同，本技能帮你定位而非套用模板）
- 写作模板（不告诉你"结论段应该写三句话"）

所有诊断问题的来源均可追溯到蒸馏材料——你可以验证"这个标准来自谁的哪篇文章"。

## 与其他子技能的关系

`research-contribution` 是 `research-architecture` 三层四步架构中**第三层（收敛）的纵向深度版本**。

```
research-architecture（横向广度）
  ├── 第一层（锚定/选题）→ topic-problematization（纵向深度）
  ├── 第二层（执行/设计）→ research-execution（纵向深度）
  └── 第三层（收敛/贡献）→ research-contribution（纵向深度）← 本技能
```

三层四步架构至此完整——从选题（起点对不对）到执行（过程稳不稳）到收敛（果实有没有价值），三个纵向子技能各覆盖一层，architecture做横向全流程定位。

当用户说"我的论文写完了但不知道贡献够不够"——architecture先定位"你在收敛层"，本技能接着展开完整的贡献诊断链。

## 触发方式

- "我觉得论文贡献不够，帮我看看"
- "怎么判断我的研究有没有理论贡献？"
- "审稿人说我的Discussion太弱，问题在哪？"
- "我的局限写作是不是太模板化了？"
- "怎么把发现写得不像只是复述结果？"
- "我的贡献到底属于哪种类型？"

## 核心框架：四步贡献诊断

> 收敛层回答一个问题：**"我做完了——然后呢？这个研究到底贡献了什么？怎样才算够？怎样让它更好？"** 四个步骤分别诊断贡献的类型、建构质量、表述有效性和局限真诚性。

```
Step A: 贡献类型定位 ─→ 你的贡献属于什么类型？在这个类型下够"够"吗？
    └── 理论推进/现象发现/综述整合/政策对话？目标期刊匹配吗？
         ↓
Step B: 贡献建构诊断 ─→ 六路径自检：你的贡献建构走了哪条路？有没有掉进常见陷阱？
    └── 场景→Why解释→张力→图表→语言→时代——每条对应一个失败模式
         ↓
Step C: Discussion/Conclusion表述诊断 ─→ 三大陷阱+双重结构检查
    └── Rehashing? Meandering? Overreaching? 结构是倒金字塔+沙漏吗？
         ↓
Step D: 局限真诚性检验 ─→ 四要素框架+套话审计
    └── 每个局限有Describe→Implication→Alternative→Mitigation吗？
```

---

## Step A: 贡献类型定位

在做任何诊断之前，先定位你的贡献属于什么类型。不同类型的贡献有不同的达标标准。

### A1: 贡献类型定位

| 贡献类型 | 核心特征 | 你的结论章应该回答 | 适配期刊类型（AOM为例） | 来源 |
|---------|---------|-------------------|----------------------|------|
| **理论推进** | 改变/挑战/从根本上推进了对某一现象的理论理解 | "我们之前以为X，现在知道Y——这改变了什么？" | AMJ, AMR | AMJ Impact Award (2021); Ravasi等(2025) |
| **现象发现** | 描述此前未被识别或未被充分理解的现象，生成初步理论解释 | "原来存在X现象，以前没人描述过——它的机制可能是什么？" | AMD | AOM Journals (2021): "phenomenon-forward" |
| **综述整合** | 对已有研究流进行系统整合，提出未来研究路线图 | "关于X我们知道了什么？还有什么是我们不知道却应该知道的？" | Annals | AOM Journals (2021): "reviews with an attitude" |
| **政策对话** | 将学术发现导向公共/政策讨论 | "X研究对政策制定者意味着什么？" | AMP | AOM Journals (2021): "public interest" |
| **方法创新** | 引入/创新研究方法来揭示此前不可见的东西 | "用了新方法X之后，我们看到了之前看不到的什么？" | 各实证期刊 | Gerring & Seawright (见 compendium 第一层) |

**诊断问题**——如果说不清：

- 能用一句话说清楚"本文的贡献是X类型的Y"吗？→ 说不清说明贡献定位模糊，可能是meandering的前兆
- 如果你投的期刊偏重理论推进，你的结论章是在"推进理论"还是在"描述发现"？→ 如果是后者，贡献类型与期刊不匹配（AOM Journals: "each journal plays a different role... the journals complement one another"）
- 你的贡献是"增量扩展"还是"非增量变革"？→ 不同期刊有不同的阈值（AMJ: "nonincremental changes"; AMD: 现象的新奇性而非理论的新奇性）

### A2: 理论与实践的乘法效应检查

AMJ Impact Award的核心标准：理论与实践的贡献应该是"mutually reinforcing and even exert multiplicative effects on one another"。这个问题值得问：

**诊断问题**：
- 你的理论贡献有没有指向一个可操作的实际后果？→ 如果没有，不等于论文不好，但意味着你可能失去"乘法效应"
- 你的研究发现对实践者/政策制定者意味着什么具体行动？→ 不能只说"有实践意义"，要具体到"X群体应做Y改变"（USC Conclusion: "Recommend a specific course or courses of action"）
- 你是否研究了"被忽视的人群或组织"？→ 不一定是必须的，但AMJ两篇获奖论文都以此为共同特征（AMJ Impact Award: "Approach—Don't Avoid—Studying Overlooked People and Organizations"）

---

## Step B: 贡献建构诊断：六路径自检

Ravasi等(2025)提出的六条路径直接对应六个最常见的贡献建构失败模式。每条路径问一个问题——答不上来说明贡献建构在那个维度有缺口。

### 路径1: Leverage the Unusual —— "你超越了有趣场景吗？"

**常见失败**：论文照亮了一个迷人的背景或群体，但理论抽离不够——读者学到了关于这个场景的很多事，但几乎没有学到能迁移到其他场景的理论洞见。

> "Focusing too much on the context or phenomenon and too little on theory can lead to... applying existing theory to a new sample or context without developing new theoretical insights."（Ravasi等2025）

**诊断问题**：
- 如果你换一个完全不同的场景/样本，你的"理论构件"（boxes）还适用吗？→ 如果答案是否定的，你的结论是context-specific而非theoretical
- 你的研究问题是由**理论困惑**驱动的，还是仅由**场景独特性**驱动的？→ "Why do we need this study? What can we understand now that we could not understand before?"
- 你讨论了你发现的边界条件（boundary conditions）吗？→ 没有讨论=隐含着"适用所有场景"的未辩护主张

**纠正方向**：从场景中抽离→"确保模型中的理论构件是potentially applicable to other settings"；明确讨论"findings在什么条件下可迁移到哪些其他场景"

### 路径2: Leverage Inference —— "你回答了Why吗？"

**常见失败**：论文识别了经验模式（相似性/差异/序列/主题）但没有解释为什么这些模式出现。"Theorizing requires answering the question 'Why?'"（Ravasi等2025）

> "Moving from an observed empirical pattern to a transferable theoretical explanation requires an act of inference... 'the greater the number of alternatives considered simultaneously, the greater the speed of the strategic decision process' — generalization per se, however, is insufficient, unless it is associated with a compelling explanation."（Ravasi等2025）

**诊断问题**——对论文中的每个主要发现，逐个追问：
- 你描述了这个发现（WHAT）——你解释了这个发现为什么会出现吗（WHY）？
- 你的解释是使用了过去时（描述特定语境中的观察）还是**现在时**（做一般化的理论陈述）？→ 过去时→现在时的切换本身就是描述→理论贡献的标记
- 你的推理用了哪种方式：归纳（从观察到概括）、溯因（推断至最佳解释）还是回溯（假定深层机制来解释表面模式）？→ 只做概括而没有任何解释机制 = induction without abduction/retroduction = 不够

**纠正方向**：对每个核心发现追问2-3层"Why"——"因为我们观察到X和Y同时出现"→"为什么同时出现？"→"因为机制M..."→"为什么机制M会在这种条件下运作？"

### 路径3: Leverage Tensions —— "你揭示了张力吗？"

**常见失败**：论文"打开了黑箱"——以动名词标签（gerund-labeled practices）描述了一个过程序列，但没有揭示驱动过程的**张力/矛盾/悖论**。

> "Mapping out ordinary, taken-for-granted sequences of activities that dominate conventional wisdom or everyday experience is unlikely to be enough."（Ravasi等2025）

**诊断问题**：
- 你的过程描述中，存在什么**矛盾**或**悖论**吗？→ 例如：短期vs长期、稳定性vs创新、个体vs集体
- 你研究了不同主体如何**差异性地**应对同一张力吗？→ 这增加variance视角回过程研究，进一步提升理论贡献
- 读者看完你的过程描述，会觉得"这是显然的常识"还是"原来如此，我没这样想过"？→ 前者是"banal regularities"，不够

**纠正方向**："embed the process within a broader theoretical puzzle or base it on some deep-seated and commonly experienced practical tension"

### 路径4: Leverage Visualizations —— "你的箭头被标注了吗？"

**常见失败**：用过程模型图（boxes and arrows）替代理论发展，但箭头未标注、未编码、未解释。Sutton & Staw (1995): "Diagrams are not theory." Weick (1995): "What theory is not, theorizing is."

> "Process models frequently use 'arrows' to connect 'boxes'... but these connections are often unlabeled and underspecified. What do the arrows signify? Is it causal relationships, correlations, enabling conditions, mediating mechanisms, or simply temporal sequences?"（Ravasi等2025）

**诊断问题**：
- 你的模型图中的每根箭头都被**明确标注**了吗？→ 箭头代表什么（因果/相关/使能条件/中介/时间序列）？
- 你是只编码了盒子（主题/类别），还是也编码了箭头（关系/机制）？→ 只编码盒子 = 理论未完成
- 你的图是"为了好看"还是确实揭示了不做图就看不到的东西？→ 前者是装饰，后者是理论化

**纠正方向**：正面标注每根箭头的关系类型；考虑"coding the data for the arrows"而不仅仅是coding for themes；如果线性模型扭曲了现实中的反馈循环和涌现属性，考虑使用系统动力学映射等替代可视化方法。

### 路径5: Leverage Language —— "你的修辞经得起检验吗？"

**常见失败**：三种修辞陷阱——(1)过度最高级（"ground-breaking"），(2)稻草人论证（引最不相关的文献来显得原创），(3)新瓶装旧酒（用新标签包装已有概念）。

> "Just saying so does not make it so. Excessive claims come across as pretentious... as a rule of thumb, authors should seek to be as comprehensive as possible, engaging literatures within management that speak to the relationships and processes they are exploring."（Ravasi等2025）

**诊断问题**：
- **最高级审计**：搜索论文中的最高级词汇（"首次""从根本上""突破性""颠覆"）——每一个都能被具体证据支撑吗？
- **反向文献搜索**：你引的文献是"最有可能让你的初步想法显得多余"的那些吗？还是你有意回避了最相关的文献？→ 后者是稻草人论证（Ravasi等: "look for the literature that has the greatest—rather than the least—possibility of making one's own initial ideas seem redundant"）
- **术语审计**：你引入的新术语/概念是否只是已有概念的重命名？→ 如果有已有术语可以同样准确地描述，新术语就是"old wine in new bottles"

**纠正方向**："Language is the primary tool through which we make our theoretical arguments persuasive, but superficial claiming will not usually pass muster."推荐参考Golden-Biddle & Locke的Composing Qualitative Research——理论故事与经验故事的艺术性交织。

### 路径6: Leverage the Moment —— "你在回应时代吗？"

**常见失败**：仅仅模仿既有优秀研究的框架和话题，但时代变化可能已经使那些框架不完整或需要重新解释。

> "Simply emulating theoretical insights and models from past research, however excellent they may be, might offer a starting point but will probably be insufficient. Arriving at a meaningful theoretical contribution demands reinterpretation, adaptation, extension, synthesis, or innovation of prior theoretical knowledge."（Ravasi等2025）

**诊断问题**：
- 你的研究框架中，哪些继承了既有理论？→ 继承是正当的，但需要检查：
- 你所处的时代/技术/社会环境是否已经使这些理论的某些前提不成立了？→ 如果你不检查这一点，审稿人会检查
- 你的理论贡献是"已有框架在新时代的应用"还是"因新时代而需要对框架本身的修正"？→ 前者是路径1（场景迁移），后者是路径6（重新解释）。两者的理论贡献层次不同。

**纠正方向**：追问"经典理论的盲点在哪里？它们在发展时忽视了什么？它们如何被重新框定以照亮新兴现实？"AI工具可辅助发现人类研究者因学科专精而忽视的跨领域模式，但真正的原创突破仍然需要人的判断。

### B 汇总：六路径速查

| 路径 | 核心问题 | 失败信号 | 来源 |
|------|---------|---------|------|
| 1. Unusual | 你的发现能迁移到其他场景吗？ | 去掉场景后什么都没剩下 | Ravasi等2025 |
| 2. Inference | 你解释了Why，而不只是What？ | 只有概括没有机制 | Ravasi等2025 |
| 3. Tensions | 你揭示了张力/矛盾吗？ | 过程描述"显然是常识" | Ravasi等2025 |
| 4. Visualizations | 你的箭头被标注了吗？ | 模型图只有盒子没有关系 | Ravasi等2025; Sutton & Staw 1995 |
| 5. Language | 你的修辞经得起审计吗？ | 最高级没证据/稻草人/新瓶旧酒 | Ravasi等2025 |
| 6. Moment | 你在回应时代变化吗？ | 完全照搬既有框架的话题和模型 | Ravasi等2025 |

---

## Step C: Discussion/Conclusion表述诊断

### C1: 三大陷阱自检

AMJ Part 6 (Geletkanycz & Tepper, 2012) 和 USC两份指南独立发现了相同的三大问题：

| 陷阱 | 症状 | 你论文中的信号 | 来源 |
|------|------|--------------|------|
| **Rehashing（复述结果）** | Discussion大量复述"我们发现了X显著正相关"而不解释"这意味着什么" | Results段和Discussion段读起来像重复 | AMJ Part 6; USC Discussion: "Don't Write Two Results Sections" |
| **Meandering（漫游）** | Implications分散在多个互不相关的方向上，每个都是点到为止 | 读者看完Discussion记不住你的核心贡献是什么 | AMJ Part 6: "should cohere around a small number of important issues covered in great depth" |
| **Overreaching（过度推演）** | 结论超出了数据能承载的范围，引入Discussion之前从未提过的新理论领域 | 审稿人说"你这些结论从哪里来的" | AMJ Part 6; USC Discussion: "Avoid Unwarranted Speculation" |

**操作建议**（来源：AMJ Part 6）：

> "Instead of identifying implications for each result, they might follow the better strategy of focusing on what the findings mean collectively."

- Rehashing修补：用"bridge sentences"——"In the case of..., the findings suggest that..."然后立即进入解释，不复述数字
- Meandering修补：Discussion写完后做"焦点审计"——所有implications能汇聚到≤3个核心主题吗？每个主题都闭环连接到引言的研究问题了吗？
- Overreaching修补：如果Discussion中出现了引言和理论部分从未提及的理论——要么引入到前面，要么删掉

### C2: 双重结构检查

Discussion/Conclusion需要在"总结已完成"和"打开新可能"之间取得平衡：

| 结构层面 | 应做到 | 来源 |
|---------|--------|------|
| **Ending（结束）** | 回到原始理论动机→兑现对读者的承诺（"answer the underlying theoretical questions"）→综合实证发现为单一融贯的信息 | AMJ Part 6 |
| **New Beginning（新开始）** | 将发现bridge到更大的文献→探索Why而不仅是What→与早期发现对话（分歧=边界条件，一致=精炼理解）→探索替代解释和不支持的假设 | AMJ Part 6 |
| **倒金字塔结构** | General(link to literature) → Specific(your findings) → General(implications) | USC Discussion |
| **沙漏结构** | Introduction: Broad→Specific / Discussion: Specific / Conclusion: Specific→Broad | USC Conclusion |

**诊断问题**——逐项检查你的Discussion/Conclusion：

- Ending检查：
  - 你是否在Discussion开头重新连接了引言中提出的理论问题？→ 没有的话读者不知道"这个讨论在回答哪个问题"
  - 你的讨论是否将多个发现**综合**成了单一融贯的叙事，而非逐一讨论每个假设？→ "weaving them together" vs "discussing each finding separately"
  - 你回答了"So What"吗？→ 不只是"我们发现了X"而是"发现X意味着我们对Y的理解应该改变为..."
- New Beginning检查：
  - 你是否解释了Why，而不只是What/When/How？→ (Geletkanycz & Tepper: "More interesting and valuable are insights that delve deeper... to address the question why")
  - 你是否讨论了你的发现与已有研究的**差异**（如果有）？→ 差异=边界条件/假设问题/遗漏变量的机会
  - 不支持的假设是否被当作信息来讨论（而非被悄悄删除）？→ "the failure to find rigorous support for key theoretical arguments is in itself informative"
  - 你是否考虑了替代解释（alternative explanations）？→ (USC Discussion: "the purpose of research... is to discover and not to prove")
- 结构检查：
  - 你的Conclusion是"综合性关键点"还是"Discussion的摘要"？→ 后者是"Belabor the Obvious"（USC Conclusion）
  - 你的Conclusion引入了新信息吗？→ "New Insight, Not New Information!"（USC Conclusion）
  - 你的Conclusion有"take-home message"吗？→ 一句读者离开了还能记住的精炼宣言

### C3: 两种特殊情况

**意外发现（unexpected findings）**：
- USC Discussion: 应该"begin by highlighting the implications of a particularly unexpected or significant finding"——意外发现可以成为Discussion中读者最感兴趣的部分
- 解释意外发现时：描述→解释为什么你认为它出现了→它在整体研究中的可能意义

**不支持的假设（unsupported hypotheses）**：
- AMJ Part 6: "the failure to find rigorous support for key theoretical arguments is in itself informative and rather thought-provoking"——不要悄悄删除
- 追问：(1)理论逻辑有问题？(2)测量有问题？(3)发现了边界条件？(4)有一个隐藏的调节变量？

---

## Step D: 局限真诚性检验

### D1: 四要素框架

局限写作的核心问题是"只列不释"——大多数作者只做了第1步。

> "Too often, authors only list the potential limitations, without including these other important elements."（Ross & Zaidi, 2019）

**四要素完整操作链**（Ross & Zaidi 2019 + AJE 2023 独立收敛）：

| 要素 | 操作 | 你的局限段有没有？ |
|------|------|-------------------|
| **1. Describe** | 识别局限类型（study design / data collection / data analysis / study results）+ 指明具体来源 | ☐ |
| **2. Explain Implication** | 这个局限如何影响结果和结论？对internal/external validity的具体威胁是什么？影响的可能性/量级？ | ☐ |
| **3. Provide Alternative** | 其他研究用了什么替代方法可以克服这个局限？为什么当时没采用？→ "This information is valuable coming from the researcher because of the direct, relevant experience and insight gained as they conducted the study" | ☐ |
| **4. Describe Mitigation** | 你已经采取了什么步骤来减轻这个局限？→ "No research design is perfect and free from explicit and implicit biases; however various methods can be employed to minimize the impact" | ☐ |

**逐条自检**：对论文中的每一个局限声明，问——

- 我描述了它是什么（不只是标签）？☐
- 我解释了它为什么重要、可能如何影响结论？☐
- 我提供了可能的替代方法/解释吗？☐
- 我描述了我已经采取的缓解措施吗？☐

四项缺任何一项 → 局限讨论在那个点上不完整。

### D2: 套话审计

**三板斧黑名单**（Ross & Zaidi 2019: "growing list of generic and overused limitations"）：
- "样本量较小"
- "单一机构研究"
- "使用自报告数据"
- "横截面设计"

这些本身不一定是坏局限——但如果你只写了这几个短语而不做D1的四步展开，它们是空洞的。

**诊断问题**：
- 你的局限段中，是否出现了黑名单中的任何一条？→ 如果是，你有没有用四要素解释"为什么这确实是我的研究的具体问题"？
- 删掉你的局限段，论文的credibility会变化吗？→ 如果不会，说明你的局限段是装饰性文本，没有实际功能
- 你的局限讨论是否只说了"缺了什么"而没说"这意味着什么"和"该怎么办"？→ 如果是，读者得到了什么？

### D3: 心态转换

局限写作最关键的可能不是技巧，而是心态：

> "The quality and rigor of our research is largely defined by our limitations."（Ross & Zaidi 2019）

> "proper framing and presentation of limitations can actually increase the likelihood of acceptance."（Ross & Zaidi 2019, 引用Bordage 2001: "one of the top reasons reviewers report recommending acceptance... involves limitations—specifically how the study's interpretation accounts for its limitations"）

**诊断问题**：
- 你是带着"赶紧应付过去"的心态写局限段，还是带着"这一段可以展示我的学术严谨性"的心态？→ 读者能看出来
- 你的局限段让读者想要做后续研究吗？→ "Study limitations should leave the reader thinking about opportunities to engage in prospective improvements"（Ross & Zaidi 2019）
- 你的结论段的语气是"道歉"还是"自信地限定"？→ USC Conclusion: "Resist the urge to apologize. Don't undermine your authority as a researcher"

### D4: 局限→未来研究转化

局限不是终点，而是下一轮研究的起点。AJE (2023) 和 Ross & Zaidi (2019) 都强调：

> "To spark the interest of other researchers, these acknowledgements must come with thorough explanations regarding how the limitations affected the current study and how they can potentially be overcome with amended methods."（AJE 2023）

**诊断问题**：
- 你的每个主要局限是否与至少一个"未来研究可以如何解决它"的具体建议配对？
- 这些建议是否足够具体（"future research should use a larger sample" = 不够具体；"future research should replicate in industry X with Y control variable to test whether Z boundary condition holds" = 具体）？
- 你的"未来研究方向"是否只是局限的反射（"我缺了X，所以未来应该做X"），还是在此基础上提出了新的理论问题？

---

## 诊断汇总：贡献四步快检表

| 步骤 | 如果答不上来 | 参考来源 |
|------|-------------|---------|
| A. 你的贡献是什么类型？与目标期刊匹配吗？ | 贡献类型模糊 → 先去读目标期刊的mission statement | AOM Journals (2021); AMJ Impact Award (2021) |
| B1. 去掉场景后你的理论还成立吗？ | 你的贡献是场景描述而非理论抽离 | Ravasi等2025 路径1 |
| B2. 你的每个发现都追问了"Why"吗？ | 你的贡献停留在模式识别而非解释 | Ravasi等2025 路径2 |
| B3. 你揭示了什么张力/矛盾吗？ | 你的贡献可能是常识的翻新 | Ravasi等2025 路径3 |
| B4. 你的每个箭头都被标注了吗？ | 你的可视化是装饰而非理论化工具 | Ravasi等2025 路径4; Sutton & Staw 1995 |
| B5. 你的最高级经得起证据支撑吗？你引了最难对话的文献吗？ | 你可能犯了夸大/稻草人/新瓶旧酒 | Ravasi等2025 路径5 |
| B6. 时代变化使你的理论前提更相关还是更过时？ | 你可能在模仿既有研究而非推进 | Ravasi等2025 路径6 |
| C. Discussion是综合的≤3个核心含义还是每个发现一个implication？ | Meandering → 做焦点审计，浓缩到≤3个 | AMJ Part 6 (2012) |
| C. Discussion中是否出现了引言从未提过的新理论？ | Overreaching → 删除或引入到前面 | AMJ Part 6 (2012); USC Discussion |
| C. Discussion是否大量复述Results内容？ | Rehashing → 用bridge sentences + 立即进入解释 | AMJ Part 6 (2012); USC Discussion |
| D. 每个局限都有四要素吗？ | 平板局限 → 逐条补充Implication/Alternative/Mitigation | Ross & Zaidi (2019); AJE (2023) |
| D. 你的局限段出现了"三板斧"吗？ | 如果只有标签没有展开 → 要么展开，要么删除 | Ross & Zaidi (2019) |

---

## 跨方法参数

| 维度 | 定量研究 | 定性研究 | 混合方法 |
|------|---------|---------|---------|
| **贡献类型侧重** | 理论检验+边界条件发现 | 理论建构+机制揭示（Ravasi等2025: "elevated expectations for novelty"） | 多维度贡献（不同部分贡献不同类型） |
| **Why的追问方式** | 为什么这个因果关系成立？潜在机制是什么？替代解释是什么？ | 为什么这个过程如此展开？什么机制驱动了它？ | Why需同时在统计和过程两个层面回答 |
| **常见局限** | 内部效度/外部效度/测量/内生性 | 可迁移性/研究者偏见/理论饱和度 | 整合逻辑/不同范式的范式间张力 |
| **Discussion表述特色** | "These findings challenge/extend theory X by showing..." — 明确与假设对话 | "These findings reveal that..." — 从具体语境向一般理论抽象（过去时→现在时切换） | 需同时处理不同部分的贡献+整合层面的贡献 |
| **局限→未来** | 替代解释→新变量→新设计 | 边界条件→多案例比较→不同语境检验 | 方法论创新→改进整合策略 |

---

## 关键提醒

1. **贡献不是"越多越好"**：2-3个深度覆盖的核心implications > 10个表面提及。AMJ Part 6明确警告meandering——"a small number of important issues that are covered in great depth"。

2. **"Why"是你最重要的单词**：从Step B路径2到Step C的New Beginning，几乎所有诊断都回到同一个问题——你解释了为什么吗？Ravasi等(2025)的时态切换（过去时→现在时）是最简单的自检操作。

3. **局限是质量标志，不是缺陷清单**：Ross & Zaidi (2019) 的反常识发现——"proper framing and presentation of limitations can actually increase the likelihood of acceptance"。心态从"赶紧应付"转为"展示严谨性"，文本会完全不同。

4. **不同期刊定义不同的"贡献"**：AOM Journals (2021) 用同一个"identity"研究在六种期刊的六种不同贡献类型，说明了"贡献"不是单一的gold standard——先定位类型，再按类型诊断质量。

5. **收敛层的质量取决于前三步**：architecture已经指出"收敛层最容易被空洞化"——真正区分论文质量的在锚定和执行层，不在结论的修辞（来源：综合推断自陆铭+三层结构+王汎森）。好Conclusion无法挽救坏研究发现。但如果前两步扎实而第三步掉链子，好的研究也会被低估。

---

## 与其他子技能的协作

- **与 topic-problematization**：选题阶段的"驱动类型定位"和"问题差异性检验"→直接决定了贡献类型(A)的选择范围——选题时的问题意识已经隐含了可能的贡献路径
- **与 research-execution**：执行层的"理论推导(A1-A4)"和"方法辩护(C1-C3)"→决定了结论能否通过六路径(B)诊断——如果执行层的理论推导不充分(没有解释Why)，收敛层不可能凭空产生解释力
- **与 research-architecture**：当用户说"论文改不下去了"或"不知道贡献够不够"→architecture先横向定位(在收敛层)，本技能接着纵向深入(用四步诊断)
