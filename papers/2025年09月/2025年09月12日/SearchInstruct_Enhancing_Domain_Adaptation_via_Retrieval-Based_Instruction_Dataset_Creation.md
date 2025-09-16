# SearchInstruct：通过基于检索的指令数据集构建提升领域自适应能力

发布时间：2025年09月12日

`LLM应用` `基础理论`

> SearchInstruct: Enhancing Domain Adaptation via Retrieval-Based Instruction Dataset Creation

# 摘要

> 监督微调（SFT）是训练大型语言模型（LLMs）的核心步骤，它显著提升了指令遵循、上下文学习等核心能力。但由于领域特殊性限制和数据稀缺问题，为特定领域构建定制化的优质训练数据集仍颇具挑战。本文提出SearchInstruct——一种创新方法，专为构建高质量SFT指令数据集而设计。我们的方法首先从少量领域特定的人工生成问题出发，借助大型语言模型对其进行系统性扩展；随后动态检索领域相关资源，为每个扩展后的问题生成准确且符合上下文的答案。实验验证显示，SearchInstruct不仅提升了SFT数据集的多样性与质量，进而在特定领域显著提升了LLM性能。此外，我们还发现，除了数据集生成外，该方法还能有效支持模型编辑等任务，实现现有模型的高效更新。为便于复现和社区使用，我们已在公开Git仓库中提供了完整实现细节、全部生成的指令-响应对及源代码：[https://github.com/mostafaamiri/SearchInstruct](https://github.com/mostafaamiri/SearchInstruct)

> Supervised Fine-Tuning (SFT) is essential for training large language models (LLMs), significantly enhancing critical capabilities such as instruction following and in-context learning. Nevertheless, creating suitable training datasets tailored for specific domains remains challenging due to unique domain constraints and data scarcity. In this paper, we propose SearchInstruct, an innovative method explicitly designed to construct high quality instruction datasets for SFT. Our approach begins with a limited set of domain specific, human generated questions, which are systematically expanded using a large language model. Subsequently, domain relevant resources are dynamically retrieved to generate accurate and contextually appropriate answers for each augmented question. Experimental evaluation demonstrates that SearchInstruct enhances both the diversity and quality of SFT datasets, leading to measurable improvements in LLM performance within specialized domains. Additionally, we show that beyond dataset generation, the proposed method can also effectively facilitate tasks such as model editing, enabling efficient updates to existing models. To facilitate reproducibility and community adoption, we provide full implementation details, the complete set of generated instruction response pairs, and the source code in a publicly accessible Git repository: [https://github.com/mostafaamiri/SearchInstruct](https://github.com/mostafaamiri/SearchInstruct)

[Arxiv](https://arxiv.org/abs/2509.10708)