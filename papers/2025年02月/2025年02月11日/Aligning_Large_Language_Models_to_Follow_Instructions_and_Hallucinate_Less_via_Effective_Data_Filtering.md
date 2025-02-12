# 通过有效数据过滤对齐大型语言模型，使其更少生成幻觉并遵循指令

发布时间：2025年02月11日

`LLM理论` `人工智能`

> Aligning Large Language Models to Follow Instructions and Hallucinate Less via Effective Data Filtering

# 摘要

> 在 LLM 的指令微调过程中，使用包含陌生知识的数据进行训练会导致模型过于自信并鼓励产生幻觉。为了解决这一问题，我们提出了一个全新的框架 NOVA，该框架通过识别与 LLM 已有知识高度契合的高质量数据来减少幻觉现象。NOVA 包含两个关键组件：内部一致性探测（ICP）和语义等价识别（SEI），用于评估 LLM 对指令数据的熟悉程度。具体而言，ICP 通过计算多个自生成响应之间的定制一致性来衡量 LLM 对给定指令的理解深度。SEI 则进一步通过比较目标响应与生成响应，结合语义聚类和投票策略，评估 LLM 对目标响应的熟悉程度。此外，我们引入了一个与专家对齐的奖励模型，综合考虑了超越熟悉度的其他特征，以进一步提升数据质量。通过注重数据质量并避免使用陌生数据，我们可以利用筛选后的数据有效对齐 LLM，使其更好地遵循指令并显著减少幻觉现象。大量实验和分析结果表明，NOVA 在减少幻觉方面表现出色，同时保持了 LLM 强大的遵循指令能力。

> Training LLMs on data that contains unfamiliar knowledge during the instruction tuning stage can make LLMs overconfident and encourage hallucinations. To address this challenge, we introduce a novel framework, NOVA, which identifies high-quality data that aligns well with the LLM's learned knowledge to reduce hallucinations. NOVA includes Internal Consistency Probing (ICP) and Semantic Equivalence Identification (SEI) to measure how familiar the LLM is with instruction data. Specifically, ICP evaluates the LLM's understanding of the given instruction by calculating the tailored consistency among multiple self-generated responses. SEI further assesses the familiarity of the LLM with the target response by comparing it to the generated responses, using the proposed semantic clustering and well-designed voting strategy. Finally, we introduce an expert-aligned reward model, considering characteristics beyond just familiarity to enhance data quality. By considering data quality and avoiding unfamiliar data, we can utilize the selected data to effectively align LLMs to follow instructions and hallucinate less. Extensive experiments and analysis show that NOVA significantly reduces hallucinations and allows LLMs to maintain a strong ability to follow instructions.

[Arxiv](https://arxiv.org/abs/2502.07340)