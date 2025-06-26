# QueueEDIT：用于大型语言模型中序列模型编辑的结构化自我修正方法

发布时间：2025年06月21日

`LLM理论` `模型编辑` `模型优化`

> QueueEDIT: Structural Self-Correction for Sequential Model Editing in LLMs

# 摘要

> 大型语言模型（LLMs）近期表现卓越，但幻觉问题依旧存在。为修正LLMs的事实性错误，模型编辑技术应运而生。其中，顺序模型编辑（SME）作为一项具挑战性的技术，致力于持续修正错误而非一次性解决。然而，SME过程中引入的新参数可能损害LLMs的通用能力。本文提出了一种基于队列的自修正框架（QueueEDIT），该框架通过解决长序列依赖性提升SME性能，同时有效缓解参数偏见对LLMs通用能力的影响。具体而言，我们引入结构映射编辑损失，将三元组映射至LLMs Transformer层中的知识敏感神经元。随后，我们将每条编辑知识对应的参数存储于队列中，并动态对齐历史编辑参数。在每次编辑时，系统会自动选择与当前参数最相关的队列参数，判断是否需要重新对齐历史知识。队列中不相关的参数会被冻结，确保更新仅限于队列头部，避免影响模型的通用能力。实验结果表明，我们的框架在各类SME场景下显著超越现有方法，单轮编辑表现同样出色。经过SME过程的LLMs在各类NLP任务中始终保持高水平能力。

> Recently, large language models (LLMs) have demonstrated impressive results but still suffer from hallucinations. Model editing has been proposed to correct factual inaccuracies in LLMs. A challenging case is sequential model editing (SME), which aims to rectify errors continuously rather than treating them as a one-time task. During SME, the general capabilities of LLMs can be negatively affected due to the introduction of new parameters. In this paper, we propose a queue-based self-correction framework (QueueEDIT) that not only enhances SME performance by addressing long-sequence dependency but also mitigates the impact of parameter bias on the general capabilities of LLMs. Specifically, we first introduce a structural mapping editing loss to map the triplets to the knowledge-sensitive neurons within the Transformer layers of LLMs. We then store the located parameters for each piece of edited knowledge in a queue and dynamically align previously edited parameters. In each edit, we select queue parameters most relevant to the currently located parameters to determine whether previous knowledge needs realignment. Irrelevant parameters in the queue are frozen, and we update the parameters at the queue head to the LLM to ensure they do not harm general abilities. Experiments show that our framework significantly outperforms strong baselines across various SME settings and maintains competitiveness in single-turn editing. The resulting LLMs also preserve high capabilities in general NLP tasks throughout the SME process.

[Arxiv](https://arxiv.org/abs/2506.17864)