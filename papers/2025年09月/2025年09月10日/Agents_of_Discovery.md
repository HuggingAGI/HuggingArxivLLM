# 发现智能体

发布时间：2025年09月10日

`Agent` `基础理论`

> Agents of Discovery

# 摘要

> 现代粒子物理及其他基础物理研究领域的海量数据，促使研究者采用（且必须依赖）日益复杂的数据分析工具与工作流。尽管机器学习（ML）工具在数据分析中的应用近年呈爆发式增长，但这些工具多为专用算法，往往需依赖编码的物理知识才能实现最优性能。本研究另辟蹊径，探索一个全新方向：借助大型语言模型（LLMs）的最新进展，构建由智能体组成的协作团队——即承担特定子任务的LLM实例——以类人科研的方式协同解决数据分析类研究问题。具体而言，智能体通过编写代码调用标准工具与库（含ML系统），并基于迭代结果持续优化。若研发成功，这类智能体系统有望自动化常规分析环节，从而应对现代工具链愈发复杂的挑战。为验证当前商用LLM的能力，我们基于公开且广受研究的LHC Olympics数据集，开展异常检测任务测试，涉及OpenAI的多款模型（GPT-4o、o4-mini、GPT-4.1及GPT-5）并验证了其稳定性。结果显示，该智能体系统不仅能独立完成数据分析任务，其生成的最优方案性能更是媲美人类顶尖水平。

> The substantial data volumes encountered in modern particle physics and other domains of fundamental physics research allow (and require) the use of increasingly complex data analysis tools and workflows. While the use of machine learning (ML) tools for data analysis has recently proliferated, these tools are typically special-purpose algorithms that rely, for example, on encoded physics knowledge to reach optimal performance. In this work, we investigate a new and orthogonal direction: Using recent progress in large language models (LLMs) to create a team of agents -- instances of LLMs with specific subtasks -- that jointly solve data analysis-based research problems in a way similar to how a human researcher might: by creating code to operate standard tools and libraries (including ML systems) and by building on results of previous iterations. If successful, such agent-based systems could be deployed to automate routine analysis components to counteract the increasing complexity of modern tool chains. To investigate the capabilities of current-generation commercial LLMs, we consider the task of anomaly detection via the publicly available and highly-studied LHC Olympics dataset. Several current models by OpenAI (GPT-4o, o4-mini, GPT-4.1, and GPT-5) are investigated and their stability tested. Overall, we observe the capacity of the agent-based system to solve this data analysis problem. The best agent-created solutions mirror the performance of human state-of-the-art results.

[Arxiv](https://arxiv.org/abs/2509.08535)