# 随机性悖论：变温LLM输出中结构化虚构数据的创造力限制与计算解耦

发布时间：2025年02月12日

`LLM应用` `合成数据生成` `模型优化`

> The Paradox of Stochasticity: Limited Creativity and Computational Decoupling in Temperature-Varied LLM Outputs of Structured Fictional Data

# 摘要

> 本研究深入探讨了温度设置与模型架构对三款大型语言模型（LLMs）生成结构化虚构数据（如姓名、出生日期）的影响，涉及的模型包括llama3.1:8b、deepseek-r1:8b和mistral:latest。通过系统性地测试从0.0到1.0（以0.1为增量）的温度值，我们进行了330次试验，成功生成并验证了889个结构化实体的句法一致性。研究发现，模型架构对计算效率的影响至关重要，其中mistral:latest和llama3.1:8b的数据处理速度比deepseek-r1:8b快8倍。令人意外的是，温度设置与处理时间之间并无明显关联，这一发现挑战了关于随机采样成本的传统假设。尽管输出多样性有限，所有模型在不同温度设置下均倾向于生成常见姓名原型（如'John Doe'和'Jane Smith'），但罕见名字在中等温度值（0.3-0.7）下出现频率较高。这些结果表明，在结构化生成任务中，架构优化相较于温度调整更具决定性影响。研究强调，在效率优先的情况下，应将模型选择置于超参数调优之上，并建议在合成数据管道中引入显式多样性约束以缓解默认输出偏差。

> This study examines how temperature settings and model architectures affect the generation of structured fictional data (names, birthdates) across three large language models (LLMs): llama3.1:8b, deepseek-r1:8b, and mistral:latest. By systematically testing temperature values from 0.0 to 1.0 in increments of 0.1, we conducted 330 trials yielding 889 structured entities, validated for syntactic consistency. Key findings reveal that model architecture significantly influences computational efficiency, with mistral:latest and llama3.1:8b processing data 8x faster than deepseek-r1:8b. Contrary to expectations, temperature showed no correlation with processing time, challenging assumptions about stochastic sampling costs. Output diversity remained limited, as models consistently defaulted to common name archetypes (e.g., 'John Doe' and 'Jane Smith') across all temperatures, though rare names clustered at intermediate values (0.3-0.7). These results demonstrate that architectural optimizations, rather than temperature adjustments, dominate performance in structured generation tasks. The findings emphasize prioritizing model selection over hyperparameter tuning for efficiency and suggest explicit diversity constraints are necessary to mitigate default output biases in synthetic data pipelines.

[Arxiv](https://arxiv.org/abs/2502.08515)