# 监督式链式推理助力长上下文理解

发布时间：2025年02月18日

`LLM应用

摘要中的研究重点在于改进大型语言模型（LLMs）的长上下文理解能力，通过整合思维链推理和智能体框架，应用于金融领域，属于LLM的应用层面改进。`

> Facilitating Long Context Understanding via Supervised Chain-of-Thought Reasoning

# 摘要

> 大型语言模型 (LLMs) 近期的进展使其能够处理越来越长的序列，范围从 2K 到 2M 个令牌，甚至更长。然而，单纯延长输入序列的长度并不一定能实现有效的长上下文理解。本研究通过监督学习的方式将思维链 (CoT) 推理整合到 LLMs 中，以促进有效的长上下文理解。为此，我们引入了 LongFinanceQA，这是一个金融领域的合成数据集，旨在提升长上下文推理能力。与现有的长上下文合成数据不同，LongFinanceQA 在最终结论前包含中间的 CoT 推理过程，这促使 LLMs 进行显式的推理，从而提高长上下文理解的准确性和可解释性。为了生成合成的 CoT 推理，我们提出了基于属性驱动的智能体推理 (PAI)，这是一个模拟人类推理步骤的智能体框架，包括属性提取、检索和总结。通过在 Loong 基准上评估 GPT-4o-mini 与 PAI 的推理能力，我们发现其表现优于标准 GPT-4o-mini 20.0%。此外，我们在 LongFinanceQA 上对 LLaMA-3.1-8B-Instruct 进行微调，在 Loong 的金融子集上实现了 24.6% 的性能提升。

> Recent advances in Large Language Models (LLMs) have enabled them to process increasingly longer sequences, ranging from 2K to 2M tokens and even beyond. However, simply extending the input sequence length does not necessarily lead to effective long-context understanding. In this study, we integrate Chain-of-Thought (CoT) reasoning into LLMs in a supervised manner to facilitate effective long-context understanding. To achieve this, we introduce LongFinanceQA, a synthetic dataset in the financial domain designed to improve long-context reasoning. Unlike existing long-context synthetic data, LongFinanceQA includes intermediate CoT reasoning before the final conclusion, which encourages LLMs to perform explicit reasoning, improving accuracy and interpretability in long-context understanding. To generate synthetic CoT reasoning, we propose Property-driven Agentic Inference (PAI), an agentic framework that simulates human-like reasoning steps, including property extraction, retrieval, and summarization. We evaluate PAI's reasoning capabilities by assessing GPT-4o-mini w/ PAI on the Loong benchmark, outperforming standard GPT-4o-mini by 20.0%. Furthermore, we fine-tune LLaMA-3.1-8B-Instruct on LongFinanceQA, achieving a 24.6% gain on Loong's financial subset.

[Arxiv](https://arxiv.org/abs/2502.13127)