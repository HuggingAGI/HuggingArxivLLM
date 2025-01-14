# 当谎言中夹杂真相：嵌入式谎言的自动语言欺骗检测

发布时间：2025年01月13日

`LLM应用

理由：这篇论文主要讨论了如何利用微调的语言模型（Llama-3-8B）来检测言语中的嵌入谎言。虽然涉及到了语言模型的应用，但重点在于如何使用这些模型来解决特定的实际问题（即言语欺骗检测），而不是探讨语言模型的理论基础或构建新的模型架构。因此，将其归类为“LLM应用”是合适的。` `心理学`

> When lies are mostly truthful: automated verbal deception detection for embedded lies

# 摘要

> 背景：言语欺骗检测研究通常假设陈述要么真实要么欺骗，但更现实的视角认为陈述的真实性是一个连续体，真实和欺骗的部分可能共存于同一陈述中。然而，关于嵌入谎言的研究进展缓慢。方法：我们收集了一个包含2,088个真实和欺骗陈述的新数据集，标注了嵌入的谎言。采用受试者内设计，参与者首先提供自传事件的真实描述，然后以欺骗方式重写陈述，嵌入谎言并标注其中心性、欺骗性和来源。结果：微调的语言模型（Llama-3-8B）能以64%的准确率区分真实陈述和包含嵌入谎言的陈述。个体差异、语言属性和可解释性分析表明，嵌入谎言的挑战在于它们与真实陈述的高度相似性。典型的欺骗陈述由2/3的真实信息和1/3的嵌入谎言组成，主要基于个人经历，语言差异极小。结论：我们提供这一数据集作为新资源，推动言语欺骗检测中嵌入谎言的研究。

> Background: Verbal deception detection research relies on narratives and commonly assumes statements as truthful or deceptive. A more realistic perspective acknowledges that the veracity of statements exists on a continuum with truthful and deceptive parts being embedded within the same statement. However, research on embedded lies has been lagging behind. Methods: We collected a novel dataset of 2,088 truthful and deceptive statements with annotated embedded lies. Using a within-subjects design, participants provided a truthful account of an autobiographical event. They then rewrote their statement in a deceptive manner by including embedded lies, which they highlighted afterwards and judged on lie centrality, deceptiveness, and source. Results: We show that a fined-tuned language model (Llama-3-8B) can classify truthful statements and those containing embedded lies with 64% accuracy. Individual differences, linguistic properties and explainability analysis suggest that the challenge of moving the dial towards embedded lies stems from their resemblance to truthful statements. Typical deceptive statements consisted of 2/3 truthful information and 1/3 embedded lies, largely derived from past personal experiences and with minimal linguistic differences with their truthful counterparts. Conclusion: We present this dataset as a novel resource to address this challenge and foster research on embedded lies in verbal deception detection.

[Arxiv](https://arxiv.org/abs/2501.07217)