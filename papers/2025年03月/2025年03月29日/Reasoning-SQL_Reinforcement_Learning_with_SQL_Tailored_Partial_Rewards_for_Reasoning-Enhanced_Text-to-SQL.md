# 推理SQL：通过为SQL量身定制的部分奖励机制进行强化学习，提升文本到SQL转换的推理能力。

发布时间：2025年03月29日

`LLM应用` `数据库` `人工智能`

> Reasoning-SQL: Reinforcement Learning with SQL Tailored Partial Rewards for Reasoning-Enhanced Text-to-SQL

# 摘要

> Text-to-SQL 是一个涉及自然语言理解、数据库模式解析和精确 SQL 查询生成的复杂任务。现有方法往往依赖于手工设计的推理路径，这些路径可能因归纳偏见而影响整体效果。受 DeepSeek R1 和 OpenAI o1 等推理增强模型的启发，我们为 Text-to-SQL 任务设计了一套专门的部分奖励机制。这套奖励包括模式链接、AI 反馈、n-gram 相似性和语法检查，旨在解决强化学习 (RL) 中的奖励稀疏性问题。通过组相对策略优化 (GRPO)，我们引导大型语言模型 (LLMs) 培养生成准确 SQL 查询所需的内在推理能力。实验表明，与监督微调 (SFT) 相比，仅使用我们的奖励进行 RL 训练的模型在准确性和泛化能力上均有显著提升。特别是，我们的 14B 参数 RL 模型在 BIRD 基准上超越了 o3-mini 和 Gemini-1.5-Pro-002 等大型专有模型，分别高出 4% 和 3%。这充分证明了我们提出的部分奖励 RL 训练框架在提升 Text-to-SQL 任务效果方面的显著优势。

> Text-to-SQL is a challenging task involving multiple reasoning-intensive subtasks, including natural language understanding, database schema comprehension, and precise SQL query formulation. Existing approaches often rely on handcrafted reasoning paths with inductive biases that can limit their overall effectiveness. Motivated by the recent success of reasoning-enhanced models such as DeepSeek R1 and OpenAI o1, which effectively leverage reward-driven self-exploration to enhance reasoning capabilities and generalization, we propose a novel set of partial rewards tailored specifically for the Text-to-SQL task. Our reward set includes schema-linking, AI feedback, n-gram similarity, and syntax check, explicitly designed to address the reward sparsity issue prevalent in reinforcement learning (RL). Leveraging group relative policy optimization (GRPO), our approach explicitly encourages large language models (LLMs) to develop intrinsic reasoning skills necessary for accurate SQL query generation. With models of different sizes, we demonstrate that RL-only training with our proposed rewards consistently achieves higher accuracy and superior generalization compared to supervised fine-tuning (SFT). Remarkably, our RL-trained 14B-parameter model significantly outperforms larger proprietary models, e.g. o3-mini by 4% and Gemini-1.5-Pro-002 by 3% on the BIRD benchmark. These highlight the efficacy of our proposed RL-training framework with partial rewards for enhancing both accuracy and reasoning capabilities in Text-to-SQL tasks.

[Arxiv](https://arxiv.org/abs/2503.23157)