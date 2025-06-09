# 大语言模型真的会遗忘吗？基于知识相关性和置信度感知的遗忘机制评估

发布时间：2025年06月06日

`LLM理论

理由：这篇论文探讨了大型语言模型中的知识遗忘问题，提出了新的评估框架和方法，属于理论研究。` `机器学习` `人工智能`

> Do LLMs Really Forget? Evaluating Unlearning with Knowledge Correlation and Confidence Awareness

# 摘要

> 机器学习中的知识遗忘技术旨在缓解大型语言模型（LLMs）中的意外记忆问题。然而，现有方法主要集中在显式删除孤立的事实，往往忽视了潜在的推理依赖和LLMs中知识的非确定性本质。因此，被认为已被遗忘的事实可能通过相关联的信息隐性地持续存在。

为了解决这些挑战，我们提出了一种知识遗忘评估框架，通过将相关事实背景表示为带有置信度分数的知识图谱，更准确地捕捉现实世界知识的隐性结构。我们进一步开发了一种基于推理的评估协议，利用强大的LLMs作为评估者；这些评估者通过对提取的知识子图进行推理来判断遗忘是否成功。我们的LLM评估者采用了精心设计的提示，并通过与人工评估的对比校准，以确保其可靠性和稳定性。

在我们新构建的基准数据集上进行的大量实验表明，我们的框架能够对遗忘性能进行更现实和严格的评估。此外，我们的研究发现，当前的评估策略往往高估了遗忘的有效性。我们的代码已公开发布在https://github.com/Graph-COM/Knowledge_Unlearning.git。

> Machine unlearning techniques aim to mitigate unintended memorization in large language models (LLMs). However, existing approaches predominantly focus on the explicit removal of isolated facts, often overlooking latent inferential dependencies and the non-deterministic nature of knowledge within LLMs. Consequently, facts presumed forgotten may persist implicitly through correlated information. To address these challenges, we propose a knowledge unlearning evaluation framework that more accurately captures the implicit structure of real-world knowledge by representing relevant factual contexts as knowledge graphs with associated confidence scores. We further develop an inference-based evaluation protocol leveraging powerful LLMs as judges; these judges reason over the extracted knowledge subgraph to determine unlearning success. Our LLM judges utilize carefully designed prompts and are calibrated against human evaluations to ensure their trustworthiness and stability. Extensive experiments on our newly constructed benchmark demonstrate that our framework provides a more realistic and rigorous assessment of unlearning performance. Moreover, our findings reveal that current evaluation strategies tend to overestimate unlearning effectiveness. Our code is publicly available at https://github.com/Graph-COM/Knowledge_Unlearning.git.

[Arxiv](https://arxiv.org/abs/2506.05735)