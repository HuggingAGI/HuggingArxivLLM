# MAG-V：一种用于合成数据生成与验证的多智能体框架

发布时间：2024年11月28日

`Agent` `客户服务`

> MAG-V: A Multi-Agent Framework for Synthetic Data Generation and Verification

# 摘要

> 将大型语言模型（LLMs）与用于环境交互的函数或工具相结合，催生了代理范式。在行业中，由于领域数据稀缺、对专有客户数据的法律限制、业务需求快速变化以及需要为新助手制作原型，训练LLM往往不可行。代理依靠底层LLM的零样本推理能力，利用工具探索、推理客户数据并响应用户请求，为上述难题提供了精妙的解决方案。但这里存在两个问题：（I）获取大规模客户查询用于代理测试很耗时；（II）高度依赖代理响应用户查询时的工具调用序列（或轨迹）可能导致意外或错误行为。为此，我们提出了MAG-V这一多代理框架，首先生成模拟客户查询的问题数据集，其次从响应中逆向推出替代问题以进行轨迹验证。初步结果显示，我们的合成数据能提升代理处理实际客户查询的性能。此外，我们受远程监督启发并使用传统机器学习（ML）模型的轨迹验证方法，准确性比GPT-4o法官基线高11%，在我们构建的数据集中与GPT-4法官的表现相当。总之，我们的方法朝着将不同任务代理统一到一个有凝聚力的框架中以实现一致目标迈进了一步。

> Extending the capabilities of Large Language Models (LLMs) with functions or tools for environment interaction has led to the emergence of the agent paradigm. In industry, training an LLM is not always feasible because of the scarcity of domain data, legal holds on proprietary customer data, rapidly changing business requirements, and the need to prototype new assistants. Agents provide an elegant solution to the above by relying on the zero-shot reasoning abilities of the underlying LLM and utilizing tools to explore and reason over customer data and respond to user requests. However, there are two concerns here: (I) acquiring large scale customer queries for agent testing is time-consuming, and (II) high reliance on the tool call sequence (or trajectory) followed by the agent to respond to user queries may lead to unexpected or incorrect behavior. To address this, we propose MAG-V, a multi-agent framework to first generate a dataset of questions that mimic customer queries; and second, reverse-engineer alternate questions from the responses for trajectory verification. Initial results indicate that our synthetic data can improve agent performance on actual customer queries. Furthermore, our trajectory verification methodology, inspired by distant supervision and using traditional machine learning (ML) models, outperforms a GPT-4o judge baseline by 11% accuracy and matches the performance of a GPT-4 judge on our constructed dataset. Overall, our approach is a step towards unifying diverse task agents into a cohesive framework for achieving an aligned objective.

[Arxiv](https://arxiv.org/abs/2412.04494)