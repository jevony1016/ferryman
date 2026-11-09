<div align="center">

# ⛵ ferryman · 摆渡人

**做摆渡人，不做裁判。**<br>
一个给 AI agent 用的第一性原理思考 skill：把事实、规定、推理和选项摆清楚，渡你过河，决定由你来做。

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
![Agent Skill](https://img.shields.io/badge/agent-skill-8A2BE2)
![Claude Code](https://img.shields.io/badge/Claude_Code-ready-D97757)
![Any language](https://img.shields.io/badge/replies_in-your_language-2EA44F)

[English](README.md) | 简体中文

</div>

---

## 为什么做它

很多糟糕的答案，不管出自人还是 AI，问题不在推理，而在起点：把习惯当成规定，把听说当成事实，把别人的处境当成自己的，把“大家都这么说”当成证据。

ferryman 让 AI 反过来做：**每个答案都追到它真正依据的东西。**

| 依据 | 例子 |
|---|---|
| 看得见的事实 | 对方给你的报价、日志里的日期 |
| 规定的原文 | 合同里的那一条、法规里的那一款 |
| 逻辑上的必然 | 上面这些成立时，必然推出什么 |
| 你自己的优先级 | 你在乎什么，只有你能说 |

其余的（经验、共识、权威说法、猜测）都会标出来，用之前先核查。

## 能问什么

| 模式 | 你想…… | 比如 |
|---|---|---|
| 🔍 **查** | 查术语、定义、原文 | “我合同里关于离职通知期的那条，原文到底怎么写？” |
| 📚 **学** | 从底层学懂一件事，再做练习 | “从头给我讲复利，讲完出几道题。” |
| ⚖️ **判** | 判断事实符不符合某条规定或标准 | “按公布的条件，我能不能申请这项补贴？” |
| 🛠️ **做** | 做决定、解决问题、找根因、写东西 | “这个 offer 要不要接？”“我们的周报为什么总是晚交？”“帮我起草一封投诉邮件。” |

它会自己判断用哪种模式、你是新手还是有经验，告诉你它的判断，你可以纠正。

## 它怎么想

```
0  安全检查 + 了解全貌   ← 苏格拉底式追问，每轮最多 3 个，每个都说明为什么问
1  分流                 ← 这件事值得深入分析吗？
2  拆                   ← 每个前提依据的是什么？
3  建                   ← 在硬约束之内给出 2–3 个选项
4  验                   ← 推理链、失败条件、最小试验
5  对抗审查             ← 一个独立审查者专门挑草稿的毛病
6  输出报告             ← 决定交还给你
```

- **先问再答。** 信息不全就先追问，追问本身也会挑战“大家都这么做”“规定要求……”“只能这样”。
- **知道什么时候停。** 照惯常做法就够的事，它会直说并停下。不是什么事都需要第一性原理。
- **按症状选方法。** 四种拆解方法（追问为什么、成本拆解、假设审查、去掉类比）和四种重构方法。
- **只引原文，不凭记忆转述。** 规定只从看得到的原文里引用，看不到就写“未核实”，并告诉你去哪里查。
- **给你看之前先自审。** 学、判、做的每次回答，都先交给一个独立子代理审一轮；子代理只看你的原话和草稿。重点找：编造的事实、只是标签的根因（比如“意识不足”）、没有分母的指标、顺着你说、往最常见的答案上靠。
- **价值观由你定。** 它把你的优先级说清楚，并告诉你优先级不同时答案怎么变（“如果你更看重 A……如果更看重 B……”），从不替你排序。

默认是**报告模式**。说“陪我想”，就切换到**陪想模式**，一步一步来。

## 看个例子

> **你**：用第一性原理帮我想想，要不要买车？大家都说有了孩子就得买车。
>
> **ferryman**：先问三个问题，答案会直接改变结论：这辆车主要用在哪些出行上，每周几次、多远？这些出行现在怎么解决，每次花多少？有没有停车位、预算这类硬限制？
>
> *……你回答之后……*
>
> “大家都说”被标为**共识**，先放一边；每周末 4 段出行才是真正的需求。按你给的数，光车位一项就相当于现在每月打车花费的七成左右，这还没算保险和折旧（它请你按车型自己查，而不是替你估）。然后给出三个选项、反对自己建议的最强理由、一个两三个月的低成本试验，最后：*如果你更看重花费和灵活……如果更看重带孩子随时能走……*

完整对话：[examples/general-decision-buy-a-car.zh.md](examples/general-decision-buy-a-car.zh.md)

## 安装

**Claude Code**

```bash
git clone https://github.com/jevony1016/ferryman.git ~/.claude/skills/ferryman
```

装好后直接问：*“用第一性原理帮我想想……”*、*“帮我决定……”*、*“从底层给我讲讲……”*、*“给我出几道……的题”*。

**其他支持 skill 的 agent**：把文件夹复制到对应的 skills 目录即可。入口是 `SKILL.md`，`references/` 里的文件按需加载。

## 🧪 附带：临研包

作者在临床研究行业工作，所以 ferryman 自带一个临研包。**只有问题涉及临床试验时才会用到**：

- **法规原文照录**，每份都注明官方来源链接、版本和取得日期：2026 版 GCP 和 NMPA 核心法规、ICH E6(R3) / E2A / E8(R1) / E9 / E9(R1)、CTCAE v6.0 和 v5.0、21 CFR、欧盟临床试验条例。
- **官方术语**，中英对照，包括旧术语 → 现行术语。
- **现成方法**：算不算 SAE、CTCAE 几级、是不是重要方案偏离、报告时限怎么起算、CAPA、监查报告。

可以这样问：*“这算不算 SAE？”*、*“血红蛋白 7.5 g/dL，按 CTCAE v6.0 是几级？”*、*“我是新 CRC，给我出 3 道 SAE 题”*、*“这个 SAE 晚报的 CAPA 怎么写？”*

<details>
<summary>临研包里有什么</summary>

- **中国**：药物临床试验质量管理规范（2026年修订）；CDE 安全性数据快速报告标准和程序；药品管理法；药品注册管理办法；药物临床试验机构管理规定；涉及人的生命科学和医学研究伦理审查办法（2023）；人类遗传资源管理条例及实施细则。
- **ICH**：E6(R3) 英文全文和 CDE 中文术语表；E2A、E8(R1)、E9、E9(R1)，每份都有中英文。
- **CTCAE**：v6.0 和 v5.0，以及 NCI 官方的 v5.0→v6.0 对照和勘误。
- **美国**：21 CFR 312.3、312.32、312 D 分部、50 B 分部、56 部分、11 部分。
- **欧盟**：(EU) No 536/2014 条例节选（第 1–3、28–35、40–48、52 条和附件 III）。

暂未收录：2026 年修订、2026年5月15日施行的药品管理法实施条例，以及 2020 版 GCP。详见 [references/regulations/README.md](references/regulations/README.md)。

</details>

## 仓库结构

<details>
<summary>文件</summary>

```
SKILL.md                                 入口：安全检查、领域判断、模式、水平、共用规则
references/modes/                        lookup.md · learn.md · judge.md · do.md（查 · 学 · 判 · 做）
references/socratic-questioning.md       怎么追问；问题库
references/decomposition-methods.md      四种拆解方法
references/rebuilding-methods.md         四种重构方法
references/adversarial-review.md         审查清单
references/value-decisions.md            职业、家庭等价值类决定
references/report-template.md            输出结构
references/clinical-research.md          临研包：硬约束、规定层级、CAPA、隐私
references/terminology.md                临研包：中英文官方术语
references/regulations/                  临研包：法规原文
examples/general-decision-buy-a-car.zh.md     日常决定：把“大家都说”拆开看（中文）
examples/sae-late-reporting-capa.zh.md        一例记为“晚报”、其实不晚的 SAE（中文）
examples/light-triage-follow-up-letter.en.md  分流结论：不需要深入分析（英文）
```

</details>

## 出处与致谢

**思维方法**提炼自两本讲第一性原理的中文书，全部用我自己的话重写，没有转载原文：

- 武从文《第一性原理：普通人的人生高效手册》（2026）：拆解四法、重构四法、三条判定标准、五大常见陷阱，以及什么时候不值得投入分析。
- 李善友《第一性原理》（人民邮电出版社，2021）：归纳法和演绎法的隐含假设、从众效应，以及逻辑三洽（自洽、他洽、续洽）。

**法规和指导原则**：`references/regulations/` 里的文本从官方来源原样照录，以官方发布版本为准。各文件里附有转载条款原文：

- ICH 指南：按 ICH 的声明转载，声明附在各 ICH 文件里。
- CTCAE：由美国国家癌症研究所（NCI）发布。来源：[NCI DCTD, CTCAE and Adverse Event Reporting](https://dctd.cancer.gov/research/ctep-trials/for-sites/adverse-events)。
- 欧盟 536/2014 条例：Source: EUR-Lex, https://eur-lex.europa.eu, © European Union, 1998–2026。
- 21 CFR：美国政府作品，取自 eCFR。
- 中国法律法规和官方文件：取自各发布机关网站。

设计上还参考了这些开源 skill：[awesome-skills/first-principles-skill](https://github.com/awesome-skills/first-principles-skill)、[huangmingche/first-principles-skill](https://github.com/huangmingche/first-principles-skill)、[jiaosl/first-principles-reasoning-skill](https://github.com/jiaosl/first-principles-reasoning-skill)、[swapnildahiphale/first-principles-thinking-skill](https://github.com/swapnildahiphale/first-principles-thinking-skill)、[reshadat/first-principles-destructor](https://github.com/reshadat/first-principles-destructor)。

本项目与上述书籍的作者和出版社、监管机构、ICH、NCI、欧盟以及任何雇主均无关联。

## 免责声明

本 skill 只提供思考和决策辅助，不构成医学、法律、财务或法规意见。在临床研究中，请遵守你的试验方案、SOP 和适用法规；最终解释以申办者、QA、伦理审查委员会或监管机构为准。请勿输入任何能识别试验参与者或他人身份的信息。

## 许可

skill 本身的文字采用 [MIT](LICENSE) 许可。`references/regulations/` 里的法规和指导原则文本保留其原有的法律地位和使用条款，详见各文件说明。
