# 基于主题的学术论文评审水印技术的可行性研究

发布时间：2025年05月27日

`LLM应用` `学术出版` `同行评审`

> The Feasibility of Topic-Based Watermarking on Academic Peer Reviews

# 摘要

> 大型语言模型（LLMs）正逐渐成为学术工作流程中不可或缺的一部分，许多学术会议和期刊已允许其用于语言润色和文献总结等任务。然而，出于对机密泄露、虚假内容和评估不一致的担忧，LLMs 在同行评审中的使用仍被禁止。随着 LLM 生成文本越来越难以与人类写作区分，我们需要可靠的归属机制来维护评审过程的完整性。

在本研究中，我们评估了一种名为主题基水印（TBW）的轻量级语义感知技术，它能够将可检测信号嵌入 LLM 生成的文本中。我们使用真实学术会议的同行评审数据，对多个 LLM 配置进行了全面评估，包括基础、少样本和微调版本。结果表明，TBW 不仅能够保持评审质量，相对于未加水印的输出，还对基于改写的规避表现出强大的鲁棒性。这些发现凸显了 TBW 作为 enforcement LLM 在同行评审中使用的一种 minimally intrusive 和实用解决方案的可行性。

> Large language models (LLMs) are increasingly integrated into academic workflows, with many conferences and journals permitting their use for tasks such as language refinement and literature summarization. However, their use in peer review remains prohibited due to concerns around confidentiality breaches, hallucinated content, and inconsistent evaluations. As LLM-generated text becomes more indistinguishable from human writing, there is a growing need for reliable attribution mechanisms to preserve the integrity of the review process. In this work, we evaluate topic-based watermarking (TBW), a lightweight, semantic-aware technique designed to embed detectable signals into LLM-generated text. We conduct a comprehensive assessment across multiple LLM configurations, including base, few-shot, and fine-tuned variants, using authentic peer review data from academic conferences. Our results show that TBW maintains review quality relative to non-watermarked outputs, while demonstrating strong robustness to paraphrasing-based evasion. These findings highlight the viability of TBW as a minimally intrusive and practical solution for enforcing LLM usage in peer review.

[Arxiv](https://arxiv.org/abs/2505.21636)