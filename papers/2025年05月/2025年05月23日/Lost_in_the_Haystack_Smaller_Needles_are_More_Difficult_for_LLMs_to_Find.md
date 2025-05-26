# # 迷失在 haystack 中：更小的针，LLM 更难寻

发布时间：2025年05月23日

`LLM理论` `问答系统`

> Lost in the Haystack: Smaller Needles are More Difficult for LLMs to Find

# 摘要

> 大型语言模型（LLMs）在处理“针在 haystack 中”的任务时面临巨大挑战，这类任务要求从大量无关的上下文中提取出相关的信息（“针”）。以往研究指出，位置偏见和干扰项数量是影响模型性能的关键因素，然而，黄金上下文大小的影响却鲜少得到关注。我们通过系统性研究填补这一空白，探讨黄金上下文长度的变化如何影响 LLM 在长上下文问答任务中的表现。实验结果表明，当黄金上下文较短时，模型性能显著下降，即较小的黄金上下文会持续降低模型性能并加剧位置敏感性，这对必须整合零散、细粒度且长度不一信息的智能体系统构成重大挑战。这一规律在三个不同领域（通用知识、生物医学推理和数学推理）以及七种不同规模和架构的先进 LLM 中均成立。我们的研究为设计稳健且具备上下文感知能力的 LLM 驱动系统提供了清晰的指导思路。


> Large language models (LLMs) face significant challenges with needle-in-a-haystack tasks, where relevant information ("the needle") must be drawn from a large pool of irrelevant context ("the haystack"). Previous studies have highlighted positional bias and distractor quantity as critical factors affecting model performance, yet the influence of gold context size has received little attention. We address this gap by systematically studying how variations in gold context length impact LLM performance on long-context question answering tasks. Our experiments reveal that LLM performance drops sharply when the gold context is shorter, i.e., smaller gold contexts consistently degrade model performance and amplify positional sensitivity, posing a major challenge for agentic systems that must integrate scattered, fine-grained information of varying lengths. This pattern holds across three diverse domains (general knowledge, biomedical reasoning, and mathematical reasoning) and seven state-of-the-art LLMs of various sizes and architectures. Our work provides clear insights to guide the design of robust, context-aware LLM-driven systems.

[Arxiv](https://arxiv.org/abs/2505.18148)