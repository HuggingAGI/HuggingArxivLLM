# CogniSQL-R1-Zero：轻量化强化推理，助力高效SQL生成

发布时间：2025年07月08日

`LLM应用` `数据库`

> CogniSQL-R1-Zero: Lightweight Reinforced Reasoning for Efficient SQL Generation

# 摘要

> 自然语言到SQL（Text-to-SQL）的转换仍是语言理解与结构化数据访问交叉领域中的核心挑战。尽管大型语言模型（LLMs）提升了生成的流畅性，但准确生成可执行SQL，尤其是处理复杂查询，依然充满挑战。我们推出CogniSQL-R1-Zero，这是一个基于强化学习（RL）的框架和模型，利用轻量级奖励信号（基于执行正确性和格式标签合规性）生成准确SQL。通过摒弃中间监督、混合管道和复杂奖励塑造，我们的方法促进稳定学习，与最终目标——生成可执行程序——保持高度对齐。CogniSQL-R1-Zero在Text2SQL基准测试BIRD bench中实现最佳执行准确性，超越了包括SFT CodeS-7B、DeepSeek-Coder 236B和Mistral 123B在内的现有监督学习和指令微调基线——尽管其7B规模远小于现有模型。这一成果彰显了我们在仅使用四块NVIDIA A100 GPU（每块40 GB VRAM）训练时，基于RL方法的可扩展性和效率。为推动高效且可解释的Text-to-SQL建模研究，我们发布了两个整理数据集：(i) 包含5,024条推理轨迹的数据集，涵盖不同上下文长度；(ii) 包含36,356条弱监督查询的正样本语料库，每条查询标注了六种语义多样的推理路径。这些贡献共同推动了与执行目标对齐的可扩展Text-to-SQL生成。

> Translating natural language into SQL (Text-to-SQL) remains a core challenge at the intersection of language understanding and structured data access. Although large language models (LLMs) have improved fluency, generating correct and executable SQL, especially for complex queries, continues to be challenging. We introduce CogniSQL-R1-Zero, a reinforcement learning (RL) framework and model that produces accurate SQL using a lightweight reward signal based on execution correctness and format-tag compliance. By avoiding intermediate supervision, hybrid pipelines and complex reward shaping, our method encourages stable learning and stronger alignment with the ultimate task objective-producing executable programs. CogniSQL-R1-Zero achieves state-of-the-art execution accuracy on Text2SQL benchmark; BIRD bench, outperforming prior supervised and instruction-tuned baselines including SFT CodeS-7B, DeepSeek-Coder 236B, and Mistral 123B-despite being trained on a significantly smaller 7B backbone. This result underscores the scalability and efficiency of our RL-based approach when trained on just four NVIDIA A100 GPUs (40 GB VRAM each). To support further research in efficient and interpretable Text-to-SQL modeling, we release two curated datasets: (i) a collection of 5,024 reasoning traces with varying context lengths, and (ii) a positive-sampled corpus of 36,356 corpus of weakly supervised queries, each annotated with six semantically diverse reasoning paths. Together, these contributions advance scalable, execution-aligned Text-to-SQL generation.

[Arxiv](https://arxiv.org/abs/2507.06013)