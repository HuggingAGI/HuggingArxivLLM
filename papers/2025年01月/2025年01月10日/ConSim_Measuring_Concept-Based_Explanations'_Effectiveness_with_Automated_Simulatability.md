# ConSim: 通过自动化模拟评估基于概念的解释效果

发布时间：2025年01月10日

`LLM应用

理由：这篇论文主要讨论了使用大型语言模型（LLMs）作为模拟器来评估基于概念的解释方法。虽然涉及到了LLM的使用，但其核心在于应用LLM来解决解释性评估的问题，而不是探讨LLM的理论基础或构建新的LLM模型。因此，将其归类为“LLM应用”更为合适。` `人工智能` `模型解释`

> ConSim: Measuring Concept-Based Explanations' Effectiveness with Automated Simulatability

# 摘要

> # 摘要
基于概念的解释通过将复杂模型计算映射到人类可理解的概念来实现。评估这类解释颇具挑战，因为它不仅涉及概念空间的质量，还关乎概念如何有效传达给用户。现有评估指标往往只关注前者，忽视了后者。我们提出了一种基于自动可模拟性的评估框架，通过模拟器根据解释预测模型输出的能力来衡量概念解释。这种方法在端到端评估中同时考虑了概念空间及其解释。由于可模拟性的人类研究难以大规模实施，我们建议使用大型语言模型（LLMs）作为模拟器进行近似评估，并通过多种分析确保其可靠性。我们的方法支持跨模型和数据集的扩展性和一致性评估。基于此框架，我们进行了全面的实证评估，结果表明LLMs能够提供解释方法的一致排名。代码已开源：https://github.com/AnonymousConSim/ConSim。

> Concept-based explanations work by mapping complex model computations to human-understandable concepts. Evaluating such explanations is very difficult, as it includes not only the quality of the induced space of possible concepts but also how effectively the chosen concepts are communicated to users. Existing evaluation metrics often focus solely on the former, neglecting the latter. We introduce an evaluation framework for measuring concept explanations via automated simulatability: a simulator's ability to predict the explained model's outputs based on the provided explanations. This approach accounts for both the concept space and its interpretation in an end-to-end evaluation. Human studies for simulatability are notoriously difficult to enact, particularly at the scale of a wide, comprehensive empirical evaluation (which is the subject of this work). We propose using large language models (LLMs) as simulators to approximate the evaluation and report various analyses to make such approximations reliable. Our method allows for scalable and consistent evaluation across various models and datasets. We report a comprehensive empirical evaluation using this framework and show that LLMs provide consistent rankings of explanation methods. Code available at https://github.com/AnonymousConSim/ConSim

[Arxiv](https://arxiv.org/abs/2501.05855)