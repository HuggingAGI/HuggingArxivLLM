# 条件数：神经元单元信息编码的尺度不变代理

发布时间：2025年06月19日

`LLM理论` `机器学习`

> The Condition Number as a Scale-Invariant Proxy for Information Encoding in Neural Units

# 摘要

> 本文从信息论视角探讨了神经网络权重张量的条件数与其处理单元编码信息量之间的关系。我们提出，尽管高条件数并不足以确保有效知识编码，但它可能表明该单元已具备选择性放大和压缩信息的能力。我们对这一直觉进行了形式化推导，特别是在具有高斯输入的线性单元场景下，将条件数和变换的对数体积缩放因子与输出熵特性及学习变换的几何属性建立了联系。分析结果表明，在固定权重范数下，奇异值的集中分布（即高条件数）对应于整体信息传递的减少，这表明了一种专业化且高效的编码策略。此外，我们通过实际案例展示了这些原理在多模态大型语言模型选择性微调中的应用，旨在缓解跨模态适配过程中的灾难性遗忘问题。与众多依赖预训练统计信息（通常不可获取）的现有方法不同，我们的选择性微调策略提供了一种突破这一限制的有效途径。

> This paper explores the relationship between the condition number of a neural network's weight tensor and the extent of information encoded by the associated processing unit, viewed through the lens of information theory. We argue that a high condition number, though not sufficient for effective knowledge encoding, may indicate that the unit has learned to selectively amplify and compress information. We formalize this intuition, particularly for linear units with Gaussian inputs, linking the condition number and the transformation's log-volume scaling factor to the characteristics of the output entropy and the geometric properties of the learned transformation. Our analysis demonstrates that for a fixed weight norm, a concentrated distribution of singular values (high condition number) corresponds to reduced overall information transfer, indicating a specialized and efficient encoding strategy. Furthermore, we present a practical case study where these principles are applied to guide selective fine-tuning of a multimodal Large Language Model, aiming to mitigate catastrophic forgetting during cross-modal adaptation. Unlike many existing catastrophic forgetting mitigation methods that rely on access to pre-training statistics, which are often unavailable, our selective fine-tuning approach offers a way to bypass this common requirement.

[Arxiv](https://arxiv.org/abs/2506.16289)