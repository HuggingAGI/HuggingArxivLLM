# # 标题
SpectR：通过频谱路由动态组合语言模型专家，一种创新的方法。

发布时间：2025年04月04日

`LLM理论` `模型优化` `模型组合`

> SpectR: Dynamically Composing LM Experts with Spectral Routing

# 摘要

> 训练大型通用语言模型面临重大挑战。随着针对特定任务或领域微调的专家模型越来越多，这为解决问题提供了有前景的替代方案。在实际应用中，有效利用这些现有专家模型的潜力，需要能够选择或合并最适合特定任务的模型的方法。本文介绍的SPECTR方法，能够在推理过程中动态组合专家模型。值得注意的是，我们的方法无需额外训练，支持灵活地按token和层进行模型组合。实验结果表明，SPECTR在提高路由准确性方面优于其他无训练方法，能够显著提升跨专家领域任务的性能表现。

> Training large, general-purpose language models poses significant challenges. The growing availability of specialized expert models, fine-tuned from pretrained models for specific tasks or domains, offers a promising alternative. Leveraging the potential of these existing expert models in real-world applications requires effective methods to select or merge the models best suited for a given task. This paper introduces SPECTR, an approach for dynamically composing expert models at each time step during inference. Notably, our method requires no additional training and enables flexible, token- and layer-wise model combinations. Our experimental results demonstrate that SPECTR improves routing accuracy over alternative training-free methods, increasing task performance across expert domains.

[Arxiv](https://arxiv.org/abs/2504.03454)