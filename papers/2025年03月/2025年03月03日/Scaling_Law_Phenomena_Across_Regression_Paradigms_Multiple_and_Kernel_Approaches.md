# 多变量与核方法：跨越回归范式的缩放法则现象

发布时间：2025年03月03日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的成功背后的缩放定律，分析了模型大小、数据集规模和训练计算量之间的幂律关系，挑战了传统机器学习的原理，并扩展了缩放定律到更广泛的回归设置。这些内容属于对LLMs内在机制和理论基础的研究，因此归类为LLM理论。` `人工智能` `计算科学`

> Scaling Law Phenomena Across Regression Paradigms: Multiple and Kernel Approaches

# 摘要

> 大型语言模型 (LLMs) 近期取得了显著的成功，而 OpenAI 发现的缩放定律正是这一成功的关键。对于采用 Transformer 架构的模型，测试损失与模型大小、数据集规模及训练计算量之间呈现出跨越七个数量级的幂律关系。这一发现挑战了传统机器学习中的奥斯卡剪刀原则，该原则认为过参数化模型会在训练数据上过拟合，从而导致测试性能下降。有趣的是，缩放定律不仅存在于复杂的模型中，还在简单的线性回归场景中被发现。然而，完全解释大型模型中的缩放定律仍是未解之谜。本研究通过扩展缩放定律到更具表现力的多重回归和核回归设置，进一步揭示了这一现象的本质，为理解 LLMs 提供了新的视角。

> Recently, Large Language Models (LLMs) have achieved remarkable success. A key factor behind this success is the scaling law observed by OpenAI. Specifically, for models with Transformer architecture, the test loss exhibits a power-law relationship with model size, dataset size, and the amount of computation used in training, demonstrating trends that span more than seven orders of magnitude. This scaling law challenges traditional machine learning wisdom, notably the Oscar Scissors principle, which suggests that an overparametrized algorithm will overfit the training datasets, resulting in poor test performance. Recent research has also identified the scaling law in simpler machine learning contexts, such as linear regression. However, fully explaining the scaling law in large practical models remains an elusive goal. In this work, we advance our understanding by demonstrating that the scaling law phenomenon extends to multiple regression and kernel regression settings, which are significantly more expressive and powerful than linear methods. Our analysis provides deeper insights into the scaling law, potentially enhancing our understanding of LLMs.

[Arxiv](https://arxiv.org/abs/2503.01314)