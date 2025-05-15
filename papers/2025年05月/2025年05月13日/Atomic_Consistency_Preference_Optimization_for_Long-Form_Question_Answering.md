# 长文本问答中的原子一致性偏好优化

发布时间：2025年05月13日

`LLM理论` `问答系统`

> Atomic Consistency Preference Optimization for Long-Form Question Answering

# 摘要

> 大型语言模型（LLMs）常会产生看似合理却错误的事实性幻觉。为解决这一问题，模型对齐是一种常见策略，通过训练筛选后的事实与非事实配对来提升准确性。然而，这种方法通常依赖于更强的模型或外部知识库，这些资源并非总能获取。为此，我们提出了一种无需外部监督的自监督偏好微调方法——原子一致性偏好优化（ACPO）。该方法利用多个随机响应中个体事实的一致性，识别高质量和低质量的数据对，从而实现模型对齐。ACPO无需昂贵的GPT调用，提供了一种高效且可扩展的提升事实性问答性能的方案。实验结果表明，尽管是自监督方法，ACPO在LongFact和BioGen数据集上比有监督对齐基线FactAlign高出1.95分，充分证明了其在无需依赖外部模型或知识库的情况下增强事实可靠性的有效性。

> Large Language Models (LLMs) frequently produce factoid hallucinations - plausible yet incorrect answers. A common mitigation strategy is model alignment, which improves factual accuracy by training on curated factual and non-factual pairs. However, this approach often relies on a stronger model (e.g., GPT-4) or an external knowledge base to assess factual correctness, which may not always be accessible. To address this, we propose Atomic Consistency Preference Optimization (ACPO), a self-supervised preference-tuning method that enhances factual accuracy without external supervision. ACPO leverages atomic consistency signals, i.e., the agreement of individual facts across multiple stochastic responses, to identify high- and low-quality data pairs for model alignment. By eliminating the need for costly GPT calls, ACPO provides a scalable and efficient approach to improving factoid question-answering. Despite being self-supervised, empirical results demonstrate that ACPO outperforms FactAlign, a strong supervised alignment baseline, by 1.95 points on the LongFact and BioGen datasets, highlighting its effectiveness in enhancing factual reliability without relying on external models or knowledge bases.

[Arxiv](https://arxiv.org/abs/2505.09039)