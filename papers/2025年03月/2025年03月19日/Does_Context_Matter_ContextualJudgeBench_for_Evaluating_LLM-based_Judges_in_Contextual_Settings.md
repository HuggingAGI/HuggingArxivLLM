# 背景真的重要吗？# ContextualJudgeBench：评估基于大语言模型的裁判能力
在背景化环境中，ContextualJudgeBench为您提供专业评估工具。

发布时间：2025年03月19日

`RAG

理由：这篇论文探讨了在上下文设置中评估大型语言模型输出的挑战，特别是针对检索增强生成（RAG）和摘要等用例。研究者提出了一个专门针对上下文评估的基准，分析了现有评估模型的表现，因此属于RAG类别。`

> Does Context Matter? ContextualJudgeBench for Evaluating LLM-based Judges in Contextual Settings

# 摘要

> 大型语言模型（LLM）作为评估者范式被广泛用于满足AI系统开发和部署后监控期间对廉价、可靠且快速的模型输出评估需求。尽管评估模型——经过微调以专门评估和批评模型输出的LLMs——被誉为通用评估器，但它们的评估范围通常局限于非上下文场景（如遵循指令）。令人惊讶的是，鉴于检索增强生成（RAG）和摘要等用例的日益普及，上下文设置（即利用外部信息作为上下文生成输出的情况）却被忽略了。上下文评估具有独特挑战性，因为评估往往取决于实践者的优先级，导致条件性评估标准（例如，先比较响应的事实性，如果事实性相同则考虑完整性）。为了解决这一差距，我们提出了ContextualJudgeBench，这是一个包含2,000个具有挑战性的响应对的评估基准，这些响应对灵感源自现实世界中的上下文评估场景，分为八个部分。我们通过一个多管齐下的数据构建管道构建了该基准，结合了现有的人工标注和基于模型的扰动。我们对11个评估模型和9个通用模型的全面研究发现，上下文信息及其评估标准对即使是最先进的模型也构成了重大挑战。例如，表现最佳的模型OpenAI的o1，其一致性准确率仅勉强达到55%。


> The large language model (LLM)-as-judge paradigm has been used to meet the demand for a cheap, reliable, and fast evaluation of model outputs during AI system development and post-deployment monitoring. While judge models -- LLMs finetuned to specialize in assessing and critiquing model outputs -- have been touted as general purpose evaluators, they are typically evaluated only on non-contextual scenarios, such as instruction following. The omission of contextual settings -- those where external information is used as context to generate an output -- is surprising given the increasing prevalence of retrieval-augmented generation (RAG) and summarization use cases. Contextual assessment is uniquely challenging, as evaluation often depends on practitioner priorities, leading to conditional evaluation criteria (e.g., comparing responses based on factuality and then considering completeness if they are equally factual). To address the gap, we propose ContextualJudgeBench, a judge benchmark with 2,000 challenging response pairs across eight splits inspired by real-world contextual evaluation scenarios. We build our benchmark with a multi-pronged data construction pipeline that leverages both existing human annotations and model-based perturbations. Our comprehensive study across 11 judge models and 9 general purpose models, reveals that the contextual information and its assessment criteria present a significant challenge to even state-of-the-art models. For example, OpenAI's o1, the best-performing model, barely reaches 55% consistent accuracy.

[Arxiv](https://arxiv.org/abs/2503.15620)