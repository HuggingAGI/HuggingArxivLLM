# 知识更新无需模型编辑，只需选择性上下文推理

发布时间：2025年03月07日

`LLM应用

理由：这篇论文探讨了如何通过选择性上下文推理（SCR）来更新和优化大型语言模型的知识，属于应用层面的研究，因此归类为LLM应用。` `人工智能` `信息检索`

> Knowledge Updating? No More Model Editing! Just Selective Contextual Reasoning

# 摘要

> # 选择性上下文推理（SCR）

随着真实世界知识的不断演变，大型语言模型（LLMs）的知识库可能会逐渐过时、不完整甚至出现错误。为了解决这一问题，模型编辑作为一种新兴方法应运而生，它能够以极低的计算成本和参数调整代价，对LLMs的知识进行更新。具体而言，模型编辑通过识别并调整与新知识相关的特定模型参数来实现知识更新。然而，现有方法往往低估了参数修改对模型整体知识的潜在负面影响。更为关键的是，经过编辑后的LLMs在多跳推理和持续知识更新方面常常表现不佳。尽管已有诸多研究讨论了这些不足之处，但缺乏全面的评估。

在本文中，我们对十种模型编辑方法从可靠性、泛化性、局部性和可移植性四个维度进行了全面评估。实证结果证实，所有十种流行的模型编辑方法在多个维度上均存在显著不足，表明模型编辑的前景并不乐观。针对这一问题，我们提出了一种名为选择性上下文推理（SCR）的简单而有效的方法，用于知识更新。SCR无需修改模型参数，而是通过利用更新后的知识片段，充分发挥LLM固有的上下文推理能力。具体而言，在SCR框架下，LLM首先评估输入查询是否在外部知识库的范围内。如果是，则将相关外部知识文本进行上下文化处理以增强推理；否则，直接回答查询。

为了验证SCR的有效性，我们采用两个反事实数据集，并结合三种基础LLM，将SCR与十种模型编辑方法进行了对比评估。实证结果证实了上下文推理在知识更新中的有效性和高效性，展示了SCR在实际应用中的巨大潜力。

> As real-world knowledge evolves, the information embedded within large language models (LLMs) can become outdated, inadequate, or erroneous. Model editing has emerged as a prominent approach for updating LLMs' knowledge with minimal computational costs and parameter changes. This approach typically identifies and adjusts specific model parameters associated with newly acquired knowledge. However, existing methods often underestimate the adverse effects that parameter modifications can have on broadly distributed knowledge. More critically, post-edit LLMs frequently struggle with multi-hop reasoning and continuous knowledge updates. Although various studies have discussed these shortcomings, there is a lack of comprehensive evaluation. In this paper, we provide an evaluation of ten model editing methods along four dimensions: reliability, generalization, locality, and portability. Results confirm that all ten popular model editing methods show significant shortcomings across multiple dimensions, suggesting model editing is less promising. We then propose a straightforward method called Selective Contextual Reasoning (SCR), for knowledge updating. SCR does not modify model parameters but harnesses LLM's inherent contextual reasoning capabilities utilizing the updated knowledge pieces. Under SCR, an LLM first assesses whether an incoming query falls within the scope of an external knowledge base. If it does, the relevant external knowledge texts are contextualized to enhance reasoning; otherwise, the query is answered directly. We evaluate SCR against the ten model editing methods on two counterfactual datasets with three backbone LLMs. Empirical results confirm the effectiveness and efficiency of contextual reasoning for knowledge updating.

[Arxiv](https://arxiv.org/abs/2503.05212)