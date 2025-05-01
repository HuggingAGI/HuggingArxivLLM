# BiasGuard：专为大型语言模型打造的推理增强型偏见检测工具

发布时间：2025年04月30日

`LLM应用` `机器学习`

> BiasGuard: A Reasoning-enhanced Bias Detection Tool For Large Language Models

# 摘要

> 在确保大型语言模型公平性方面，识别LLM生成内容中的偏见至关重要。现有的公平分类器和基于LLM的判断工具因难以理解潜在意图且缺乏公平性判断标准而存在局限。本文推出了一种名为BiasGuard的新型偏见检测工具，它通过显式分析输入并依据公平性规范进行推理，从而提供精准判断。BiasGuard采用双阶段方法：第一阶段初始化模型，使其基于公平性规范进行显式推理；第二阶段则借助强化学习提升推理和判断能力。我们在五个数据集上的实验表明，BiasGuard不仅提高了准确性，还显著减少了过度公平的误判，展现出优于现有工具的性能。我们还强调了增强推理在决策中的重要性，并通过实验结果验证了双阶段优化管道的有效性。

> Identifying bias in LLM-generated content is a crucial prerequisite for ensuring fairness in LLMs. Existing methods, such as fairness classifiers and LLM-based judges, face limitations related to difficulties in understanding underlying intentions and the lack of criteria for fairness judgment. In this paper, we introduce BiasGuard, a novel bias detection tool that explicitly analyzes inputs and reasons through fairness specifications to provide accurate judgments. BiasGuard is implemented through a two-stage approach: the first stage initializes the model to explicitly reason based on fairness specifications, while the second stage leverages reinforcement learning to enhance its reasoning and judgment capabilities. Our experiments, conducted across five datasets, demonstrate that BiasGuard outperforms existing tools, improving accuracy and reducing over-fairness misjudgments. We also highlight the importance of reasoning-enhanced decision-making and provide evidence for the effectiveness of our two-stage optimization pipeline.

[Arxiv](https://arxiv.org/abs/2504.21299)