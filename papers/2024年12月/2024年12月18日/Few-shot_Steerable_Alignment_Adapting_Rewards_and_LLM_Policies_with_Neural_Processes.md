# Few-shot Steerable Alignment：借助神经过程调适奖励与大型语言模型策略

发布时间：2024年12月18日

`LLM应用` `语言模型` `用户偏好`

> Few-shot Steerable Alignment: Adapting Rewards and LLM Policies with Neural Processes

# 摘要

> 随着大型语言模型（LLMs）在日常应用中不断深入，确保其与个体用户的多元偏好相契合已成为关键难题。当下所采用的方法往往假定用户目标一致，依赖于单目标微调。然而，人类偏好实则各异，受诸多不可观测因素影响，致使偏好数据存在冲突信号。现有的应对此类多样性的解决方案，通常需要针对特定目标标注的昂贵数据集，还涉及训练多个奖励模型或LLM策略，这在计算上既昂贵又不实用。在本研究中，我们提出了一个用于少样本可引导对齐的全新框架，能从用户的少量选择样本中推断出其潜在偏好。为此，我们拓展了Bradley-Terry-Luce模型来处理存在未观测变异因素的异质偏好，并给出其在奖励建模和LLM微调中的实际应用。得益于我们提出的功能参数空间调节方法，用我们框架训练的LLM在推理时能够适应个体偏好，生成一系列行为模式的输出。我们通过实验验证了这些方法的有效性，表明它们能够以高效的数据利用方式捕捉并契合不同的人类偏好。我们的代码可在以下网址获取：https://github.com/kasia-kobalczyk/few-shot-steerable-alignment。

> As large language models (LLMs) become increasingly embedded in everyday applications, ensuring their alignment with the diverse preferences of individual users has become a critical challenge. Currently deployed approaches typically assume homogeneous user objectives and rely on single-objective fine-tuning. However, human preferences are inherently heterogeneous, influenced by various unobservable factors, leading to conflicting signals in preference data. Existing solutions addressing this diversity often require costly datasets labelled for specific objectives and involve training multiple reward models or LLM policies, which is computationally expensive and impractical. In this work, we present a novel framework for few-shot steerable alignment, where users' underlying preferences are inferred from a small sample of their choices. To achieve this, we extend the Bradley-Terry-Luce model to handle heterogeneous preferences with unobserved variability factors and propose its practical implementation for reward modelling and LLM fine-tuning. Thanks to our proposed approach of functional parameter-space conditioning, LLMs trained with our framework can be adapted to individual preferences at inference time, generating outputs over a continuum of behavioural modes. We empirically validate the effectiveness of methods, demonstrating their ability to capture and align with diverse human preferences in a data-efficient manner. Our code is made available at: https://github.com/kasia-kobalczyk/few-shot-steerable-alignment.

[Arxiv](https://arxiv.org/abs/2412.13998)