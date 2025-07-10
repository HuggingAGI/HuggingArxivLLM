# 刻意学习，本能行动：解锁多模态大语言模型的测试时推理能力

发布时间：2025年07月09日

`LLM应用` `人工智能`

> Learning Deliberately, Acting Intuitively: Unlocking Test-Time Reasoning in Multimodal LLMs

# 摘要

> 推理能力对大型语言模型至关重要，尤其在解决数学问题等复杂任务时表现突出。然而，多模态推理研究仍需深入探索模态对齐与训练成本的关系。现有方法多依赖额外标注与规则奖励来提升能力，但增加了训练成本并限制了扩展性。为解决此问题，我们提出“深思熟虑到直觉推理框架”（D2I），无需额外标注和复杂奖励即可提升多模态大语言模型（MLLMs）的能力。在训练中，我们通过规则格式奖励设定深思熟虑策略，增强模态对齐；在评估时，推理风格转为直觉式，隐性体现模型能力。实验表明，D2I在内部与跨领域测试中均超越现有方法。研究凸显了格式奖励在培养可迁移推理技能中的作用，并为推理深度与响应灵活性的解耦提供了新方向。

> Reasoning is a key capability for large language models (LLMs), particularly when applied to complex tasks such as mathematical problem solving. However, multimodal reasoning research still requires further exploration of modality alignment and training costs. Many of these approaches rely on additional data annotation and relevant rule-based rewards to enhance the understanding and reasoning ability, which significantly increases training costs and limits scalability. To address these challenges, we propose the Deliberate-to-Intuitive reasoning framework (D2I) that improves the understanding and reasoning ability of multimodal LLMs (MLLMs) without extra annotations and complex rewards. Specifically, our method sets deliberate reasoning strategies to enhance modality alignment only through the rule-based format reward during training. While evaluating, the reasoning style shifts to intuitive, which removes deliberate reasoning strategies during training and implicitly reflects the model's acquired abilities in the response. D2I outperforms baselines across both in-domain and out-of-domain benchmarks. Our findings highlight the role of format reward in fostering transferable reasoning skills in MLLMs, and inspire directions for decoupling training-time reasoning depth from test-time response flexibility.

[Arxiv](https://arxiv.org/abs/2507.06999)