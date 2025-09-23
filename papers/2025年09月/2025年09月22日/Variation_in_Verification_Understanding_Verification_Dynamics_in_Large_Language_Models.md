# 验证的变异性：解析大型语言模型中的验证动态

发布时间：2025年09月22日

`LLM应用` `基础理论`

> Variation in Verification: Understanding Verification Dynamics in Large Language Models

# 摘要

> 近期研究表明，扩展测试时计算量可让大型语言模型（LLMs）在多领域解决更复杂的问题。测试时扩展（TTS）的一种有效范式是：LLM生成器产出多个解决方案候选，LLM验证器则在无参考答案时评估其正确性。本文研究生成式验证器——这类验证器通过生成思维链（CoT）推理并给出二元判断来完成验证。我们借助14个开源模型（参数规模20亿至720亿）和GPT-4o，在数学推理、知识类及自然语言推理任务的12个基准测试上开展实证研究，系统分析了验证动态的三个维度：问题难度、生成器能力与验证器生成能力。实验揭示了验证有效性的三个关键发现：（1）简单问题中，验证器对正确响应的确认更可靠；（2）弱生成器的错误比强生成器更易检测；（3）验证能力通常与验证器自身的解题能力相关，但该关系会随问题难度变化。这些发现为优化TTS应用中的基础验证策略带来了契机。其一，在相同验证器下，部分弱生成器的验证后TTS性能可接近强生成器（如Gemma2-9B与Gemma2-27B的性能差距缩小75.5%）。其二，我们发现强验证器相比弱验证器优势有限的场景——此时两者均无法带来显著验证增益，这说明仅靠验证器扩展无法解决根本性验证挑战。

> Recent advances have shown that scaling test-time computation enables large language models (LLMs) to solve increasingly complex problems across diverse domains. One effective paradigm for test-time scaling (TTS) involves LLM generators producing multiple solution candidates, with LLM verifiers assessing the correctness of these candidates without reference answers. In this paper, we study generative verifiers, which perform verification by generating chain-of-thought (CoT) reasoning followed by a binary verdict. We systematically analyze verification dynamics across three dimensions - problem difficulty, generator capability, and verifier generation capability - with empirical studies on 12 benchmarks across mathematical reasoning, knowledge, and natural language reasoning tasks using 14 open-source models (2B to 72B parameter range) and GPT-4o. Our experiments reveal three key findings about verification effectiveness: (1) Easy problems allow verifiers to more reliably certify correct responses; (2) Weak generators produce errors that are easier to detect than strong generators; (3) Verification ability is generally correlated with the verifier's own problem-solving capability, but this relationship varies with problem difficulty. These findings reveal opportunities to optimize basic verification strategies in TTS applications. First, given the same verifier, some weak generators can nearly match stronger ones in post-verification TTS performance (e.g., the Gemma2-9B to Gemma2-27B performance gap shrinks by 75.5%). Second, we identify cases where strong verifiers offer limited advantage over weak ones, as both fail to provide meaningful verification gains, suggesting that verifier scaling alone cannot overcome fundamental verification challenges.

[Arxiv](https://arxiv.org/abs/2509.17995)