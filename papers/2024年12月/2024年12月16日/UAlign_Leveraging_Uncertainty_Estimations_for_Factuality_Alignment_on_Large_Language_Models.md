# UAlign：借助不确定性估计在大型语言模型上达成真实性对齐

发布时间：2024年12月16日

`LLM应用` `语言模型` `知识问答`

> UAlign: Leveraging Uncertainty Estimations for Factuality Alignment on Large Language Models

# 摘要

> 尽管大型语言模型（LLMs）展现出了令人瞩目的能力，但在准确表达所拥有的事实知识方面仍常常面临困境，尤其是在其知识边界模糊不清时。为提升 LLMs 的事实表达能力，我们提出了 UAlign 框架，该框架借助不确定性估计来表征知识边界，然后将这些表征明确作为输入特征融入提示中，促使 LLMs 与事实知识对齐。首先，我们通过计算包括置信度得分和语义熵在内的两种不确定性估计，为知识问答（QA）样本准备数据集，以此来表征 LLMs 的知识边界。接着，利用准备好的数据集，我们训练了一个融合不确定性估计的奖励模型，随后运用近端策略优化（PPO）算法对 LLMs 进行事实对齐。实验结果显示，通过在 LLM 对齐中整合不确定性表征，所提出的 UAlign 能够显著增强 LLMs 在域内和域外任务中自信回答已知问题和拒绝未知问题的能力，展现出可靠性的提升以及相较于各类基于提示和训练的基线的良好泛化能力。

> Despite demonstrating impressive capabilities, Large Language Models (LLMs) still often struggle to accurately express the factual knowledge they possess, especially in cases where the LLMs' knowledge boundaries are ambiguous. To improve LLMs' factual expressions, we propose the UAlign framework, which leverages Uncertainty estimations to represent knowledge boundaries, and then explicitly incorporates these representations as input features into prompts for LLMs to Align with factual knowledge. First, we prepare the dataset on knowledge question-answering (QA) samples by calculating two uncertainty estimations, including confidence score and semantic entropy, to represent the knowledge boundaries for LLMs. Subsequently, using the prepared dataset, we train a reward model that incorporates uncertainty estimations and then employ the Proximal Policy Optimization (PPO) algorithm for factuality alignment on LLMs. Experimental results indicate that, by integrating uncertainty representations in LLM alignment, the proposed UAlign can significantly enhance the LLMs' capacities to confidently answer known questions and refuse unknown questions on both in-domain and out-of-domain tasks, showing reliability improvements and good generalizability over various prompt- and training-based baselines.

[Arxiv](https://arxiv.org/abs/2412.11803)