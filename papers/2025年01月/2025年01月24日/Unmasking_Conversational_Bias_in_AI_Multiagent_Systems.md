# AI多智能体系统中的对话偏见揭秘

发布时间：2025年01月24日

`Agent

理由：这篇论文主要研究的是多智能体系统中的偏见问题，特别是对话型大型语言模型（LLMs）在多智能体系统中的表现。论文提出了一个框架来量化这些系统中的偏见，并通过实验展示了多智能体系统中偏见的动态变化。因此，这篇论文的核心内容与多智能体系统（Agent）相关，而不是直接涉及RAG、LLM应用、LLM理论或其他领域。` `人工智能` `社会研究`

> Unmasking Conversational Bias in AI Multiagent Systems

# 摘要

> 检测生成模型输出中的偏见对于降低其关键应用中的潜在风险至关重要。然而，现有方法大多孤立地分析模型，忽略了其上下文应用。特别是，涉及生成模型的多智能体系统中可能出现的偏见研究较少。为此，我们提出了一种框架，用于量化对话型大型语言模型（LLMs）多智能体系统中的偏见。我们通过模拟小型回声室，让成对的LLMs在初始化时对极化话题持有相同观点并进行讨论。出乎意料的是，生成消息中的立场发生了显著变化，尤其是在所有智能体最初表达保守观点的回声室中，这与许多LLMs倾向于自由派立场的政治偏见一致。值得注意的是，回声室实验中的偏见未被当前依赖问卷的先进偏见检测方法发现。这凸显了开发更复杂工具包以检测和减轻AI多智能体系统中偏见的迫切需求。实验代码可在https://anonymous.4open.science/r/LLMsConversationalBias-7725公开获取。

> Detecting biases in the outputs produced by generative models is essential to reduce the potential risks associated with their application in critical settings. However, the majority of existing methodologies for identifying biases in generated text consider the models in isolation and neglect their contextual applications. Specifically, the biases that may arise in multi-agent systems involving generative models remain under-researched. To address this gap, we present a framework designed to quantify biases within multi-agent systems of conversational Large Language Models (LLMs). Our approach involves simulating small echo chambers, where pairs of LLMs, initialized with aligned perspectives on a polarizing topic, engage in discussions. Contrary to expectations, we observe significant shifts in the stance expressed in the generated messages, particularly within echo chambers where all agents initially express conservative viewpoints, in line with the well-documented political bias of many LLMs toward liberal positions. Crucially, the bias observed in the echo-chamber experiment remains undetected by current state-of-the-art bias detection methods that rely on questionnaires. This highlights a critical need for the development of a more sophisticated toolkit for bias detection and mitigation for AI multi-agent systems. The code to perform the experiments is publicly available at https://anonymous.4open.science/r/LLMsConversationalBias-7725.

[Arxiv](https://arxiv.org/abs/2501.14844)