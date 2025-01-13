# 机器人导航中的语言与规划：顶尖模型的多语言评估

发布时间：2025年01月07日

`Agent

理由：这篇论文主要讨论了在机器人领域的视觉与语言导航（VLN）中引入阿拉伯语集成，并使用了一个基于LLM的指令跟随导航代理（NavGPT）来进行导航任务规划。虽然涉及到了LLM的应用，但核心内容集中在导航代理（Agent）的设计和评估上，因此更适合归类为Agent。` `机器人` `多语言处理`

> Language and Planning in Robotic Navigation: A Multilingual Evaluation of State-of-the-Art Models

# 摘要

> # 摘要
像 GPT-4 这样的大型语言模型（LLMs），经过跨多个领域的大量数据集训练，在各种任务中展现出强大的推理、理解和规划能力。本研究首次在机器人领域的视觉与语言导航（VLN）中引入了阿拉伯语集成，填补了现有研究的空白。我们对包括 GPT-4o mini、Llama 3 8B 和 Phi-3 medium 14B 在内的多语言小型语言模型（SLMs）以及以阿拉伯语为中心的 LLM Jais 进行了全面评估。通过 NavGPT 框架，一个纯基于 LLM 的指令跟随导航代理，我们使用 R2R 数据集进行零-shot 序列动作预测，评估了语言对导航推理的影响。实验表明，当提供英语和阿拉伯语指令时，我们的框架能够进行高级导航任务规划。然而，某些模型在阿拉伯语中的推理和规划方面表现不佳，这归因于其能力的局限性、性能不足和解析问题。这些发现强调了增强语言模型规划和推理能力的重要性，为阿拉伯语模型在现实世界应用中的潜力开辟了新的研究方向。

> Large Language Models (LLMs) such as GPT-4, trained on huge amount of datasets spanning multiple domains, exhibit significant reasoning, understanding, and planning capabilities across various tasks. This study presents the first-ever work in Arabic language integration within the Vision-and-Language Navigation (VLN) domain in robotics, an area that has been notably underexplored in existing research. We perform a comprehensive evaluation of state-of-the-art multi-lingual Small Language Models (SLMs), including GPT-4o mini, Llama 3 8B, and Phi-3 medium 14B, alongside the Arabic-centric LLM, Jais. Our approach utilizes the NavGPT framework, a pure LLM-based instruction-following navigation agent, to assess the impact of language on navigation reasoning through zero-shot sequential action prediction using the R2R dataset. Through comprehensive experiments, we demonstrate that our framework is capable of high-level planning for navigation tasks when provided with instructions in both English and Arabic. However, certain models struggled with reasoning and planning in the Arabic language due to inherent limitations in their capabilities, sub-optimal performance, and parsing issues. These findings highlight the importance of enhancing planning and reasoning capabilities in language models for effective navigation, emphasizing this as a key area for further development while also unlocking the potential of Arabic-language models for impactful real-world applications.

[Arxiv](https://arxiv.org/abs/2501.05478)