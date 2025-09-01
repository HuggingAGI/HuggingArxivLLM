# SEFRQO：自进化微调的基于RAG的查询优化器

发布时间：2025年08月24日

`RAG` `基础理论`

> SEFRQO: A Self-Evolving Fine-Tuned RAG-Based Query Optimizer

# 摘要

> 查询优化是数据库系统中一个研究数十年的核心问题。学习型查询优化器（LQOs）能通过整合反馈持续提升性能，但存在冷启动问题，且在工作负载变化或模式变更时往往需要重新训练。近年来，基于LLM的查询优化器借助预训练和微调的LLM缓解了这些问题，但却忽视了LLM的上下文学习能力及执行记录对持续进化的反馈作用。本文提出一种自进化微调的基于RAG的查询优化器SEFRQO（Self-Evolving Fine-tuned RAG-based Query Optimizer）。SEFRQO借助检索增强生成（RAG）框架，通过持续学习执行反馈来缓解LQOs的冷启动问题。我们通过监督微调和强化微调，让LLM生成语法正确且性能优异的查询提示。此外，SEFRQO通过动态构建参考相似查询及同一查询历史执行记录的提示，充分发挥LLM的上下文学习能力。该自进化范式通过迭代优化提示，不断降低查询执行延迟。评估结果显示，SEFRQO性能超越现有最优LQOs，在CEB和Stack工作负载上，与PostgreSQL相比查询延迟分别降低了65.05%和93.57%。

> Query optimization is a crucial problem in database systems that has been studied for decades. Learned query optimizers (LQOs) can improve performance over time by incorporating feedback; however, they suffer from cold-start issues and often require retraining when workloads shift or schemas change. Recent LLM-based query optimizers leverage pre-trained and fine-tuned LLMs to mitigate these challenges. Nevertheless, they neglect LLMs' in-context learning and execution records as feedback for continuous evolution. In this paper, we present SEFRQO, a Self-Evolving Fine-tuned RAG-based Query Optimizer. SEFRQO mitigates the cold-start problem of LQOs by continuously learning from execution feedback via a Retrieval-Augmented Generation (RAG) framework. We employ both supervised fine-tuning and reinforcement fine-tuning to prepare the LLM to produce syntactically correct and performance-efficient query hints. Moreover, SEFRQO leverages the LLM's in-context learning capabilities by dynamically constructing prompts with references to similar queries and the historical execution record of the same query. This self-evolving paradigm iteratively optimizes the prompt to minimize query execution latency. Evaluations show that SEFRQO outperforms state-of-the-art LQOs, achieving up to 65.05% and 93.57% reductions in query latency on the CEB and Stack workloads, respectively, compared to PostgreSQL.

[Arxiv](https://arxiv.org/abs/2508.17556)