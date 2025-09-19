# 重声望轻实质：同行评审中大型语言模型偏见的适应性审查

发布时间：2025年09月18日

`LLM应用` `基础理论`

> Prestige over merit: An adapted audit of LLM bias in peer review

# 摘要

> 大型语言模型（LLMs）在学术同行评审中的作用日益关键，尽管多半尚未正式化。但LLMs是否会复刻人类决策中存在的偏见，目前仍不明确。我们将简历式审计模式引入科学出版领域，构建了多角色LLM模拟系统（模拟编辑/审稿人），在随机化作者身份（机构声望、性别、种族）的条件下，对物理、生物、社会科学领域一组具有代表性的高质量论文进行评估。审计结果显示出显著且一致的机构声望偏见：当完全相同的论文被标注为低声望机构作者时，其拒稿风险显著升高，即便LLM对论文质量的评估差异甚微。为探究背后机制，我们为相同作者档案生成了合成简历；这些简历不仅包含与声望相关的巨大差异，还呈现出与全国基准相反的声望-任期梯度。结果表明，一旦作者身份明确，领域规范与训练数据中嵌入的声望相关先验知识便会共同影响论文评审结果，使机构归属成为决定性的地位信号。

> Large language models (LLMs) are playing an increasingly integral, though largely informal, role in scholarly peer review. Yet it remains unclear whether LLMs reproduce the biases observed in human decision-making. We adapt a resume-style audit to scientific publishing, developing a multi-role LLM simulation (editor/reviewer) that evaluates a representative set of high-quality manuscripts across the physical, biological, and social sciences under randomized author identities (institutional prestige, gender, race). The audit reveals a strong and consistent institutional-prestige bias: identical papers attributed to low-prestige affiliations face a significantly higher risk of rejection, despite only modest differences in LLM-assessed quality. To probe mechanisms, we generate synthetic CVs for the same author profiles; these encode large prestige-linked disparities and an inverted prestige-tenure gradient relative to national benchmarks. The results suggest that both domain norms and prestige-linked priors embedded in training data shape paper-level outcomes once identity is visible, converting affiliation into a decisive status cue.

[Arxiv](https://arxiv.org/abs/2509.15122)