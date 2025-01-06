# 你能有多毒？基于搜索的LLM毒性测试

发布时间：2025年01月03日

`LLM应用

理由：这篇论文主要讨论了一个自动化测试框架EvoTox，用于评估大型语言模型（LLMs）的毒性倾向。该框架通过迭代进化策略和两个LLM的互动来检测LLM生成有害回应的程度。虽然涉及LLM的对齐和伦理标准，但核心内容是关于如何应用LLM来检测和评估其生成内容的毒性，因此属于LLM应用的范畴。` `人工智能`

> How Toxic Can You Get? Search-based Toxicity Testing for Large Language Models

# 摘要

> # 摘要
语言是刻板印象和歧视的深层传播工具。如今，大型语言模型（LLMs）已渗透到我们的日常生活中，一旦生成有害回应，便可能造成广泛伤害。尽管通过对齐LLM可以缓解这一问题，但这并非根治之策。因此，即使在对齐后，测试LLM以检测其与伦理标准的偏差仍至关重要。我们推出了EvoTox，一个自动化测试框架，用于评估LLM的毒性倾向，即使在存在对齐的情况下，也能定量衡量LLM被推向有害回应的程度。该框架采用迭代进化策略，利用两个LLM的互动——被测系统（SUT）和引导SUT生成更高毒性回应的提示生成器。毒性水平由基于现有毒性分类器的自动化oracle评估。我们使用四个复杂度递增（7-130亿参数）的先进LLM进行了定量和定性评估。定量评估比较了EvoTox的四个版本与基线方法（如随机搜索、有害提示数据集和对抗性攻击）的成本效益。定性评估则邀请人类评估者对生成提示的流畅性和测试过程中收集的回应的毒性进行评分。结果显示，EvoTox在检测毒性水平上的有效性显著高于基线方法（与随机搜索相比，效应大小高达1.0；与对抗性攻击相比，效应大小高达0.99），且成本开销有限（平均22%-35%）。

> Language is a deep-rooted means of perpetration of stereotypes and discrimination. Large Language Models (LLMs), now a pervasive technology in our everyday lives, can cause extensive harm when prone to generating toxic responses. The standard way to address this issue is to align the LLM, which, however, dampens the issue without constituting a definitive solution. Therefore, testing LLM even after alignment efforts remains crucial for detecting any residual deviations with respect to ethical standards. We present EvoTox, an automated testing framework for LLMs' inclination to toxicity, providing a way to quantitatively assess how much LLMs can be pushed towards toxic responses even in the presence of alignment. The framework adopts an iterative evolution strategy that exploits the interplay between two LLMs, the System Under Test (SUT) and the Prompt Generator steering SUT responses toward higher toxicity. The toxicity level is assessed by an automated oracle based on an existing toxicity classifier. We conduct a quantitative and qualitative empirical evaluation using four state-of-the-art LLMs as evaluation subjects having increasing complexity (7-13 billion parameters). Our quantitative evaluation assesses the cost-effectiveness of four alternative versions of EvoTox against existing baseline methods, based on random search, curated datasets of toxic prompts, and adversarial attacks. Our qualitative assessment engages human evaluators to rate the fluency of the generated prompts and the perceived toxicity of the responses collected during the testing sessions. Results indicate that the effectiveness, in terms of detected toxicity level, is significantly higher than the selected baseline methods (effect size up to 1.0 against random search and up to 0.99 against adversarial attacks). Furthermore, EvoTox yields a limited cost overhead (from 22% to 35% on average).

[Arxiv](https://arxiv.org/abs/2501.01741)