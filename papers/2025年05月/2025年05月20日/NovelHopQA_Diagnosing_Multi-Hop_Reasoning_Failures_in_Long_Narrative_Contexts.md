# NovelHopQA：长叙述上下文中多跳推理失败的诊断

发布时间：2025年05月20日

`LLM应用` `问答系统` `模型评估`

> NovelHopQA: Diagnosing Multi-Hop Reasoning Failures in Long Narrative Contexts

# 摘要

> 当前大型语言模型（LLMs）在处理跨越数万token的问题时表现欠佳，尤其在涉及多跳推理时。现有基准测试分别考察了长上下文理解或多跳推理，但未能在自然叙述环境中同时调整上下文长度与推理深度。我们推出NovelHopQA，首个针对k1-4跳QA的基准测试，基于83本公开领域小说的64k-128k-token摘录。通过关键词引导的管道，构建了基于连贯故事情节的跳分隔链。我们评估了六种最先进的模型，并采用黄金上下文过滤确保所有问题皆可解答。人类标注者验证了对齐度与跳深度。研究发现，跳数与上下文长度增加时，准确率持续下降，即使在前沿模型中也揭示了单纯规模无法确保稳健推理。故障模式分析揭示了常见问题，如最终跳整合失败与长距离漂移。NovelHopQA提供了一个受控诊断环境，用于在大规模下测试多跳推理的极限。

> Current large language models (LLMs) struggle to answer questions that span tens of thousands of tokens, especially when multi-hop reasoning is involved. While prior benchmarks explore long-context comprehension or multi-hop reasoning in isolation, none jointly vary context length and reasoning depth in natural narrative settings. We introduce NovelHopQA, the first benchmark to evaluate k1-4 hop QA over 64k-128k-token excerpts from 83 full-length public-domain novels. A keyword-guided pipeline builds hop-separated chains grounded in coherent storylines. We evaluate six state-of-the-art (SOTA) models and apply oracle-context filtering to ensure all questions are genuinely answerable. Human annotators validate both alignment and hop depth. We noticed consistent accuracy drops with increased hops and context length, even in frontier models-revealing that sheer scale does not guarantee robust reasoning. Our failure mode analysis highlights common breakdowns, such as missed final-hop integration and long-range drift. NovelHopQA offers a controlled diagnostic setting to stress-test multi-hop reasoning at scale.

[Arxiv](https://arxiv.org/abs/2506.02000)