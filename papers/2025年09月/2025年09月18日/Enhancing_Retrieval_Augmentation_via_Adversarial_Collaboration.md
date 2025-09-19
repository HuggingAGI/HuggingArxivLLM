# 基于对抗性协作的检索增强优化

发布时间：2025年09月18日

`RAG` `基础理论`

> Enhancing Retrieval Augmentation via Adversarial Collaboration

# 摘要

> 检索增强生成（RAG）是特定领域大型语言模型（LLMs）的主流方法，却常受“检索幻觉”问题困扰——即微调模型无法识别并应对低质量检索文档，进而影响性能的现象。为此，我们提出对抗协作检索增强生成（AC-RAG）框架。AC-RAG配备两个异构智能体：一个定位知识盲区的通用检测器（Detector），以及一个提供精准解决方案的领域专用求解器（Resolver）。在协调者的引导下，这些智能体展开对抗协作：检测器通过连环追问不断考验求解器的专业能力。这一动态过程促成了问题的层层拆解与知识检索的精准化。大量实验结果显示，AC-RAG大幅提升了检索准确性，并在多个垂直领域性能超越当前最先进的RAG方法。

> Retrieval-augmented Generation (RAG) is a prevalent approach for domain-specific LLMs, yet it is often plagued by "Retrieval Hallucinations"--a phenomenon where fine-tuned models fail to recognize and act upon poor-quality retrieved documents, thus undermining performance. To address this, we propose the Adversarial Collaboration RAG (AC-RAG) framework. AC-RAG employs two heterogeneous agents: a generalist Detector that identifies knowledge gaps, and a domain-specialized Resolver that provides precise solutions. Guided by a moderator, these agents engage in an adversarial collaboration, where the Detector's persistent questioning challenges the Resolver's expertise. This dynamic process allows for iterative problem dissection and refined knowledge retrieval. Extensive experiments show that AC-RAG significantly improves retrieval accuracy and outperforms state-of-the-art RAG methods across various vertical domains.

[Arxiv](https://arxiv.org/abs/2509.14750)