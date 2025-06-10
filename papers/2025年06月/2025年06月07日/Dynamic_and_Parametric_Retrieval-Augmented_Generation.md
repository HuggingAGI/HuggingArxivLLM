# 动态参数化检索增强生成

发布时间：2025年06月07日

`RAG` `信息检索` `知识密集型应用`

> Dynamic and Parametric Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）已成为为大型语言模型（LLMs）配备外部知识的基础范式，在信息检索和知识密集型应用中发挥着关键作用。然而，传统的RAG系统通常采用静态的检索-生成流水线，并依赖于上下文中的知识注入，这在处理复杂任务时可能表现不佳。为了克服这些限制，研究界已经超越了静态检索和上下文知识注入的范畴。在新兴的研究方向中，本教程深入探讨了两个迅速发展且互补的RAG研究领域：动态RAG与参数化RAG。动态RAG能够自适应地决定在LLM生成过程中何时以及检索什么内容，从而实现实时适应LLM不断变化的信息需求。参数化RAG重新思考了检索到的知识应如何注入到LLMs中，从输入层面转向参数层面的知识注入，以提升效率和效果。本教程全面概述了这些新兴研究领域的最新进展，并分享了理论基础与实践见解，旨在支持和启发RAG领域的进一步研究。

> Retrieval-Augmented Generation (RAG) has become a foundational paradigm for equipping large language models (LLMs) with external knowledge, playing a critical role in information retrieval and knowledge-intensive applications. However, conventional RAG systems typically adopt a static retrieve-then-generate pipeline and rely on in-context knowledge injection, which can be suboptimal for complex tasks that require multihop reasoning, adaptive information access, and deeper integration of external knowledge. Motivated by these limitations, the research community has moved beyond static retrieval and in-context knowledge injection. Among the emerging directions, this tutorial delves into two rapidly growing and complementary research areas on RAG: Dynamic RAG and Parametric RAG. Dynamic RAG adaptively determines when and what to retrieve during the LLM's generation process, enabling real-time adaptation to the LLM's evolving information needs. Parametric RAG rethinks how retrieved knowledge should be injected into LLMs, transitioning from input-level to parameter-level knowledge injection for enhanced efficiency and effectiveness. This tutorial offers a comprehensive overview of recent advances in these emerging research areas. It also shares theoretical foundations and practical insights to support and inspire further research in RAG.

[Arxiv](https://arxiv.org/abs/2506.06704)