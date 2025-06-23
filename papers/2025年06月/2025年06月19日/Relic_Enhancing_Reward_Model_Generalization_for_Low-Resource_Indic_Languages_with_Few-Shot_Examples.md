# Relic：通过少量示例增强奖励模型在低资源印度语言中的泛化能力

发布时间：2025年06月19日

`LLM应用` `NLP` `跨语言处理`

> Relic: Enhancing Reward Model Generalization for Low-Resource Indic Languages with Few-Shot Examples

# 摘要

> 奖励模型是将大型语言模型 (LLMs) 与人类偏好对齐的关键。然而，现有的开源多语言奖励模型大多依赖于高资源语言的偏好数据集进行训练，导致在处理低资源印地语时，奖励信号的可靠性大打折扣。由于收集这些语言的大规模高质量偏好数据成本高昂，基于偏好的训练方法难以实施。为解决这一难题，我们提出了 RELIC——一种专为低资源印地语设计的 in-context 学习框架。RELIC 通过成对排名目标训练检索器，从辅助高资源语言中挑选出最能凸显优选与非优选响应差异的 in-context 示例。在 PKU-SafeRLHF、WebGPT 和 HH-RLHF 三个偏好数据集上，使用最先进的开源奖励模型进行的大量实验表明，RELIC 显著提升了低资源印地语奖励模型的准确性，超越了现有的所有示例选择方法。以低资源印地语 Bodo 为例，使用 LLaMA-3.2-3B 奖励模型，RELIC 的准确性较零-shot 提示和最先进示例选择方法分别提升了 12.81% 和 10.13%。

> Reward models are essential for aligning large language models (LLMs) with human preferences. However, most open-source multilingual reward models are primarily trained on preference datasets in high-resource languages, resulting in unreliable reward signals for low-resource Indic languages. Collecting large-scale, high-quality preference data for these languages is prohibitively expensive, making preference-based training approaches impractical. To address this challenge, we propose RELIC, a novel in-context learning framework for reward modeling in low-resource Indic languages. RELIC trains a retriever with a pairwise ranking objective to select in-context examples from auxiliary high-resource languages that most effectively highlight the distinction between preferred and less-preferred responses. Extensive experiments on three preference datasets- PKU-SafeRLHF, WebGPT, and HH-RLHF-using state-of-the-art open-source reward models demonstrate that RELIC significantly improves reward model accuracy for low-resource Indic languages, consistently outperforming existing example selection methods. For example, on Bodo-a low-resource Indic language-using a LLaMA-3.2-3B reward model, RELIC achieves a 12.81% and 10.13% improvement in accuracy over zero-shot prompting and state-of-the-art example selection method, respectively.

[Arxiv](https://arxiv.org/abs/2506.16502)