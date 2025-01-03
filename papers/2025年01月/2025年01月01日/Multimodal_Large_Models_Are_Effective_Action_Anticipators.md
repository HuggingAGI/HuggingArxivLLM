# 多模态大模型：高效的动作预测利器

发布时间：2025年01月01日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）来解决长期动作预测任务，提出了一个名为ActionLLM的框架。该框架通过将视频序列视为连续标记，并利用LLMs的序列建模能力和常识知识来预测未来动作。论文的核心在于应用LLMs来解决具体的实际问题（动作预测），因此应归类为LLM应用。` `计算机视觉` `动作预测`

> Multimodal Large Models Are Effective Action Anticipators

# 摘要

> 长期动作预测任务需要能够有效建模长时间动态并深入理解动作内在语义的解决方案。传统方法主要依赖循环单元或Transformer层来捕捉长期依赖关系，但在应对这些挑战时往往表现不足。大型语言模型（LLMs）凭借其强大的序列建模能力和广泛的常识知识，为长期动作预测提供了新的机会。在这项工作中，我们提出了ActionLLM框架，这是一种将视频序列视为连续标记的新方法，利用LLMs来预测未来动作。我们的基线模型通过设置未来标记、引入动作调优模块并将文本解码器层简化为线性层，简化了LLM架构，从而无需复杂指令或冗余描述即可实现直接的动作预测。为了进一步利用LLMs的常识推理能力，我们预测观察帧的动作类别，并使用序列文本线索来引导语义理解。此外，我们引入了一个跨模态交互块，旨在探索每种模态内的特异性并捕捉视觉和文本模态之间的交互，从而增强多模态调优。在基准数据集上的大量实验证明了所提出的ActionLLM框架的优越性，为探索LLMs在动作预测中的应用开辟了有前景的方向。代码可在https://github.com/2tianyao1/ActionLLM.git获取。

> The task of long-term action anticipation demands solutions that can effectively model temporal dynamics over extended periods while deeply understanding the inherent semantics of actions. Traditional approaches, which primarily rely on recurrent units or Transformer layers to capture long-term dependencies, often fall short in addressing these challenges. Large Language Models (LLMs), with their robust sequential modeling capabilities and extensive commonsense knowledge, present new opportunities for long-term action anticipation. In this work, we introduce the ActionLLM framework, a novel approach that treats video sequences as successive tokens, leveraging LLMs to anticipate future actions. Our baseline model simplifies the LLM architecture by setting future tokens, incorporating an action tuning module, and reducing the textual decoder layer to a linear layer, enabling straightforward action prediction without the need for complex instructions or redundant descriptions. To further harness the commonsense reasoning of LLMs, we predict action categories for observed frames and use sequential textual clues to guide semantic understanding. In addition, we introduce a Cross-Modality Interaction Block, designed to explore the specificity within each modality and capture interactions between vision and textual modalities, thereby enhancing multimodal tuning. Extensive experiments on benchmark datasets demonstrate the superiority of the proposed ActionLLM framework, encouraging a promising direction to explore LLMs in the context of action anticipation. Code is available at https://github.com/2tianyao1/ActionLLM.git.

[Arxiv](https://arxiv.org/abs/2501.00795)