# CogSteer: 认知启发的选择性层干预，助力大型语言模型高效语义引导

发布时间：2024年10月23日

`LLM理论

理由：这篇论文主要探讨了如何通过眼动测量来解读大型语言模型（LLMs）的行为，并提出了一种启发式引导层选择的方法。研究重点在于理解LLMs的内部工作机制，并通过实验验证了该方法在提升模型可解释性和安全性方面的有效性。因此，这篇论文属于LLM理论范畴，因为它涉及对LLMs行为的理论分析和解释。` `人工智能`

> CogSteer: Cognition-Inspired Selective Layer Intervention for Efficient Semantic Steering in Large Language Models

# 摘要

> 尽管LLMs能力强大，但其可解释性不足，且可能生成有害内容。虽然将LLMs作为基础模型并应用语义引导方法已很常见，但我们认为，有效的方法应基于对LLM行为的深入理解。为此，我们提出使用眼动测量来解读跨层的LLM行为。我们发现，LLMs在不同层中表现出类似人类注视的模式，且各层功能各异。受此启发，我们引入了一种启发式引导层选择，并通过微调和推理将其应用于层干预方法。以语言毒化和去毒化为测试平台，我们证明了CogSteer方法在毒性评分上表现更优，同时节省了97%的计算资源和60%的训练时间。这一模型无关的方法可广泛应用于各种LLMs，提升其可解释性，增强安全部署的可信度。

> Despite their impressive capabilities, large language models (LLMs) often lack interpretability and can generate toxic content. While using LLMs as foundation models and applying semantic steering methods are widely practiced, we believe that efficient methods should be based on a thorough understanding of LLM behavior. To this end, we propose using eye movement measures to interpret LLM behavior across layers. We find that LLMs exhibit patterns similar to human gaze across layers and different layers function differently. Inspired by these findings, we introduce a heuristic steering layer selection and apply it to layer intervention methods via fine-tuning and inference. Using language toxification and detoxification as test beds, we demonstrate that our proposed CogSteer methods achieve better results in terms of toxicity scores while efficiently saving 97% of the computational resources and 60% of the training time. Our model-agnostic approach can be adopted into various LLMs, contributing to their interpretability and promoting trustworthiness for safe deployment.

[Arxiv](https://arxiv.org/abs/2410.17714)