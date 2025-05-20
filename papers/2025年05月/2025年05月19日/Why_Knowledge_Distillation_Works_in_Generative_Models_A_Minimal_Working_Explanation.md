# 知识蒸馏为何在生成模型中奏效：一个简单有效的解释

发布时间：2025年05月19日

`LLM理论` `生成建模`

> Why Knowledge Distillation Works in Generative Models: A Minimal Working Explanation

# 摘要

> 知识蒸馏（KD）是现代生成模型，尤其是大型语言模型（LLMs），训练和部署中的核心组件。尽管其实际优势已被充分证明——使较小的学生模型能够模仿远大于自己的教师模型的性能——但其如何提升生成质量的内在机制仍不清晰。本文为生成建模中的 KD 提供了一个简明的工作解释。通过使用高斯混合模型的受控模拟，我们展示了蒸馏在学生模型中引发了精确性和召回率之间的权衡。随着教师分布变得更加挑剔，学生模型将更多的概率质量集中在高可能性区域，但以覆盖范围为代价——这一行为由单一的熵控制参数调节。然后，我们使用 SmolLM2 模型家族在大规模语言建模环境中验证了这一效果。实证结果揭示了与模拟中相同的精确性-召回率动态，其中精确性对应样本质量，召回率对应分布覆盖范围。这种精确性-召回率的权衡在样本质量优先于多样性的场景中尤其有益，例如指令调优或下游生成。我们的分析为 KD 在生成建模中的有效性提供了一个简单且通用的解释。

> Knowledge distillation (KD) is a core component in the training and deployment of modern generative models, particularly large language models (LLMs). While its empirical benefits are well documented--enabling smaller student models to emulate the performance of much larger teachers--the underlying mechanisms by which KD improves generative quality remain poorly understood. In this work, we present a minimal working explanation of KD in generative modeling. Using a controlled simulation with mixtures of Gaussians, we demonstrate that distillation induces a trade-off between precision and recall in the student model. As the teacher distribution becomes more selective, the student concentrates more probability mass on high-likelihood regions at the expense of coverage--a behavior modulated by a single entropy-controlling parameter. We then validate this effect in a large-scale language modeling setup using the SmolLM2 family of models. Empirical results reveal the same precision-recall dynamics observed in simulation, where precision corresponds to sample quality and recall to distributional coverage. This precision-recall trade-off proves especially beneficial in scenarios where sample quality outweighs diversity, such as instruction tuning or downstream generation. Our analysis provides a simple and general explanation for the effectiveness of KD in generative modeling.

[Arxiv](https://arxiv.org/abs/2505.13111)