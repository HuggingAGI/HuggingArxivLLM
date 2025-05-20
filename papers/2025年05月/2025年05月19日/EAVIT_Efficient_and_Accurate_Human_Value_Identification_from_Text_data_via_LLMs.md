# EAVIT：利用LLMs从文本数据中高效准确识别人类价值

发布时间：2025年05月19日

`LLM应用

理由：这篇论文专注于探讨大型语言模型（LLMs）在识别人类价值观方面的应用，提出了一种结合本地模型和在线模型的高效框架。它主要关注如何在实际任务中优化和应用LLMs，属于LLM应用的范畴。` `社会学` `伦理学`

> EAVIT: Efficient and Accurate Human Value Identification from Text data via LLMs

# 摘要

> 大型语言模型（LLMs）的快速发展彻底改变了多个领域，特别是在文本数据中发现人类价值观方面。尽管传统NLP模型如BERT曾用于此类任务，但新兴的GPT类LLMs在文本表示能力上表现更优。然而，在线LLMs在处理价值识别所需的长上下文时性能往往会下降，同时带来巨大的计算成本。

为应对这些挑战，我们提出EAVIT——一个结合本地可微调模型与在线黑盒LLMs优势的高效准确人类价值观识别框架。我们的框架采用了一个小型本地语言模型作为价值探测器，用于生成初步的价值估计。这些估计随后被用于构建简洁的输入提示，供在线LLMs进行准确的价值识别。

为训练价值探测器，我们引入了专门针对价值识别的基于解释的训练和数据生成技术，以及优化LLM输入提示简洁性的采样策略。与直接查询在线LLMs相比，我们的方法将输入令牌数量减少了1/6，同时始终超越传统NLP方法和其他LLM策略。

> The rapid evolution of large language models (LLMs) has revolutionized various fields, including the identification and discovery of human values within text data. While traditional NLP models, such as BERT, have been employed for this task, their ability to represent textual data is significantly outperformed by emerging LLMs like GPTs. However, the performance of online LLMs often degrades when handling long contexts required for value identification, which also incurs substantial computational costs. To address these challenges, we propose EAVIT, an efficient and accurate framework for human value identification that combines the strengths of both locally fine-tunable and online black-box LLMs. Our framework employs a value detector - a small, local language model - to generate initial value estimations. These estimations are then used to construct concise input prompts for online LLMs, enabling accurate final value identification. To train the value detector, we introduce explanation-based training and data generation techniques specifically tailored for value identification, alongside sampling strategies to optimize the brevity of LLM input prompts. Our approach effectively reduces the number of input tokens by up to 1/6 compared to directly querying online LLMs, while consistently outperforming traditional NLP methods and other LLM-based strategies.

[Arxiv](https://arxiv.org/abs/2505.12792)