# 课程到技能：LLM 课程分析性能评估

发布时间：2025年05月04日

`LLM应用` `课程分析`

> From Course to Skill: Evaluating LLM Performance in Curricular Analytics

# 摘要

> 课程分析（CA）——通过对课程数据进行系统分析，以指导项目和课程的完善——正日益成为一种越来越有价值的工具，帮助教育机构将学术课程与不断变化的社会和经济需求相匹配。大型语言模型（LLMs）在处理大规模、非结构化的课程数据方面展现出巨大潜力，但目前尚不清楚LLMs能否可靠地执行课程分析任务。本文系统评估了四种基于LLMs或传统NLP方法的文本对齐策略，用于技能提取这一课程分析的核心任务。通过分层抽样的400份不同类型的课程文件以及人-LLM协作评估框架，我们发现检索增强生成（RAG）在所有类型的课程文件中表现最佳，而零样本提示在大多数情况下表现不如传统NLP方法。我们的研究结果突显了LLMs在分析简短和抽象课程文件方面的潜力，但也揭示了其性能可能因模型选择和提示策略而显著变化。这凸显了在大规模部署之前，谨慎评估基于LLMs的策略性能的重要性。


> Curricular analytics (CA) -- systematic analysis of curricula data to inform program and course refinement -- becomes an increasingly valuable tool to help institutions align academic offerings with evolving societal and economic demands. Large language models (LLMs) are promising for handling large-scale, unstructured curriculum data, but it remains uncertain how reliably LLMs can perform CA tasks. In this paper, we systematically evaluate four text alignment strategies based on LLMs or traditional NLP methods for skill extraction, a core task in CA. Using a stratified sample of 400 curriculum documents of different types and a human-LLM collaborative evaluation framework, we find that retrieval-augmented generation (RAG) to be the top-performing strategy across all types of curriculum documents, while zero-shot prompting performs worse than traditional NLP methods in most cases. Our findings highlight the promise of LLMs in analyzing brief and abstract curriculum documents, but also reveal that their performance can vary significantly depending on model selection and prompting strategies. This underscores the importance of carefully evaluating the performance of LLM-based strategies before large-scale deployment.

[Arxiv](https://arxiv.org/abs/2505.02324)