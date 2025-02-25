# 感知模态的神经元剪枝方法，用于多模态大型语言模型的遗忘机制研究

发布时间：2025年02月21日

`LLM理论` `人工智能`

> Modality-Aware Neuron Pruning for Unlearning in Multimodal Large Language Models

# 摘要

> 生成模型，例如大型语言模型（LLMs）和多模态大型语言模型（MLLMs），在大规模数据集上的训练可能导致它们记忆并无意中泄露敏感信息，引发伦理和隐私方面的担忧。尽管此前已有研究在LLMs背景下探讨过这一问题，但MLLMs由于跨模态知识的纠缠特性，给全面的知识遗忘带来了独特挑战。为应对这一挑战，我们提出了模态感知神经元遗忘框架（MANU），一种专为MLLMs设计的新型遗忘框架，旨在根据不同模态的重要性，选择性地剪裁与目标遗忘数据相关的神经元。具体而言，MANU包含两个阶段：重要神经元选择和选择性剪枝。第一阶段识别并收集与目标遗忘知识在各模态中最相关的神经元，第二阶段则专注于剪枝这些选定的神经元。MANU能够有效隔离并移除各模态中对遗忘数据贡献最大的神经元，同时保留其余知识的完整性。我们对多种MLLM架构的实验表明，MANU能够在不显著影响整体模型效用的前提下，实现各模态中更加均衡和全面的知识遗忘。

> Generative models such as Large Language Models (LLMs) and Multimodal Large Language Models (MLLMs) trained on massive datasets can lead them to memorize and inadvertently reveal sensitive information, raising ethical and privacy concerns. While some prior works have explored this issue in the context of LLMs, it presents a unique challenge for MLLMs due to the entangled nature of knowledge across modalities, making comprehensive unlearning more difficult. To address this challenge, we propose Modality Aware Neuron Unlearning (MANU), a novel unlearning framework for MLLMs designed to selectively clip neurons based on their relative importance to the targeted forget data, curated for different modalities. Specifically, MANU consists of two stages: important neuron selection and selective pruning. The first stage identifies and collects the most influential neurons across modalities relative to the targeted forget knowledge, while the second stage is dedicated to pruning those selected neurons. MANU effectively isolates and removes the neurons that contribute most to the forget data within each modality, while preserving the integrity of retained knowledge. Our experiments conducted across various MLLM architectures illustrate that MANU can achieve a more balanced and comprehensive unlearning in each modality without largely affecting the overall model utility.

[Arxiv](https://arxiv.org/abs/2502.15910)