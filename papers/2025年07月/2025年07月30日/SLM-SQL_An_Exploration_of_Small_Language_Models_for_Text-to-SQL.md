# SLM-SQL：小型语言模型在文本到SQL任务中的探索与实践

发布时间：2025年07月30日

`LLM应用` `数据库管理`

> SLM-SQL: An Exploration of Small Language Models for Text-to-SQL

# 摘要

> 大型语言模型（LLMs）在Text-to-SQL任务中表现出色，但参数量在0.5B到1.5B之间的小语言模型（SLMs）由于逻辑推理能力有限，目前在该任务上表现不佳。不过，SLMs在推理速度和边缘部署方面具有优势。为了挖掘其潜力，我们借助最新的后训练技术，基于开源的SynSQL-2.5M数据集构建了两个衍生数据集：用于SQL生成的SynSQL-Think-916K和用于SQL合并修订的SynSQL-Merge-Think-310K。通过监督微调和强化学习对SLM进行后训练，并采用修正自洽方法进行推理。实验结果表明，我们的SLM-SQL方法有效且具有良好的泛化能力。在BIRD开发集上，五个评估模型的平均提升了31.4分。其中，0.5B模型达到了56.87%的执行准确率（EX），而1.5B模型实现了67.08%的EX。我们将数据集、模型和代码发布到GitHub：https://github.com/CycloneBoy/slm_sql。

> Large language models (LLMs) have demonstrated strong performance in translating natural language questions into SQL queries (Text-to-SQL). In contrast, small language models (SLMs) ranging from 0.5B to 1.5B parameters currently underperform on Text-to-SQL tasks due to their limited logical reasoning capabilities. However, SLMs offer inherent advantages in inference speed and suitability for edge deployment. To explore their potential in Text-to-SQL applications, we leverage recent advancements in post-training techniques. Specifically, we used the open-source SynSQL-2.5M dataset to construct two derived datasets: SynSQL-Think-916K for SQL generation and SynSQL-Merge-Think-310K for SQL merge revision. We then applied supervised fine-tuning and reinforcement learning-based post-training to the SLM, followed by inference using a corrective self-consistency approach. Experimental results validate the effectiveness and generalizability of our method, SLM-SQL. On the BIRD development set, the five evaluated models achieved an average improvement of 31.4 points. Notably, the 0.5B model reached 56.87\% execution accuracy (EX), while the 1.5B model achieved 67.08\% EX. We will release our dataset, model, and code to github: https://github.com/CycloneBoy/slm_sql.

[Arxiv](https://arxiv.org/abs/2507.22478)