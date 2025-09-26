# 阿拉伯语大型语言模型的工具调用：数据策略与指令微调

发布时间：2025年09月25日

`Agent` `基础理论`

> Tool Calling for Arabic LLMs: Data Strategies and Instruction Tuning

# 摘要

> 工具调用是一项关键能力，它让大型语言模型（LLMs）能够与外部系统交互，大幅拓展其实用价值。然而，工具调用的相关研究与资源主要以英语为核心，导致我们在如何为其他语言（如阿拉伯语）实现该功能的认知上存在空白。本文探讨了三个关键研究问题：（1）语言内（阿拉伯语）工具调用数据的必要性——与依赖跨语言迁移相比；（2）通用指令微调对工具调用性能的影响；（3）针对特定高优先级工具进行微调的价值。为解答这些问题，我们利用开源阿拉伯语大型语言模型的基础与后训练版本开展了大量实验。为推进此项研究，我们将两个开源工具调用数据集翻译成阿拉伯语并加以适配，填补了这一资源空白。研究结果为开发阿拉伯语稳健的工具增强智能体提供了关键策略见解。

> Tool calling is a critical capability that allows Large Language Models (LLMs) to interact with external systems, significantly expanding their utility. However, research and resources for tool calling are predominantly English-centric, leaving a gap in our understanding of how to enable this functionality for other languages, such as Arabic. This paper investigates three key research questions: (1) the necessity of in-language (Arabic) tool-calling data versus relying on cross-lingual transfer, (2) the effect of general-purpose instruction tuning on tool-calling performance, and (3) the value of fine-tuning on specific, high-priority tools. To address these questions, we conduct extensive experiments using base and post-trained variants of an open-weight Arabic LLM. To enable this study, we bridge the resource gap by translating and adapting two open-source tool-calling datasets into Arabic. Our findings provide crucial insights into the optimal strategies for developing robust tool-augmented agents for Arabic.

[Arxiv](https://arxiv.org/abs/2509.20957)