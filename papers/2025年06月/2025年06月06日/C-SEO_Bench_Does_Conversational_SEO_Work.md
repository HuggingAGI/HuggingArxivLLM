# C-SEO 基准：对话式 SEO 真的有用吗？

发布时间：2025年06月06日

`LLM应用

理由：这篇论文探讨了大型语言模型在搜索引擎优化中的应用，特别是对话式搜索引擎优化（C-SEO）的方法和评估。它展示了LLMs在实际应用中的影响和优化策略，属于LLM的应用领域。` `搜索引擎优化` `对话式搜索引擎`

> C-SEO Bench: Does Conversational SEO Work?

# 摘要

> 大型语言模型（LLMs）正在推动搜索引擎向对话式搜索引擎（CSE）转型，随之而来的搜索引擎优化（SEO）也正在向对话式搜索引擎优化（C-SEO）演变。我们已经开始看到一系列专门的C-SEO方法，这些方法通过修改网页文档来提升其在CSE结果中的可见性。然而，这些方法往往仅在一个有限的应用领域范围内进行测试，我们尚不清楚某些C-SEO方法是否能广泛适用于各种领域。此外，现有的评估仅考虑单一参与者场景，即仅有一个网页文档采用C-SEO方法；而在现实情况下，多个参与者可能会竞争性地采用前沿的C-SEO技术，这与我们所熟知的SEO动态类似。

为了解决这些问题，我们推出了C-SEO Bench，这是首个专为跨多任务、多领域及多参与者数量的C-SEO方法设计的基准测试框架。我们考虑了两个核心搜索任务：问答和产品推荐，每个任务下涵盖三个不同领域。我们还制定了一个新的评估协议，其中涉及参与者采用率的动态变化。实验结果显示，大多数现有的C-SEO方法效果并不显著，与文献中报告的结果形成鲜明对比。相反，传统的SEO策略——旨在提升源内容在LLM上下文中的排名——表现出了显著更高的有效性。

此外，我们观察到，随着采用C-SEO方法的参与者数量增加，整体收益呈现下降趋势，这表明该问题具有拥挤和零和博弈的特性。我们的代码和数据可在以下链接获取：[GitHub](https://github.com/parameterlab/c-seo-bench) 和 [Hugging Face](https://huggingface.co/datasets/parameterlab/c-seo-bench)。

> Large Language Models (LLMs) are transforming search engines into Conversational Search Engines (CSE). Consequently, Search Engine Optimization (SEO) is being shifted into Conversational Search Engine Optimization (C-SEO). We are beginning to see dedicated C-SEO methods for modifying web documents to increase their visibility in CSE responses. However, they are often tested only for a limited breadth of application domains; we do not understand whether certain C-SEO methods would be effective for a broad range of domains. Moreover, existing evaluations consider only a single-actor scenario where only one web document adopts a C-SEO method; in reality, multiple players are likely to competitively adopt the cutting-edge C-SEO techniques, drawing an analogy from the dynamics we have seen in SEO. We present C-SEO Bench, the first benchmark designed to evaluate C-SEO methods across multiple tasks, domains, and number of actors. We consider two search tasks, question answering and product recommendation, with three domains each. We also formalize a new evaluation protocol with varying adoption rates among involved actors. Our experiments reveal that most current C-SEO methods are largely ineffective, contrary to reported results in the literature. Instead, traditional SEO strategies, those aiming to improve the ranking of the source in the LLM context, are significantly more effective. We also observe that as we increase the number of C-SEO adopters, the overall gains decrease, depicting a congested and zero-sum nature of the problem. Our code and data are available at https://github.com/parameterlab/c-seo-bench and https://huggingface.co/datasets/parameterlab/c-seo-bench.

[Arxiv](https://arxiv.org/abs/2506.11097)