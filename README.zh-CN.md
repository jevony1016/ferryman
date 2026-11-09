# ferryman（摆渡人）

[English](README.md) | 简体中文

> 做摆渡人，不做裁判：把事实、规定、推理和选项摆清楚，渡你过河，决定由你来做。

一个用**第一性原理想任何问题**的 agent skill。能用在这些地方：
- 做决定：职业、钱、住哪里、团队怎么管
- 找问题的根因
- 从底层学懂一个主题
- 判断一件事符不符合某条规定
- 起草文书

它还自带一个**临研包**：法规原文、官方术语，以及 SAE、CTCAE 分级、方案偏离、CAPA 这些问题的现成方法。只有问题涉及临床研究时，才会用到临研包。

你用什么语言提问，它就用什么语言回答。

## 一条原则

每个答案都追到它真正依据的东西：看得见的事实、规定的原文、逻辑上的必然，或者你自己的优先级。这些要和经验、共识、权威说法、猜测分开。放到临床研究里，就是分清法规、方案、SOP 和习惯，并且原文照录。

## 四种模式

| 你想…… | 模式 | 临研里的例子 |
|---|---|---|
| 查术语、定义、规定原文 | **查** | “SUSAR 中文怎么写，出自哪里？” |
| 从底层学懂一个主题，或者做练习 | **学** | “我是新 CRC，给我出 3 道 SAE 题” |
| 判断事实符不符合某条规定 | **判** | “这算不算 SAE？”“按 CTCAE v6.0 是几级？” |
| 做决定、解决问题、找根因、写东西 | **做** | “这个 SAE 晚报的 CAPA 怎么写” |

它会自己判断用哪种模式、你是新人还是有经验，并告诉你它是怎么判断的，你可以纠正。

## 它有什么不同

1. **安全优先。** 有需要马上处理的事，比如健康或安全风险、快到期的期限，临研里比如还没报的 SAE，它会先提醒你处理，再做分析。
2. **先了解全貌。** 用苏格拉底式追问，每轮最多三个问题，每个都说明为什么问。追问本身也会挑战“大家都这么做”“规定要求……”“只能这样”这类说法。
3. **找出规定到底写在哪里。** 规定只从看得到的原文里引用，看不到就写“未核实”。方案写的“24 小时内”和法规写的“立即”不是一回事。
4. **先分流。** 会告诉你哪些事照惯常做法就够了，哪些问题其实只需要查一下规定。
5. **按症状选方法。** 四种拆解方法（追问为什么、成本拆解、假设审查、去掉类比）和四种重构方法，全部在硬约束之内使用。
6. **展示前先对抗审查。** 学、判、做三种模式的每次回答，都先交给一个独立子代理审一轮再给你；子代理只看你的原话和草稿。查模式逐字核对原文。审查检查以下几项：
   - 引文和原文是否一致
   - 根因是不是只是一个标签
   - 指标有没有写分母
   - 是否顺着用户说
   - 是否只是在复述常见答案

   宿主不支持子代理时，按清单自审并注明。
7. **把决定交还给你。** 你的价值观由你定，它只帮你把它们说清楚，不替你排序。

“做”模式的流程：

```
0 安全检查 + 了解全貌 → 1 分流 → 2 拆 → 3 建 → 4 验 → 5 对抗审查 → 6 输出报告
```

默认是**报告模式**。说“陪我想”，就切换到**陪想模式**，一步一步来。

## 临研包

`references/regulations/` 里收录的原文，每份都注明了官方来源链接、版本和取得日期：

- **中国**：药物临床试验质量管理规范（2026年修订）；CDE 安全性数据快速报告标准和程序；药品管理法；药品注册管理办法；药物临床试验机构管理规定；涉及人的生命科学和医学研究伦理审查办法（2023）；人类遗传资源管理条例及实施细则。
- **ICH**：E6(R3) 英文全文和 CDE 中文术语表；E2A、E8(R1)、E9、E9(R1)，每份都有中英文。
- **CTCAE**：v6.0 和 v5.0，以及 NCI 官方的 v5.0→v6.0 对照和勘误。
- **美国**：21 CFR 312.3、312.32、312 D 分部、50 B 分部、56 部分、11 部分。
- **欧盟**：(EU) No 536/2014 条例节选（第 1–3、28–35、40–48、52 条和附件 III）。

暂未收录：2026 年修订、2026年5月15日施行的药品管理法实施条例，以及 2020 版 GCP。详见法规目录里的 README。

术语规则见 [references/terminology.md](references/terminology.md)：中文以 2026 版 GCP 正文为准，其次是 CDE 的 E6(R3) 中文术语表；英文以 ICH E6(R3) 术语表为准。

## 安装

**Claude Code**

```bash
git clone https://github.com/jevony1016/ferryman.git
cp -r ferryman ~/.claude/skills/ferryman
```

装好后直接问就行，比如：“用第一性原理帮我想想，这个 offer 要不要接？”或者“这算不算 SAE？”

**其他支持 skill 的 agent**：把文件夹复制到对应的 skills 目录即可。入口是 `SKILL.md`，`references/` 里的文件按需加载。

## 示例

- [examples/general-decision-buy-a-car.zh.md](examples/general-decision-buy-a-car.zh.md)：要不要买车，把“大家都说有了孩子就得买车”拆开看（中文对话，标准档）
- [examples/sae-late-reporting-capa.zh.md](examples/sae-late-reporting-capa.zh.md)：一例被记为“SAE 晚报”、按规定起算点其实不晚的偏差：先核对偏差成不成立，再谈 CAPA（中文对话，标准档）
- [examples/light-triage-follow-up-letter.en.md](examples/light-triage-follow-up-letter.en.md)：分流后直接结束，照模板做就够了（英文对话，轻档）

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
