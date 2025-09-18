# Omni-CLST：面向音频问答的错误感知课程学习与引导式选择性思维链

发布时间：2025年09月16日

`LLM应用` `媒体与娱乐`

> Omni-CLST: Error-aware Curriculum Learning with guided Selective chain-of-Thought for audio question answering

# 摘要

> 随着大型音频语言模型（LALMs）的飞速发展，音频问答（AQA）已成为一项极具挑战性的任务，它既要求细粒度的音频理解，又需要复杂的推理能力。尽管目前的方法主要通过生成字幕或推理轨迹来构建新数据集，但现有的高质量AQA数据却远未得到充分利用。为此，我们提出了Omni-CLST——一种具备引导性选择性思维链的错误感知课程学习框架。该框架通过两大核心策略高效利用现有的高质量数据集：一是按难度梯度组织样本的错误感知课程，二是将推理聚焦于疑难案例的引导性思维丢弃机制。实验结果显示，Omni-CLST在MMAU-mini数据集上达到73.80%的准确率，在MMAR数据集上则刷新了64.30%的最新纪录，充分彰显了其在多模态音频语言理解任务中的强大泛化性能。

> With the rapid progress of large audio-language models (LALMs), audio question answering (AQA) has emerged as a challenging task requiring both fine-grained audio understanding and complex reasoning. While current methods mainly rely on constructing new datasets via captioning or reasoning traces, existing high-quality AQA data remains underutilized. To address this, we propose Omni-CLST, an error-aware Curriculum Learning framework with guided Selective Chain-of-Thought. The framework efficiently leverages existing high-quality dataset through two key strategies: an error-aware curriculum that organizes samples by difficulty, and a guided thought dropout mechanism that focuses reasoning on challenging cases. Experiments show that Omni-CLST achieves 73.80% on MMAU-mini and a new state of the art of 64.30% on MMAR, demonstrating robust generalization in multimodal audio-language understanding.

[Arxiv](https://arxiv.org/abs/2509.12275)