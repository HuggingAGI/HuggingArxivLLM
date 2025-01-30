# 探索LLM世界模型：利用群体智慧解码提升猜测精度

发布时间：2025年01月28日

`LLM应用

**理由**：这篇论文主要探讨了大型语言模型（LLMs）和视觉语言模型（VLMs）在近似数量估计（guesstimation）任务中的应用。论文提出了一个新的数据集MARBLES，并引入了一种新的解码策略“WOC解码”来提升模型在guesstimation任务中的表现。这些内容主要涉及LLM在实际任务中的应用和性能提升，因此归类为LLM应用。` `社会科学` `人工智能`

> Probing LLM World Models: Enhancing Guesstimation with Wisdom of Crowds Decoding

# 摘要

> Guesstimation，即近似数量估计，是现实世界中的常见挑战，但在大型语言模型（LLMs）和视觉语言模型（VLMs）的研究中却鲜有涉及。我们推出了一个全新的guesstimation数据集——MARBLES，要求用户估计物品（如弹珠）能放入容器（如一量杯）的数量，无论是否有图像辅助。受社会科学中“群体智慧”（WOC）概念的启发——即从群体估计中取中位数，这在guesstimation中已被证明有效，我们提出了“WOC解码”策略用于LLM的guesstimation。实验表明，LLMs/VLMs在guesstimation任务上表现出色，暗示它们具备一定程度的“世界模型”，这是guesstimation所必需的。此外，WOC解码方法显著提升了LLM/VLM的估计准确性，类似于人类的表现。同时，多模态条件下的图像引入进一步增强了模型性能。这些发现不仅凸显了WOC解码策略对LLMs/VLMs的重要性，还将guesstimation定位为评估LLMs/VLMs世界模型的有效工具。

> Guesstimation, the task of making approximate quantity estimates, is a common real-world challenge. However, it has been largely overlooked in large language models (LLMs) and vision language models (VLMs) research. We introduce a novel guesstimation dataset, MARBLES. This dataset requires one to estimate how many items (e.g., marbles) can fit into containers (e.g., a one-cup measuring cup), both with and without accompanying images. Inspired by the social science concept of the ``{Wisdom of Crowds'' (WOC) - taking the median from estimates from a crowd), which has proven effective in guesstimation, we propose ``WOC decoding'' strategy for LLM guesstimation. We show that LLMs/VLMs perform well on guesstimation, suggesting that they possess some level of a "world model" necessary for guesstimation. Moreover, similar to human performance, the WOC decoding method improves LLM/VLM guesstimation accuracy. Furthermore, the inclusion of images in the multimodal condition enhances model performance. These results highlight the value of WOC decoding strategy for LLMs/VLMs and position guesstimation as a probe for evaluating LLMs/VLMs' world model.

[Arxiv](https://arxiv.org/abs/2501.17310)