# 超越大型语言模型：基于叙事文本的因果图语言学生成方法

发布时间：2025年04月10日

`LLM应用` `人工智能`

> Beyond LLMs: A Linguistic Approach to Causal Graph Generation from Narrative Texts

# 摘要

> 我们提出了一种从叙事文本生成因果图的新框架，成功连接了高层次因果关系和具体事件的详细关系。该方法首先利用大型语言模型（LLM）的摘要功能提取简洁的以主体为中心的节点。我们创新性地引入了一个包含七个语言学特征的“专家索引”，并将其整合到情境-任务-行动-后果（STAC）分类模型中。结合RoBERTa嵌入与专家索引的混合系统，在因果关系识别的精确度上显著优于纯LLM方法。通过五轮结构化提示过程，我们成功细化并构建出连贯的因果图。实验结果表明，在100个叙事章节和短篇小说上，我们的方法在因果图质量上持续超越GPT-4o和Claude 3.5，同时保持了良好的可读性。我们的开源工具提供了一种可解释且高效的解决方案，能够精准捕捉叙事中的细微因果链。

> We propose a novel framework for generating causal graphs from narrative texts, bridging high-level causality and detailed event-specific relationships. Our method first extracts concise, agent-centered vertices using large language model (LLM)-based summarization. We introduce an "Expert Index," comprising seven linguistically informed features, integrated into a Situation-Task-Action-Consequence (STAC) classification model. This hybrid system, combining RoBERTa embeddings with the Expert Index, achieves superior precision in causal link identification compared to pure LLM-based approaches. Finally, a structured five-iteration prompting process refines and constructs connected causal graphs. Experiments on 100 narrative chapters and short stories demonstrate that our approach consistently outperforms GPT-4o and Claude 3.5 in causal graph quality, while maintaining readability. The open-source tool provides an interpretable, efficient solution for capturing nuanced causal chains in narratives.

[Arxiv](https://arxiv.org/abs/2504.07459)