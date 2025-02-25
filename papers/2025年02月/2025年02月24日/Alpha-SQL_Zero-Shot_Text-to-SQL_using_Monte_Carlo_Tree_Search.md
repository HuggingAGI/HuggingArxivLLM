# Alpha-SQL：通过蒙特卡洛树搜索实现零样本文本到SQL转换

发布时间：2025年02月24日

`LLM应用` `数据库` `信息处理`

> Alpha-SQL: Zero-Shot Text-to-SQL using Monte Carlo Tree Search

# 摘要

> 文本到SQL技术让自然语言与数据库交互成为现实，在各行各业中发挥着关键作用。随着更强大的大型语言模型（LLMs）每隔几个月就涌现，微调成本高昂且耗时费力。于是，我们转向零样本文本到SQL，利用LLMs内置的知识和推理能力，无需额外微调，这不仅充满潜力，更具挑战性。为应对这一挑战，我们推出了Alpha-SQL，它采用蒙特卡洛树搜索（MCTS）框架，根据部分SQL状态逐步构建查询。通过将LLM作为动作模型，Alpha-SQL在搜索过程中动态生成构建动作，精准导向更优的SQL查询。同时，它还借助自我监督的奖励函数评估候选查询质量，确保生成的查询既准确又高效。实验数据显示，Alpha-SQL在BIRD开发集上表现卓越，使用未经微调的开源32B LLM，执行准确率达到69.7%。相比基于GPT-4o的最佳零样本方法，Alpha-SQL在BIRD开发集上高出2.5%。

> Text-to-SQL, which enables natural language interaction with databases, serves as a pivotal method across diverse industries. With new, more powerful large language models (LLMs) emerging every few months, fine-tuning has become incredibly costly, labor-intensive, and error-prone. As an alternative, zero-shot Text-to-SQL, which leverages the growing knowledge and reasoning capabilities encoded in LLMs without task-specific fine-tuning, presents a promising and more challenging direction. To address this challenge, we propose Alpha-SQL, a novel approach that leverages a Monte Carlo Tree Search (MCTS) framework to iteratively infer SQL construction actions based on partial SQL query states. To enhance the framework's reasoning capabilities, we introduce LLM-as-Action-Model to dynamically generate SQL construction actions during the MCTS process, steering the search toward more promising SQL queries. Moreover, Alpha-SQL employs a self-supervised reward function to evaluate the quality of candidate SQL queries, ensuring more accurate and efficient query generation. Experimental results show that Alpha-SQL achieves 69.7% execution accuracy on the BIRD development set, using a 32B open-source LLM without fine-tuning. Alpha-SQL outperforms the best previous zero-shot approach based on GPT-4o by 2.5% on the BIRD development set.

[Arxiv](https://arxiv.org/abs/2502.17248)