# CONGRAD：多语言偏好对齐中的冲突梯度筛选

发布时间：2025年03月31日

`LLM应用` `多语言模型` `机器学习`

> CONGRAD:Conflicting Gradient Filtering for Multilingual Preference Alignment

# 摘要

> 简单的联合训练大型语言模型 (LLMs) 进行多语言偏好对齐可能遭受负面干扰。这是多语言训练中一个已知问题，即相互冲突的目标会损害整体性能。然而，这一现象在多语言偏好对齐背景下的影响仍然研究不足。为了解决这一问题，我们提出了CONGRAD，这是一种可扩展且有效的筛选方法，用于选择跨语言梯度冲突最小的高质量偏好样本。我们的方法利用梯度手术来保留与聚合多语言更新方向一致的样本。此外，我们还引入了一种次线性梯度压缩策略，以减少梯度累积过程中的内存开销。我们将CONGRAD集成到自我奖励框架中，并在LLaMA3-8B和Gemma2-2B模型上进行了跨10种语言的评估。实验结果显示，CONGRAD在已见和未见语言上均显著优于强基线模型，且对齐代价极低。

> Naive joint training of large language models (LLMs) for multilingual preference alignment can suffer from negative interference. This is a known issue in multilingual training, where conflicting objectives degrade overall performance. However, the impact of this phenomenon in the context of multilingual preference alignment remains largely underexplored. To address this issue, we propose CONGRAD, a scalable and effective filtering method that selects high-quality preference samples with minimal gradient conflicts across languages. Our method leverages gradient surgery to retain samples aligned with an aggregated multilingual update direction. Additionally, we incorporate a sublinear gradient compression strategy that reduces memory overhead during gradient accumulation. We integrate CONGRAD into self-rewarding framework and evaluate on LLaMA3-8B and Gemma2-2B across 10 languages. Results show that CONGRAD consistently outperforms strong baselines in both seen and unseen languages, with minimal alignment tax.

[Arxiv](https://arxiv.org/abs/2503.23777)