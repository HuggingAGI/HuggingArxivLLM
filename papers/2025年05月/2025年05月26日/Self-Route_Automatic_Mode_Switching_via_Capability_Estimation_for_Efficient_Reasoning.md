# 自适应路由：通过能力评估实现自动模式切换以提升推理效率

发布时间：2025年05月26日

`LLM应用

这篇论文探讨了大型语言模型在推理过程中的优化，提出了一种动态推理框架Self-Route，旨在提高模型处理任务的效率。该研究属于模型应用层面的改进，因此归类为LLM应用。` `人工智能`

> Self-Route: Automatic Mode Switching via Capability Estimation for Efficient Reasoning

# 摘要

> 增强推理的大型语言模型（RLLMs）虽然通过延长推理链显著提升了复杂任务的处理性能，但它们在处理简单问题时却常常过度思考，导致大量不必要的token消耗。为解决这一问题，我们提出了Self-Route，一个动态推理框架，能够根据模型能力评估自动在通用模式和推理模式之间进行选择。我们的方法引入了一个轻量级的预推理阶段，从隐藏层表示中提取具备能力感知的嵌入，从而实现对模型解决问题能力的实时评估。我们进一步构建了Gradient-10K，这是一个基于模型难度估计的数据集，具有密集的复杂度采样，用于训练路由器以实现精准的能力边界检测。实验结果表明，Self-Route在保持与推理模型相当的准确率的同时，将token消耗减少了30-55%（具体数值为30-55\%），这一效果在各类基准测试中均得到了验证。该框架在不同参数规模和推理范式的模型上均表现出一致的有效性，突显了其广泛的适用性和实际应用价值。

> While reasoning-augmented large language models (RLLMs) significantly enhance complex task performance through extended reasoning chains, they inevitably introduce substantial unnecessary token consumption, particularly for simpler problems where Short Chain-of-Thought (Short CoT) suffices. This overthinking phenomenon leads to inefficient resource usage without proportional accuracy gains. To address this issue, we propose Self-Route, a dynamic reasoning framework that automatically selects between general and reasoning modes based on model capability estimation. Our approach introduces a lightweight pre-inference stage to extract capability-aware embeddings from hidden layer representations, enabling real-time evaluation of the model's ability to solve problems. We further construct Gradient-10K, a model difficulty estimation-based dataset with dense complexity sampling, to train the router for precise capability boundary detection. Extensive experiments demonstrate that Self-Route achieves comparable accuracy to reasoning models while reducing token consumption by 30-55\% across diverse benchmarks. The proposed framework demonstrates consistent effectiveness across models with different parameter scales and reasoning paradigms, highlighting its general applicability and practical value.

[Arxiv](https://arxiv.org/abs/2505.20664)