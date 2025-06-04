# NovelHopQA：解析长篇叙述中的多跳推理失效问题

发布时间：2025年05月20日

`LLM应用

理由：这篇论文专注于评估和分析大型语言模型在多跳问答任务中的应用，特别是在长文本和多跳推理方面的能力。它介绍了NovelHopQA基准测试，用于评估模型在这些场景下的表现，并探讨了模型在这些任务中的局限性和挑战，属于LLM的应用研究。` `问答系统`

> NovelHopQA: Diagnosing Multi-Hop Reasoning Failures in Long Narrative Contexts

# 摘要

> 当前大型语言模型（LLMs）在处理跨越数万tokens的问题时表现欠佳，尤其在涉及多跳推理时。现有基准测试大多分别考察长上下文理解或独立的多跳推理，却未能在自然叙述场景中同时考察上下文长度与推理深度的交互影响。为此，我们推出了NovelHopQA，这是首个专注于k1-4跳QA的基准测试，涵盖了83本公开小说的64k-128k-token长文本。通过基于关键词的流水线，我们构建了以连贯故事线为依据的分段推理链。在对六种最先进模型进行评估时，我们采用了oracle上下文过滤机制，确保所有问题均具备明确解答。经人类标注者验证，问题的对齐度与推理深度均符合预期。值得注意的是，所有模型的准确率随着跳数和上下文长度的增加而持续下降，即使是最前沿的模型也未能幸免——这表明单纯依赖模型规模无法确保稳健的推理能力。通过故障模式分析，我们发现常见的推理失败点包括最终跳整合缺失和长距离漂移等问题。NovelHopQA提供了一个受控的诊断环境，旨在大规模压力测试多跳推理能力，为相关研究提供重要参考。

> Current large language models (LLMs) struggle to answer questions that span tens of thousands of tokens, especially when multi-hop reasoning is involved. While prior benchmarks explore long-context comprehension or multi-hop reasoning in isolation, none jointly vary context length and reasoning depth in natural narrative settings. We introduce NovelHopQA, the first benchmark to evaluate k1-4 hop QA over 64k-128k-token excerpts from 83 full-length public-domain novels. A keyword-guided pipeline builds hop-separated chains grounded in coherent storylines. We evaluate six state-of-the-art (SOTA) models and apply oracle-context filtering to ensure all questions are genuinely answerable. Human annotators validate both alignment and hop depth. We noticed consistent accuracy drops with increased hops and context length, even in frontier models-revealing that sheer scale does not guarantee robust reasoning. Our failure mode analysis highlights common breakdowns, such as missed final-hop integration and long-range drift. NovelHopQA offers a controlled diagnostic setting to stress-test multi-hop reasoning at scale.

[Arxiv](https://arxiv.org/abs/2506.02000)