# 概念性的上下文学习与概念链：借助大型语言模型攻克复杂的概念性难题

发布时间：2024年12月19日

`LLM应用`

> Conceptual In-Context Learning and Chain of Concepts: Solving Complex Conceptual Problems Using Large Language Models

# 摘要

> 科学和工程问题属于复杂的概念性问题范畴，解决这类问题需要特定的概念信息（CI），比如数学/逻辑相关的知识技能、过程信息或者工程指南。大型语言模型（LLMs）因其对推进工程和科学任务（如辅助解决问题）的作用，有望成为解决此类复杂概念性问题的利器。然而，在开放世界数据上训练的普通 LLMs 缺少必要的 CI。在本研究中，我们专门探索了用于解决复杂概念问题的 LLMs 浅层定制方法（SCMs）。我们为 LLMs 提出了两种新颖的 SCM 算法，即概念性上下文学习（C-ICL）和概念链（CoC），用 CI 增强 LLMs ，使其能够解决复杂的概念问题。本文所处理的问题是依据数据建模指南中的概念信息，在工程/工业领域生成专有数据模型。我们依据与语法和语义正确性、时间及成本相关的四个评估指标，在不同规模的 OpenAI LLMs 上对我们的算法进行评估。所提出的算法比当前流行的 LLMs 的 SCMs（如上下文学习（ICL）和思维链（CoT））表现更优。观察发现，与 CoT 相比，新的 SCMs C-ICL 和 CoC 的响应正确性分别提高了 30.6％和 29.88％。定性分析表明，所提出的新 SCMs 激活了 LLMs 中以往在现有 SCMs 中未被发现的新兴能力，让问题解决过程更透明，减少了幻觉以及模型响应从提示中复制示例（模仿）的倾向。

> Science and engineering problems fall in the category of complex conceptual problems that require specific conceptual information (CI) like math/logic -related know-how, process information, or engineering guidelines to solve them. Large Language Models (LLMs) are promising agents to solve such complex conceptual problems due to their implications in advancing engineering and science tasks like assisted problem-solving. But vanilla LLMs, trained on open-world data, lack the necessary CI. In this work, we specifically explore shallow customization methods (SCMs) of LLMs for solving complex conceptual problems. We propose two novel SCM algorithms for LLM, to augment LLMs with CI and enable LLMs to solve complex conceptual problems: Conceptual In-Context Learning (C-ICL) and Chain of Concepts (CoC). The problem tackled in this paper is generation of proprietary data models in the engineering/industry domain based on conceptual information in data modelling guidelines. We evaluate our algorithms on varied sizes of the OpenAI LLMs against four evaluation metrics related to syntactic and semantic correctness, time and cost incurred. The proposed algorithms perform better than currently popular LLM SCMs like In-context Learning (ICL) and Chain of Thoughts (CoT). It was observed that as compared to CoT, response correctness increased by 30.6% and 29.88% for the new SCMs C-ICL and CoC respectively. Qualitative analysis suggests that the proposed new SCMs activate emergent capabilities in LLMs, previously unobserved in the existing SCMs. They make problem-solving processes more transparent and reduce hallucinations and the tendency of model responses to copy examples from prompts (parroting).

[Arxiv](https://arxiv.org/abs/2412.15309)