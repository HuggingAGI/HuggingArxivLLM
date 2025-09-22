# 视情况而定：借助常识知识消解有限语境下的指称歧义

发布时间：2025年09月19日

`LLM应用` `基础理论`

> It Depends: Resolving Referential Ambiguity in Minimal Contexts with Commonsense Knowledge

# 摘要

> 模糊词汇或指代不明的表述需要对话双方解决，通常需借助共享语境和常识知识。因此，我们系统研究了大型语言模型（LLMs）能否借助常识解决多轮对话中的指代歧义，并分析了歧义未消除时的模型行为。此外，我们还探究了简化语言的请求对此能力的影响。基于全新的多语言评估数据集，我们通过LLM-as-Judge和人工标注，对DeepSeek v3、GPT-4o、Qwen3-32B、GPT-4o-mini及Llama-3.1-8B开展了测试。研究发现，当前LLMs在有效解决歧义方面表现欠佳：它们要么执着于单一解读，要么罗列所有可能指代，而非采取模糊表述或主动追问澄清。这一局限在简化提示下更为突出，导致常识推理和多样化响应策略的应用大幅减少。通过直接偏好优化（Direct Preference Optimization）微调Llama-3.1-8B，显著提升了所有请求类型下的歧义解决效果。这些结果表明，需通过更先进的微调来提升LLMs对歧义的处理能力，同时保证其在多样化沟通风格中的稳健表现。

> Ambiguous words or underspecified references require interlocutors to resolve them, often by relying on shared context and commonsense knowledge. Therefore, we systematically investigate whether Large Language Models (LLMs) can leverage commonsense to resolve referential ambiguity in multi-turn conversations and analyze their behavior when ambiguity persists. Further, we study how requests for simplified language affect this capacity. Using a novel multilingual evaluation dataset, we test DeepSeek v3, GPT-4o, Qwen3-32B, GPT-4o-mini, and Llama-3.1-8B via LLM-as-Judge and human annotations. Our findings indicate that current LLMs struggle to resolve ambiguity effectively: they tend to commit to a single interpretation or cover all possible references, rather than hedging or seeking clarification. This limitation becomes more pronounced under simplification prompts, which drastically reduce the use of commonsense reasoning and diverse response strategies. Fine-tuning Llama-3.1-8B with Direct Preference Optimization substantially improves ambiguity resolution across all request types. These results underscore the need for advanced fine-tuning to improve LLMs' handling of ambiguity and to ensure robust performance across diverse communication styles.

[Arxiv](https://arxiv.org/abs/2509.16107)