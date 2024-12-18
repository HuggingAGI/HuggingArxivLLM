# OmniEval：金融领域的一个全方位自动的 RAG 评估基准

发布时间：2024年12月17日

`RAG` `语言模型`

> OmniEval: An Omnidirectional and Automatic RAG Evaluation Benchmark in Financial Domain

# 摘要

> 作为大型语言模型（LLMs）的典型实用应用，检索增强生成（RAG）技术备受广泛关注，尤其在LLMs可能欠缺特定领域知识的垂直领域。本文中，我们于金融领域引入了一个全方位自动的RAG基准——OmniEval。我们的基准具有多维评估框架的特性，包含：（1）基于矩阵的RAG场景评估系统，将查询划分为五个任务类别和16个金融主题，实现对各类查询场景的结构化评估；（2）多维评估数据生成方式，融合了基于GPT-4的自动生成与人工注释，在对生成实例的人工评估中接受率达87.47％；（3）多阶段评估系统，同时评估检索和生成性能，对RAG流程进行全面评估；（4）源自基于规则和基于LLM的强大评估指标，通过人工注释和LLM评估器的监督微调提升评估的可靠性。我们的实验表明OmniEval的全面性，涵盖了广泛的测试数据集，并突显了RAG系统在不同主题和任务中的性能差异，揭示了RAG模型在垂直领域提升能力的重要契机。我们在\href{https://github.com/RUC-NLPIR/OmniEval}{https://github.com/RUC-NLPIR/OmniEval}开源了基准的代码。

> As a typical and practical application of Large Language Models (LLMs), Retrieval-Augmented Generation (RAG) techniques have gained extensive attention, particularly in vertical domains where LLMs may lack domain-specific knowledge. In this paper, we introduce an omnidirectional and automatic RAG benchmark, OmniEval, in the financial domain. Our benchmark is characterized by its multi-dimensional evaluation framework, including (1) a matrix-based RAG scenario evaluation system that categorizes queries into five task classes and 16 financial topics, leading to a structured assessment of diverse query scenarios; (2) a multi-dimensional evaluation data generation approach, which combines GPT-4-based automatic generation and human annotation, achieving an 87.47\% acceptance ratio in human evaluations on generated instances; (3) a multi-stage evaluation system that evaluates both retrieval and generation performance, result in a comprehensive evaluation on the RAG pipeline; and (4) robust evaluation metrics derived from rule-based and LLM-based ones, enhancing the reliability of assessments through manual annotations and supervised fine-tuning of an LLM evaluator. Our experiments demonstrate the comprehensiveness of OmniEval, which includes extensive test datasets and highlights the performance variations of RAG systems across diverse topics and tasks, revealing significant opportunities for RAG models to improve their capabilities in vertical domains. We open source the code of our benchmark in \href{https://github.com/RUC-NLPIR/OmniEval}{https://github.com/RUC-NLPIR/OmniEval}.

[Arxiv](https://arxiv.org/abs/2412.13018)