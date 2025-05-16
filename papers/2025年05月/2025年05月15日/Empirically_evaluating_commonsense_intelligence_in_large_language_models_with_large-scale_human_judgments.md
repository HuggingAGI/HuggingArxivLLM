# 实证评估大型语言模型的常识推理能力，基于大规模人工判断。

发布时间：2025年05月15日

`LLM理论` `人工智能` `认知科学`

> Empirically evaluating commonsense intelligence in large language models with large-scale human judgments

# 摘要

> # 摘要
机器常识推理能力的评估通常依赖静态基准测试，这些测试将模型输出与人类预先设定的正确标签进行对比。这些标签隐含着一个关键假设：它们准确反映了所有人类的共同认知，即将人类常识视为同质化的。然而，实证研究表明，人类对常识的判断存在显著差异；一个基准设计者认为显而易见的内容，可能并不为其他人所认同。针对大型语言模型（LLMs）的常识推理能力，我们提出了一种新型评估方法，该方法通过测量模型判断与整个人类群体判断的一致性，纳入了人类之间实证观察到的异质性。研究发现，当将大部分LLMs视为独立的调查对象时，它们的常识推理能力普遍低于人类中位数。而当将LLMs用作假设人群的模拟器时，它们与真实人类在对同一组陈述的认同程度上仅存在适度的相关性。值得注意的是，较小规模的开源模型在上述两种情境下均表现优于更大规模的专有前沿模型。我们的评估框架通过将常识推理能力与其文化基础相联系，为适应具备不同、常常相互矛盾的社会知识储备的人类群体的AI模型开发提供了有力支持。


> Commonsense intelligence in machines is often assessed by static benchmarks that compare a model's output against human-prescribed correct labels. An important, albeit implicit, assumption of these labels is that they accurately capture what any human would think, effectively treating human common sense as homogeneous. However, recent empirical work has shown that humans vary enormously in what they consider commonsensical; thus what appears self-evident to one benchmark designer may not be so to another. Here, we propose a novel method for evaluating common sense in artificial intelligence (AI), specifically in large language models (LLMs), that incorporates empirically observed heterogeneity among humans by measuring the correspondence between a model's judgment and that of a human population. We first find that, when treated as independent survey respondents, most LLMs remain below the human median in their individual commonsense competence. Second, when used as simulators of a hypothetical population, LLMs correlate with real humans only modestly in the extent to which they agree on the same set of statements. In both cases, smaller, open-weight models are surprisingly more competitive than larger, proprietary frontier models. Our evaluation framework, which ties commonsense intelligence to its cultural basis, contributes to the growing call for adapting AI models to human collectivities that possess different, often incompatible, social stocks of knowledge.

[Arxiv](https://arxiv.org/abs/2505.10309)