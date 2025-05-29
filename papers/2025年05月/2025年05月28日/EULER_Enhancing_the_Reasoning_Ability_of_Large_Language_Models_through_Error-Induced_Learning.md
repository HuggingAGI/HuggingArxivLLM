# # EULER：借助错误诱导学习提升大型语言模型的推理能力
EULER: 基于错误诱导学习提升大型语言模型的推理能力

发布时间：2025年05月28日

`LLM理论`

> EULER: Enhancing the Reasoning Ability of Large Language Models through Error-Induced Learning

# 摘要

> 大型语言模型（LLMs）在数学推理方面表现出色，尤其在解决数学问题任务中取得了显著成果。通过学习错误，我们可以进一步提升LLMs在监督微调（SFT）过程中的表现。然而，合成解决方案中的错误通常来自采样轨迹，这为每个数学问题生成解决方案错误带来了挑战。本文提出了一种名为错误诱导学习（EULER）的模型，旨在开发一个能够生成高质量解决方案错误的错误暴露模型，从而增强LLMs的数学推理能力。具体而言，EULER通过优化错误暴露模型来增加自动生成解决方案错误的概率，同时利用更优LLMs生成的解决方案来规范生成质量。我们在多个数学问题数据集上的实验结果表明，EULER模型相较于所有基线模型，性能提升了4%以上。进一步分析显示，EULER能够生成更具挑战性和教育意义的解决方案错误，这些错误不仅有助于LLMs的训练，也对推理过程大有裨益。所有相关代码均可在https://github.com/NEUIR/EULER上获取。

> Large Language Models (LLMs) have demonstrated strong reasoning capabilities and achieved promising results in mathematical problem-solving tasks. Learning from errors offers the potential to further enhance the performance of LLMs during Supervised Fine-Tuning (SFT). However, the errors in synthesized solutions are typically gathered from sampling trails, making it challenging to generate solution errors for each mathematical problem. This paper introduces the Error-IndUced LEaRning (EULER) model, which aims to develop an error exposure model that generates high-quality solution errors to enhance the mathematical reasoning capabilities of LLMs. Specifically, EULER optimizes the error exposure model to increase the generation probability of self-made solution errors while utilizing solutions produced by a superior LLM to regularize the generation quality. Our experiments across various mathematical problem datasets demonstrate the effectiveness of the EULER model, achieving an improvement of over 4% compared to all baseline models. Further analysis reveals that EULER is capable of synthesizing more challenging and educational solution errors, which facilitate both the training and inference processes of LLMs. All codes are available at https://github.com/NEUIR/EULER.

[Arxiv](https://arxiv.org/abs/2505.22131)