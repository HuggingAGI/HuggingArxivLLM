# # 多模态语言模型在评估文本到图像模型中的应用

发布时间：2025年05月01日

`LLM应用` `生成式AI` `计算机视觉`

> Multi-Modal Language Models as Text-to-Image Model Evaluators

# 摘要

> 文本到图像（T2I）生成模型的持续改进使得依赖静态数据集的自动评估基准逐渐被淘汰，这促使研究人员寻求新的方法来评估T2I技术的进步。本文中，我们探索了多模态大型语言模型（MLLMs）作为评估代理的潜力，这些模型能够与T2I模型互动，从而评估提示生成的一致性和图像美学。我们提出了多模态文本到图像评估框架MT2IE，该框架通过迭代生成评估提示、对生成图像进行评分，并在使用现有静态基准一小部分提示的情况下，实现与现有基准相当的T2I评估效果。此外，我们发现MT2IE的提示生成一致性评分与人类判断的相关性显著高于文献中先前提出的评分方法。MT2IE生成的提示不仅高效，能够有效探测T2I模型的性能，而且仅使用现有基准1/80的提示数量即可生成与现有基准一致的T2I模型排名。

> The steady improvements of text-to-image (T2I) generative models lead to slow deprecation of automatic evaluation benchmarks that rely on static datasets, motivating researchers to seek alternative ways to evaluate the T2I progress. In this paper, we explore the potential of multi-modal large language models (MLLMs) as evaluator agents that interact with a T2I model, with the objective of assessing prompt-generation consistency and image aesthetics. We present Multimodal Text-to-Image Eval (MT2IE), an evaluation framework that iteratively generates prompts for evaluation, scores generated images and matches T2I evaluation of existing benchmarks with a fraction of the prompts used in existing static benchmarks. Moreover, we show that MT2IE's prompt-generation consistency scores have higher correlation with human judgment than scores previously introduced in the literature. MT2IE generates prompts that are efficient at probing T2I model performance, producing the same relative T2I model rankings as existing benchmarks while using only 1/80th the number of prompts for evaluation.

[Arxiv](https://arxiv.org/abs/2505.00759)