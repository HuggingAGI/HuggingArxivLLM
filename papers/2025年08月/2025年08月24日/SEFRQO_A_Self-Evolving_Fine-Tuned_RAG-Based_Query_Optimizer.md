# SEFRQO：自进化微调的基于RAG的查询优化器

发布时间：2025年08月24日

`RAG` `基础理论`

> SEFRQO: A Self-Evolving Fine-Tuned RAG-Based Query Optimizer

# 摘要

> 查询优化是数据库系统中一个研究数十年的核心问题。学习型查询优化器（LQOs）虽能通过整合反馈不断提升性能，但存在冷启动难题，且在工作负载变化或模式变更时往往需要重新训练。近年来，基于LLM的查询优化器借助预训练和微调的LLM缓解了这些问题，却忽略了LLM的上下文学习能力及执行记录作为持续进化反馈的价值。本文提出SEFRQO——一种自进化微调RAG基查询优化器。SEFRQO依托检索增强生成（RAG）框架，通过持续学习执行反馈来攻克LQOs的冷启动瓶颈。我们通过监督微调和强化微调双管齐下，让LLM生成语法正确且性能优异的查询提示。更重要的是，SEFRQO还善用LLM的上下文学习能力，动态构建提示——参考相似查询及同一查询的历史执行记录。这种自进化模式通过迭代优化提示，不断压低查询执行延迟。实验显示，SEFRQO性能超越现有最先进的LQOs：在CEB和Stack工作负载上，相较PostgreSQL，查询延迟分别降低65.05%和93.57%。

> Query optimization is a crucial problem in database systems that has been studied for decades. Learned query optimizers (LQOs) can improve performance over time by incorporating feedback; however, they suffer from cold-start issues and often require retraining when workloads shift or schemas change. Recent LLM-based query optimizers leverage pre-trained and fine-tuned LLMs to mitigate these challenges. Nevertheless, they neglect LLMs' in-context learning and execution records as feedback for continuous evolution. In this paper, we present SEFRQO, a Self-Evolving Fine-tuned RAG-based Query Optimizer. SEFRQO mitigates the cold-start problem of LQOs by continuously learning from execution feedback via a Retrieval-Augmented Generation (RAG) framework. We employ both supervised fine-tuning and reinforcement fine-tuning to prepare the LLM to produce syntactically correct and performance-efficient query hints. Moreover, SEFRQO leverages the LLM's in-context learning capabilities by dynamically constructing prompts with references to similar queries and the historical execution record of the same query. This self-evolving paradigm iteratively optimizes the prompt to minimize query execution latency. Evaluations show that SEFRQO outperforms state-of-the-art LQOs, achieving up to 65.05% and 93.57% reductions in query latency on the CEB and Stack workloads, respectively, compared to PostgreSQL.

[Arxiv](https://arxiv.org/abs/2508.17556)