# ResoFilter：基于数据 - 参数共振分析为大型语言模型实现细粒度的合成数据过滤

发布时间：2024年12月19日

`LLM应用` `数据增强`

> ResoFilter: Rine-grained Synthetic Data Filtering for Large Language Models through Data-Parameter Resonance Analysis

# 摘要

> 大型语言模型（LLMs）在众多领域成效显著，利用 GPT 生成合成数据的数据增强方法颇为常见。但增强数据的质量和实用性存疑，当前方法也缺少评估数据特征的清晰指标。为应对这些挑战，我们提出了 ResoFilter 这一创新方法，它将模型、数据和任务相融合以优化数据集。ResoFilter 借助微调过程获取用于数据选择的数据 - 参数特征，通过模型权重来呈现数据特征，提高了可解释性。我们的实验表明，在数学任务中，ResoFilter 仅用一半的数据就能取得与全规模微调相当的结果，且在不同模型和领域中展现出强大的泛化能力。此方法为构建合成数据集和评估高质量数据提供了宝贵思路，为强化数据增强技术和提升 LLMs 训练数据集的质量带来了颇具前景的解决方案。为保证可重复性，我们会在论文被接收后公布代码和数据。

> Large language models (LLMs) have shown remarkable effectiveness across various domains, with data augmentation methods utilizing GPT for synthetic data generation becoming prevalent. However, the quality and utility of augmented data remain questionable, and current methods lack clear metrics for evaluating data characteristics. To address these challenges, we propose ResoFilter, a novel method that integrates models, data, and tasks to refine datasets. ResoFilter leverages the fine-tuning process to obtain Data-Parameter features for data selection, offering improved interpretability by representing data characteristics through model weights. Our experiments demonstrate that ResoFilter achieves comparable results to full-scale fine-tuning using only half the data in mathematical tasks and exhibits strong generalization across different models and domains. This method provides valuable insights for constructing synthetic datasets and evaluating high-quality data, offering a promising solution for enhancing data augmentation techniques and improving training dataset quality for LLMs. For reproducibility, we will release our code and data upon acceptance.

[Arxiv](https://arxiv.org/abs/2412.14809)