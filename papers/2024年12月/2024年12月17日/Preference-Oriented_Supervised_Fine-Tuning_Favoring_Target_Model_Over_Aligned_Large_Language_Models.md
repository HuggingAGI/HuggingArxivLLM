# 偏好导向的有监督微调：更倾向于目标模型，而非对齐的大型语言模型

发布时间：2024年12月17日

`LLM应用` `人工智能`

> Preference-Oriented Supervised Fine-Tuning: Favoring Target Model Over Aligned Large Language Models

# 摘要

> 对齐，即赋予预训练的大型语言模型（LLM）遵循指令的能力，这对其在现实中的应用极为关键。传统的有监督微调（SFT）方法通常把它形式化为具有交叉熵目标的因果语言建模，这需要大量高质量的指令 - 响应对。但由于在实际创建和维护中成本高、劳动密集，广泛使用的 SFT 数据集质量难以保证。为突破 SFT 数据集质量的限制，我们引入了一种新颖的面向偏好的监督微调方法，即 PoFT。其理念是通过施加特定偏好来强化 SFT：即在相同的 SFT 数据上，更倾向于目标模型而非已对齐的 LLM。这种偏好促使目标模型预测出比已对齐的 LLM 更高的可能性，将数据质量的评估信息（即已对齐的 LLM 预测的可能性）融入训练过程。开展了大量实验，结果证实了该方法的有效性。PoFT 在不同的训练数据集和基础模型上，相比 SFT 基线实现了稳定且一致的提升。此外，我们证明 PoFT 能与现有的 SFT 数据过滤方法相结合以获得更优性能，并通过遵循偏好优化程序（如 DPO）进一步改进。

> Alignment, endowing a pre-trained Large language model (LLM) with the ability to follow instructions, is crucial for its real-world applications. Conventional supervised fine-tuning (SFT) methods formalize it as causal language modeling typically with a cross-entropy objective, requiring a large amount of high-quality instruction-response pairs. However, the quality of widely used SFT datasets can not be guaranteed due to the high cost and intensive labor for the creation and maintenance in practice. To overcome the limitations associated with the quality of SFT datasets, we introduce a novel \textbf{p}reference-\textbf{o}riented supervised \textbf{f}ine-\textbf{t}uning approach, namely PoFT. The intuition is to boost SFT by imposing a particular preference: \textit{favoring the target model over aligned LLMs on the same SFT data.} This preference encourages the target model to predict a higher likelihood than that predicted by the aligned LLMs, incorporating assessment information on data quality (i.e., predicted likelihood by the aligned LLMs) into the training process. Extensive experiments are conducted, and the results validate the effectiveness of the proposed method. PoFT achieves stable and consistent improvements over the SFT baselines across different training datasets and base models. Moreover, we prove that PoFT can be integrated with existing SFT data filtering methods to achieve better performance, and further improved by following preference optimization procedures, such as DPO.

[Arxiv](https://arxiv.org/abs/2412.12865)