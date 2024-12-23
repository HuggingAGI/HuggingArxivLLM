# 用于少样本对话意图分类的动态标签名称细化

发布时间：2024年12月20日

`LLM应用` `对话系统` `意图分类`

> Dynamic Label Name Refinement for Few-Shot Dialogue Intent Classification

# 摘要

> 对话意图分类旨在明确对话中用户输入的潜在目的或意图。当下的意图分类系统面临诸多重大挑战，主要源于可能的意图繁多以及相似意图类别间存在显著的语义重叠。在本文里，我们借助上下文学习提出了一种针对少样本对话意图分类的新颖方法，融入动态标签细化来应对这些难题。我们的方法从训练集中为测试输入检索相关实例，并借助大型语言模型依据语义理解动态优化意图标签，保证意图相互清晰可辨。实验结果显示，我们的方法有效化解了语义相似意图之间的混淆，相较于基线，在多个数据集上的表现大幅提升。我们还指出，与基线相比，我们的方法生成的意图标签更具可解释性，在捕捉潜在用户意图方面的语义连贯性也更出色。

> Dialogue intent classification aims to identify the underlying purpose or intent of a user's input in a conversation. Current intent classification systems encounter considerable challenges, primarily due to the vast number of possible intents and the significant semantic overlap among similar intent classes. In this paper, we propose a novel approach to few-shot dialogue intent classification through in-context learning, incorporating dynamic label refinement to address these challenges. Our method retrieves relevant examples for a test input from the training set and leverages a large language model to dynamically refine intent labels based on semantic understanding, ensuring that intents are clearly distinguishable from one another. Experimental results demonstrate that our approach effectively resolves confusion between semantically similar intents, resulting in significantly enhanced performance across multiple datasets compared to baselines. We also show that our method generates more interpretable intent labels, and has a better semantic coherence in capturing underlying user intents compared to baselines.

[Arxiv](https://arxiv.org/abs/2412.15603)