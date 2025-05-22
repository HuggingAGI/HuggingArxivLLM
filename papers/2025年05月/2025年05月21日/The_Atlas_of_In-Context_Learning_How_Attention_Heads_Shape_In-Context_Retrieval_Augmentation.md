# 上下文学习图谱：注意力头如何影响上下文检索增强机制

发布时间：2025年05月21日

`LLM理论` `问答系统`

> The Atlas of In-Context Learning: How Attention Heads Shape In-Context Retrieval Augmentation

# 摘要

> 大型语言模型通过检索增强实现上下文学习，能够访问超出训练数据的外部知识。尽管这一技术充满潜力，但其内在机制仍不明朗。在本研究中，我们将提示视为信息组件的组合，揭示了上下文检索增强在问答任务中的机制。我们提出了一种基于归因的方法，识别出两类专门的注意力头：一类能够理解指令并检索相关上下文信息，另一类则存储实体间的关系知识。为了深入理解它们的作用机制，我们提取了功能向量并调整了注意力权重，展示了它们对答案生成过程的具体影响。最后，我们利用这些新见解，成功追踪到了推理过程中所使用知识的来源，为构建更加安全、透明的语言模型奠定了基础。

> Large language models are able to exploit in-context learning to access external knowledge beyond their training data through retrieval-augmentation. While promising, its inner workings remain unclear. In this work, we shed light on the mechanism of in-context retrieval augmentation for question answering by viewing a prompt as a composition of informational components. We propose an attribution-based method to identify specialized attention heads, revealing in-context heads that comprehend instructions and retrieve relevant contextual information, and parametric heads that store entities' relational knowledge. To better understand their roles, we extract function vectors and modify their attention weights to show how they can influence the answer generation process. Finally, we leverage the gained insights to trace the sources of knowledge used during inference, paving the way towards more safe and transparent language models.

[Arxiv](https://arxiv.org/abs/2505.15807)