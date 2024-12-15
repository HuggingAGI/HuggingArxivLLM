# 欧几里得：以合成的高保真视觉描述为多模态大型语言模型增添强大动力

发布时间：2024年12月11日

`LLM应用` `机器人` `医学图像分析`

> Euclid: Supercharging Multimodal LLMs with Synthetic High-Fidelity Visual Descriptions

# 摘要

> 多模态大型语言模型（MLLMs）近些年来发展迅猛，然而在低级视觉感知（LLVP）方面仍面临挑战，尤其是准确描述图像几何细节的能力。这一能力在机器人、医学图像分析和制造业等领域的应用中至关重要。本文中，我们首先引入了 Geoperception 这一基准，用于评估 MLLM 从图像中准确转录 2D 几何信息的能力。借助该基准，我们揭示了领先的 MLLM 的局限性，接着开展了全面的实证研究，探索提升其在几何任务上表现的策略。我们的发现凸显了某些模型架构、训练技术和数据策略的优势，比如使用高保真合成数据以及采用数据课程的多阶段训练。特别值得一提的是，我们发现数据课程能让模型学会那些无法从零开始学习的具有挑战性的几何理解任务。基于这些见解，我们开发了 Euclid 系列模型，专门针对强大的低级几何感知进行了优化。尽管只是在合成多模态数据上训练，Euclid 对新的几何形状展现出了强大的泛化能力。例如，在某些 Geoperception 基准任务中，Euclid 比最佳闭源模型 Gemini-1.5-Pro 高出多达 58.56%，在所有任务上平均高出 10.65%。

> Multimodal large language models (MLLMs) have made rapid progress in recent years, yet continue to struggle with low-level visual perception (LLVP) -- particularly the ability to accurately describe the geometric details of an image. This capability is crucial for applications in areas such as robotics, medical image analysis, and manufacturing. In this paper, we first introduce Geoperception, a benchmark designed to evaluate an MLLM's ability to accurately transcribe 2D geometric information from an image. Using this benchmark, we demonstrate the limitations of leading MLLMs, and then conduct a comprehensive empirical study to explore strategies for improving their performance on geometric tasks. Our findings highlight the benefits of certain model architectures, training techniques, and data strategies, including the use of high-fidelity synthetic data and multi-stage training with a data curriculum. Notably, we find that a data curriculum enables models to learn challenging geometry understanding tasks which they fail to learn from scratch. Leveraging these insights, we develop Euclid, a family of models specifically optimized for strong low-level geometric perception. Although purely trained on synthetic multimodal data, Euclid shows strong generalization ability to novel geometry shapes. For instance, Euclid outperforms the best closed-source model, Gemini-1.5-Pro, by up to 58.56% on certain Geoperception benchmark tasks and 10.65% on average across all tasks.

[Arxiv](https://arxiv.org/abs/2412.08737)