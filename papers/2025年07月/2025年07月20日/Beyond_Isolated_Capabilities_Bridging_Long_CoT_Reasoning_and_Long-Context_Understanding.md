# 突破孤立能力的界限：融合长链思维推理与长上下文理解

发布时间：2025年07月20日

`LLM应用` `问答系统`

> Beyond Isolated Capabilities: Bridging Long CoT Reasoning and Long-Context Understanding

# 摘要

> 推理蒸馏作为一种有效提升小型语言模型推理能力的方法逐渐受到关注。然而，大规模推理蒸馏对其他关键能力的影响，尤其是对上下文检索和推理能力的影响，仍未得到充分研究。这一认知空白在当前日益重要的检索增强生成（RAG）系统背景下显得尤为重要，因为这些系统需要高效获取和利用上下文信息以生成可靠回应。

为深入理解扩展长链CoT过程对长上下文理解的影响，我们采用一系列源自Deepseek-R1的开源蒸馏模型展开全面研究。Deepseek-R1以其卓越的推理能力而闻名。本研究重点评估了这些模型在多文档问答任务中从扩展上下文中提取和整合相关信息的能力。

通过严谨的实验，我们证实了蒸馏推理模式对提升长上下文理解能力具有显著效果。分析表明，蒸馏过程通过促进上下文分析和信息解析过程中更详细和明确的推理流程，增强了模型的长上下文感知能力。这一突破有效缓解了长期困扰长上下文模型的“迷失在中间”问题。


> Reasoning distillation has emerged as an effective approach to enhance the reasoning capabilities of smaller language models. However, the impact of large-scale reasoning distillation on other critical abilities, particularly in-context retrieval and reasoning, remains unexplored. This gap in understanding is particularly significant given the increasing importance of Retrieval-Augmented Generation (RAG) systems, where efficient acquisition and utilization of contextual information are paramount for generating reliable responses. Motivated by the need to understand how the extended long-CoT process influences long-context comprehension, we conduct a comprehensive investigation using a series of open-source models distilled from Deepseek-R1, renowned for its exceptional reasoning capabilities. Our study focuses on evaluating these models' performance in extracting and integrating relevant information from extended contexts through multi-document question and answering tasks. Through rigorous experimentation, we demonstrate that distilled reasoning patterns significantly improve long-context understanding. Our analysis reveals that distillation fosters greater long-context awareness by promoting more detailed and explicit reasoning processes during context analysis and information parsing. This advancement effectively mitigates the persistent "lost in the middle" issue that has hindered long-context models.

[Arxiv](https://arxiv.org/abs/2507.14849)