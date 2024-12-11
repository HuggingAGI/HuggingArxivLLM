# 自然语言生成中基于标签置信度的不确定性估计

发布时间：2024年12月10日

`LLM理论` `人工智能`

> Label-Confidence-Aware Uncertainty Estimation in Natural Language Generation

# 摘要

> 大型语言模型（LLMs）在生成任务方面能力出众，不过因其易产生幻觉性回应，也潜藏着风险。不确定性量化（UQ），也就是对模型输出可靠性的评估，对保障人工智能系统的安全和稳健极为关键。近期研究通过剖析不同采样条件下的输出熵与对应标签的关系，聚焦于模型的不确定性。然而，这些方法主要是精准测量模型熵以捕捉响应特点，常常忽视了与贪婪解码结果（即模型标签的来源）相关的不确定性，这可能致使分类结果出现偏差。在本文中，我们探究了贪婪解码带来的偏差，并基于样本和标签源之间的 Kullback-Leibler（KL）散度，提出了一种标签置信度感知（LCA）的不确定性估计方法，进而增强了不确定性评估的可靠性和稳定性。我们在一系列热门的 LLMs 和 NLP 数据集上开展的实证评估显示，不同的标签源确实会影响分类，而且我们的方法能够有效捕捉采样结果和标签源的差异，展现出更出色的不确定性估计效果。

> Large Language Models (LLMs) display formidable capabilities in generative tasks but also pose potential risks due to their tendency to generate hallucinatory responses. Uncertainty Quantification (UQ), the evaluation of model output reliability, is crucial for ensuring the safety and robustness of AI systems. Recent studies have concentrated on model uncertainty by analyzing the relationship between output entropy under various sampling conditions and the corresponding labels. However, these methods primarily focus on measuring model entropy with precision to capture response characteristics, often neglecting the uncertainties associated with greedy decoding results-the sources of model labels, which can lead to biased classification outcomes. In this paper, we explore the biases introduced by greedy decoding and propose a label-confidence-aware (LCA) uncertainty estimation based on Kullback-Leibler (KL) divergence bridging between samples and label source, thus enhancing the reliability and stability of uncertainty assessments. Our empirical evaluations across a range of popular LLMs and NLP datasets reveal that different label sources can indeed affect classification, and that our approach can effectively capture differences in sampling results and label sources, demonstrating more effective uncertainty estimation.

[Arxiv](https://arxiv.org/abs/2412.07255)