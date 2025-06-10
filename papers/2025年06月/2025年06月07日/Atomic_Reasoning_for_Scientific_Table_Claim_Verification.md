# 科学表格声明验证中的原子推理

发布时间：2025年06月07日

`LLM应用` `声明验证`

> Atomic Reasoning for Scientific Table Claim Verification

# 摘要

> 科学文本因技术术语和复杂数据而显得权威，但这种复杂性有时会助长错误信息的传播。非专业人士尤其容易被科学表格误导，因其高信息密度和高可信度。现有的表格声明验证模型，包括先进的大型语言模型（LLMs），在进行精细推理时往往力不从心，导致科学声明验证时出现误差和不准确。基于认知负荷理论，我们提出通过开发模块化、可复用的推理组件（即原子技能）来降低认知负荷，从而提升模型对表格声明的解释能力。我们提出了一种技能链模式，能够动态组合这些技能，以更低的认知负荷实现更准确和通用的推理。为验证这一方法，我们创建了 SciAtomicBench，这是一个跨领域的精细推理基准测试。仅使用 350 个微调示例，通过原子推理训练的模型在科学声明验证上超越了 GPT-4o 的链式推理方法，以远少于现有方法的训练数据量达到了最先进的性能。


> Scientific texts often convey authority due to their technical language and complex data. However, this complexity can sometimes lead to the spread of misinformation. Non-experts are particularly susceptible to misleading claims based on scientific tables due to their high information density and perceived credibility. Existing table claim verification models, including state-of-the-art large language models (LLMs), often struggle with precise fine-grained reasoning, resulting in errors and a lack of precision in verifying scientific claims. Inspired by Cognitive Load Theory, we propose that enhancing a model's ability to interpret table-based claims involves reducing cognitive load by developing modular, reusable reasoning components (i.e., atomic skills). We introduce a skill-chaining schema that dynamically composes these skills to facilitate more accurate and generalizable reasoning with a reduced cognitive load. To evaluate this, we create SciAtomicBench, a cross-domain benchmark with fine-grained reasoning annotations. With only 350 fine-tuning examples, our model trained by atomic reasoning outperforms GPT-4o's chain-of-thought method, achieving state-of-the-art results with far less training data.

[Arxiv](https://arxiv.org/abs/2506.06972)