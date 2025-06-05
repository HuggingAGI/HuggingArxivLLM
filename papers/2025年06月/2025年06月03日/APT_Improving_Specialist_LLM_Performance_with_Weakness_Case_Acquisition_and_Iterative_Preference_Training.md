# APT: 利用弱点案例采集与迭代偏好训练优化专家型大语言模型的表现

发布时间：2025年06月03日

`LLM应用` `大规模语言模型` `领域适应`

> APT: Improving Specialist LLM Performance with Weakness Case Acquisition and Iterative Preference Training

# 摘要

> 大规模语言模型（LLMs）在处理特定任务时通常需要进行领域特定的微调，但这一过程可能削弱其通用能力。如何在领域特定增强与模型的通用实用性之间找到平衡，是一个关键挑战。本文提出了一种名为APT（基于弱点案例获取与迭代偏好训练）的新方法，通过自动生成的不受欢迎弱点数据（包括坏案例和相似案例）来提升领域特定性能。与传统方法不同，APT专注于仅使用模型出错的样本进行训练，并为此检索少量相似样本。这种针对性训练最大限度地减少了对模型现有知识库的干扰，从而有效保留了其通用能力。在LLama-2和Mistral-V0.3模型上进行的跨多种基准测试的实验结果表明，APT不仅确保了通用能力没有下降，还在下游任务中显著优于现有方法。这表明，我们的方法是一种有效的策略，可以在不牺牲模型更广泛应用能力的前提下，显著提升其领域特定能力。

> Large Language Models (LLMs) often require domain-specific fine-tuning to address targeted tasks, which risks degrading their general capabilities. Maintaining a balance between domain-specific enhancements and general model utility is a key challenge. This paper proposes a novel approach named APT (Weakness Case Acquisition and Iterative Preference Training) to enhance domain-specific performance with self-generated dis-preferred weakness data (bad cases and similar cases). APT uniquely focuses on training the model using only those samples where errors occur, alongside a small, similar set of samples retrieved for this purpose. This targeted training minimizes interference with the model's existing knowledge base, effectively retaining generic capabilities. Experimental results on the LLama-2 and Mistral-V0.3 models across various benchmarks demonstrate that APT ensures no reduction in generic capacity and achieves superior performance on downstream tasks compared to various existing methods. This validates our method as an effective strategy for enhancing domain-specific capabilities without sacrificing the model's broader applicability.

[Arxiv](https://arxiv.org/abs/2506.03483)