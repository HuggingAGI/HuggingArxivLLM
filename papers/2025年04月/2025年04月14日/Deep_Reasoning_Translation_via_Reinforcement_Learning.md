# 基于强化学习的深度推理翻译

发布时间：2025年04月14日

`LLM应用`

> Deep Reasoning Translation via Reinforcement Learning

# 摘要

> 深度推理大语言模型（如 OpenAI o1/o3 和 DeepSeek-R1）在复杂任务中表现优异。自由翻译作为多语言世界中的重要任务，要求突破逐字翻译的局限，兼顾文化差异。然而，这一领域在深度推理模型中尚未充分探索。本文介绍的 DeepTrans 是一种基于强化学习的深度推理翻译模型，旨在实现自由翻译。我们构建了一个奖励模型，依据预设标准评估翻译结果与思维过程。在强化学习过程中，奖励模型指导翻译模型如何思考并完成自由翻译，无需依赖人工标注数据，节省了资源与时间。实验结果表明，基于 Qwen2.5-7B 的 DeepTrans 在文学翻译中提升了 16.3% 的性能，超越了深度推理基线与合成数据微调的模型。此外，我们总结了强化学习探索中的失败案例与有趣发现，希望为自由翻译领域的研究提供启发。

> Recently, deep reasoning LLMs (e.g., OpenAI o1/o3 and DeepSeek-R1) have shown promising performance in various complex tasks. Free translation is an important and interesting task in the multilingual world, which requires going beyond word-for-word translation and taking cultural differences into account. This task is still under-explored in deep reasoning LLMs. In this paper, we introduce DeepTrans, a deep reasoning translation model that learns free translation via reinforcement learning. Specifically, we carefully build a reward model with pre-defined scoring criteria on both the translation results and the thought process. Given the source sentences, the reward model teaches the deep translation model how to think and free-translate them during reinforcement learning. In this way, training DeepTrans does not need any labeled translations, avoiding the human-intensive annotation or resource-intensive data synthesis. Experimental results show the effectiveness of DeepTrans. Using Qwen2.5-7B as the backbone, DeepTrans improves performance by 16.3% in literature translation, and outperforms strong deep reasoning baselines as well as baselines that are fine-tuned with synthesized data. Moreover, we summarize the failures and interesting findings during our RL exploration. We hope this work could inspire other researchers in free translation.

[Arxiv](https://arxiv.org/abs/2504.10187)