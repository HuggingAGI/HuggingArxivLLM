# “Review-Then-Refine”：具备时间适应性的多跳问答动态框架

发布时间：2024年12月19日

`RAG` `问答系统` `多跳问答`

> Review-Then-Refine: A Dynamic Framework for Multi-Hop Question Answering with Temporal Adaptability

# 摘要

> 检索增强生成（RAG）框架已成为解决多跳问答（QA）任务的颇具前景的方案，因其能让大型语言模型（LLMs）融入外部知识，弥补自身知识的不足。尽管如此，现有的 RAG 框架通常遵循“先检索后读取”的模式，在处理含时间信息的多跳问答时常常遭遇困境，难以检索和整合准确的时间相关信息。为应对这一挑战，本文提出了一个新颖的“先审查后改进”框架，旨在提升具有时间信息的多跳问答场景中 LLM 的表现。我们的方法始于审查阶段，在此阶段，分解的子查询会依据时间信息动态重写，便于后续的自适应检索和推理流程。另外，我们采用自适应检索机制，尽量减少不必要的检索，从而降低产生幻觉的可能。在后续的改进阶段，LLM 把每个子查询检索到的信息与自身的内部知识相融合，形成一个连贯的答案。在多个数据集上的大量实验结果表明了我们所提出框架的有效性，凸显了其大幅提升 LLM 多跳问答能力的潜力。

> Retrieve-augmented generation (RAG) frameworks have emerged as a promising solution to multi-hop question answering(QA) tasks since it enables large language models (LLMs) to incorporate external knowledge and mitigate their inherent knowledge deficiencies. Despite this progress, existing RAG frameworks, which usually follows the retrieve-then-read paradigm, often struggle with multi-hop QA with temporal information since it has difficulty retrieving and synthesizing accurate time-related information. To address the challenge, this paper proposes a novel framework called review-then-refine, which aims to enhance LLM performance in multi-hop QA scenarios with temporal information. Our approach begins with a review phase, where decomposed sub-queries are dynamically rewritten with temporal information, allowing for subsequent adaptive retrieval and reasoning process. In addition, we implement adaptive retrieval mechanism to minimize unnecessary retrievals, thus reducing the potential for hallucinations. In the subsequent refine phase, the LLM synthesizes the retrieved information from each sub-query along with its internal knowledge to formulate a coherent answer. Extensive experimental results across multiple datasets demonstrate the effectiveness of our proposed framework, highlighting its potential to significantly improve multi-hop QA capabilities in LLMs.

[Arxiv](https://arxiv.org/abs/2412.15101)