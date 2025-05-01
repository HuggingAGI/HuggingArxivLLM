# 参数Δ用于直接权重混合：零成本的训练后大型语言模型

发布时间：2025年04月22日

`LLM理论` `人工智能`

> Param$Δ$ for Direct Weight Mixing: Post-Train Large Language Model at Zero Cost

# 摘要

> 大型语言模型的后训练阶段对于提升遵循指令、推理以及与人类偏好对齐等能力至关重要。然而，这一阶段需要大量高质量的数据，同时面临过拟合等风险，并且由于每次基础模型更新后都需要重复进行后训练和评估，导致计算成本高昂。本文介绍了一种名为 $ParamΔ$ 的新方法，通过将现有后训练模型的知识迁移至新更新的基础模型，实现了无需额外训练的后训练流程简化。

通过计算后训练模型权重 ($Θ_	ext{post}$) 与基础模型权重 ($Θ_	ext{base}$) 之间的差异，并将其添加到更新后的基础模型 ($Θ'_	ext{base}$) 中，我们定义 $ParamΔ$ 模型为：$Θ_{	ext{Param}Δ} = Θ_	ext{post} - Θ_	ext{base} + Θ'_	ext{base}$。这一方法令人惊讶地使新基础模型具备了后训练能力，其性能可与直接后训练相媲美。

我们在 LLama3、Llama3.1、Qwen 以及 DeepSeek-distilled 模型上进行了分析。结果表明，$ParamΔ$ 模型能够有效复现传统的后训练效果。例如，基于 70B Llama3-inst、Llama3-base 以及 Llama3.1-base 模型获得的 $ParamΔ$ 模型，在平均性能上达到了 Llama3.1-inst 模型性能的约 95%。$ParamΔ$ 为充分利用开放权重社区中的模型提供了一个全新的视角，其中基础模型和指令模型的检查点随时可用且频繁更新，通过提供一个零成本框架加速模型开发的迭代周期。


> The post-training phase of large language models is essential for enhancing capabilities such as instruction-following, reasoning, and alignment with human preferences. However, it demands extensive high-quality data and poses risks like overfitting, alongside significant computational costs due to repeated post-training and evaluation after each base model update. This paper introduces $ParamΔ$, a novel method that streamlines post-training by transferring knowledge from an existing post-trained model to a newly updated base model with ZERO additional training. By computing the difference between post-trained model weights ($Θ_\text{post}$) and base model weights ($Θ_\text{base}$), and adding this to the updated base model ($Θ'_\text{base}$), we define $ParamΔ$ Model as: $Θ_{\text{Param}Δ} = Θ_\text{post} - Θ_\text{base} + Θ'_\text{base}$. This approach surprisingly equips the new base model with post-trained capabilities, achieving performance comparable to direct post-training. We did analysis on LLama3, Llama3.1, Qwen, and DeepSeek-distilled models. Results indicate $ParamΔ$ Model effectively replicates traditional post-training. For example, the $ParamΔ$ Model obtained from 70B Llama3-inst, Llama3-base, Llama3.1-base models attains approximately 95\% of Llama3.1-inst model's performance on average. $ParamΔ$ brings a new perspective on how to fully leverage models in the open-weight community, where checkpoints for base and instruct models are readily available and frequently updated, by providing a cost-free framework to accelerate the iterative cycle of model development.

[Arxiv](https://arxiv.org/abs/2504.21023)