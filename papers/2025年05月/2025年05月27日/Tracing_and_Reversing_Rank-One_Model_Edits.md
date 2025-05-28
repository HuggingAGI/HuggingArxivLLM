# 追踪与逆转秩一模型修改

发布时间：2025年05月27日

`LLM理论` `人工智能` `网络安全`

> Tracing and Reversing Rank-One Model Edits

# 摘要

> 知识编辑方法（KEs）为更新大型语言模型（LLMs）的事实内容提供了一种经济高效的方式，但同时也带来了双重使用风险。虽然这些方法有助于更新过时或错误的信息，但它们也可能被恶意利用来植入虚假信息或偏见。为了抵御这种恶意操控，我们需要可靠的检测、解释和缓解对抗性编辑的技术。本研究重点探究了知识编辑的可追溯性和可逆性，以广泛应用的Rank-One Model Editing（ROME）方法为例展开分析。首先，我们发现ROME在编辑后的权重矩阵中引入了独特的分布模式，这些模式可作为定位编辑权重的有效信号。其次，我们证明了这些改变后的权重可用于可靠预测编辑的事实关系，从而实现对修改事实的部分重建。基于此，我们提出了一种无需访问编辑提示、直接从修改后的权重推断编辑对象实体的方法，准确率超过95%。最后，我们证实ROME编辑可被逆转，成功以≥80%的准确率恢复模型的原始输出。我们的研究结果凸显了基于编辑权重检测、追踪和逆转编辑的可能性，为保护LLMs免受对抗性操控提供了一个稳健的框架。

> Knowledge editing methods (KEs) are a cost-effective way to update the factual content of large language models (LLMs), but they pose a dual-use risk. While KEs are beneficial for updating outdated or incorrect information, they can be exploited maliciously to implant misinformation or bias. In order to defend against these types of malicious manipulation, we need robust techniques that can reliably detect, interpret, and mitigate adversarial edits. This work investigates the traceability and reversibility of knowledge edits, focusing on the widely used Rank-One Model Editing (ROME) method. We first show that ROME introduces distinctive distributional patterns in the edited weight matrices, which can serve as effective signals for locating the edited weights. Second, we show that these altered weights can reliably be used to predict the edited factual relation, enabling partial reconstruction of the modified fact. Building on this, we propose a method to infer the edited object entity directly from the modified weights, without access to the editing prompt, achieving over 95% accuracy. Finally, we demonstrate that ROME edits can be reversed, recovering the model's original outputs with $\geq$ 80% accuracy. Our findings highlight the feasibility of detecting, tracing, and reversing edits based on the edited weights, offering a robust framework for safeguarding LLMs against adversarial manipulations.

[Arxiv](https://arxiv.org/abs/2505.20819)