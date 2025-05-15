# 基于大型语言模型的中文错误修正方案：CEC-Zero

发布时间：2025年05月13日

`LLM应用` `中文自然语言处理` `中文拼写纠正`

> CEC-Zero: Chinese Error Correction Solution Based on LLM

# 摘要

> 近期，大型语言模型（LLMs）在中文文本处理，特别是中文拼写纠正（CSC）领域展现了卓越能力。尽管LLMs在准确性和鲁棒性上超越了传统BERT模型，但可靠性和泛化性仍具挑战。本文提出CEC-Zero——一种全新的强化学习（RL）框架，使LLMs通过自主学习错误策略实现自我修正，无需外部监督。结合RL与LLMs的生成能力，该方法摆脱了对标注数据或辅助模型的依赖。实验结果表明，强化学习增强的LLMs在跨领域泛化方面达到行业适用的准确性和卓越性能，为中文NLP应用的可靠性优化提供了一种可扩展的解决方案。这一突破不仅推动了LLMs在实际中文文本纠错场景中的应用，还为自我改进的语言模型建立了新的范式。

> Recent advancements in large language models (LLMs) demonstrate exceptional Chinese text processing capabilities, particularly in Chinese Spelling Correction (CSC). While LLMs outperform traditional BERT-based models in accuracy and robustness, challenges persist in reliability and generalization. This paper proposes CEC-Zero, a novel reinforcement learning (RL) framework enabling LLMs to self-correct through autonomous error strategy learning without external supervision. By integrating RL with LLMs' generative power, the method eliminates dependency on annotated data or auxiliary models. Experiments reveal RL-enhanced LLMs achieve industry-viable accuracy and superior cross-domain generalization, offering a scalable solution for reliability optimization in Chinese NLP applications. This breakthrough facilitates LLM deployment in practical Chinese text correction scenarios while establishing a new paradigm for self-improving language models.

[Arxiv](https://arxiv.org/abs/2505.09082)