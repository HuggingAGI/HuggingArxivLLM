# 脆弱的偏好：大型语言模型中的顺序效应深度探究

发布时间：2025年06月16日

`LLM应用`

> Fragile Preferences: A Deep Dive Into Order Effects in Large Language Models

# 摘要

> 大型语言模型（LLMs）在招聘、大学录取等高风险领域的决策支持系统中得到了广泛应用，这些系统通常需要在多个选项中做出选择。尽管之前的研究已经注意到LLMs在比较任务中存在位置顺序偏差，但这些偏差尚未被系统分析或与潜在的偏好结构联系起来。我们首次对多个LLM架构和领域的定位偏差进行了全面研究，揭示了强烈且一致的顺序效应，包括一种此前未在人类或机器决策中记录的新型中心偏见。我们还发现，当选项质量较高时，模型表现出首因效应；而当选项质量较低时，模型更倾向于选择后面的选项。此外，我们发现了一种此前未被记录的偏见，即模型更偏好某些名字。为了区分表面的平局打破和真正的判断扭曲，我们引入了一个框架，将配对偏好分类为稳健、脆弱或无差异。研究表明，顺序效应可能导致模型选择严格较差的选项，并且位置偏差通常比性别偏见更强。这些发现表明，LLMs不仅继承了类似人类的偏见，还表现出人类决策中未见的独特失败模式。我们提出了针对性的缓解策略，包括温度参数的新用法，以减少由顺序驱动的扭曲。

> Large language models (LLMs) are increasingly used in decision-support systems across high-stakes domains such as hiring and university admissions, where decisions often involve selecting among competing alternatives. While prior work has noted positional order biases in LLM-driven comparisons, these biases have not been systematically dissected or linked to underlying preference structures. We provide the first comprehensive investigation of positional biases across multiple LLM architectures and domains, uncovering strong and consistent order effects, including a novel centrality bias not previously documented in human or machine decision-making. We also find a quality-dependent shift: when options are high quality, models exhibit primacy bias, but favor latter options when option quality is low. We further identify a previously undocumented bias favoring certain names over others. To distinguish superficial tie-breaking from true distortions of judgment, we introduce a framework that classifies pairwise preferences as robust, fragile, or indifferent. We show that order effects can lead models to select strictly inferior options, and that positional biases are typically stronger than gender biases. These findings suggest that LLMs are not merely inheriting human-like biases, but exhibit distinct failure modes not seen in human decision-making. We propose targeted mitigation strategies, including a novel use of the temperature parameter, to reduce order-driven distortions.

[Arxiv](https://arxiv.org/abs/2506.14092)