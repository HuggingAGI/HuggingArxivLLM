# # **EnSToM：通过熵缩放引导向量提升对话系统主题维持能力**
EnSToM 是一种创新方法，利用熵缩放引导向量显著增强了对话系统的主题维持能力。

发布时间：2025年05月22日

`LLM应用` `人工智能` `对话系统`

> EnSToM: Enhancing Dialogue Systems with Entropy-Scaled Steering Vectors for Topic Maintenance

# 摘要

> 小型大型语言模型（sLLMs）以其轻量级和高效的特点，成为资源受限环境的理想选择。然而，在任务导向对话系统中，sLLMs往往难以保持主题一致性，这对服务聊天机器人等场景尤为重要。具体而言，确保模型能够拒绝跑题或恶意输入，并严格遵循其设计功能，以防止滥用并保障可靠性，这一点至关重要。针对这一挑战，现有的激活工程方法通过在推理过程中调整内部激活来应对。尽管这些方法在某些场景下有效，但我们的初步实验发现，它们在确保主题一致性方面存在局限性。因此，我们提出了一种名为基于熵缩放的主题维护引导向量方法（EnSToM）的新方案。EnSToM根据输入的不确定性动态调整引导强度，使模型能够有效处理跑题干扰，同时保持在主题上的准确性。实验结果表明，与微调方法相比，EnSToM在较小的数据规模下实现了显著的性能提升。通过在不牺牲效率的情况下增强主题一致性，我们的方法为提升基于sLLM的对话系统提供了一个稳健的解决方案。

> Small large language models (sLLMs) offer the advantage of being lightweight and efficient, which makes them suitable for resource-constrained environments. However, sLLMs often struggle to maintain topic consistency in task-oriented dialogue systems, which is critical for scenarios such as service chatbots. Specifically, it is important to ensure that the model denies off-topic or malicious inputs and adheres to its intended functionality so as to prevent potential misuse and uphold reliability. Towards this, existing activation engineering approaches have been proposed to manipulate internal activations during inference. While these methods are effective in certain scenarios, our preliminary experiments reveal their limitations in ensuring topic adherence. Therefore, to address this, we propose a novel approach termed Entropy-scaled Steering vectors for Topic Maintenance (EnSToM). EnSToM dynamically adjusts the steering intensity based on input uncertainty, which allows the model to handle off-topic distractors effectively while preserving on-topic accuracy. Our experiments demonstrate that EnSToM achieves significant performance gain with a relatively small data size compared to fine-tuning approaches. By improving topic adherence without compromising efficiency, our approach provides a robust solution for enhancing sLLM-based dialogue systems.

[Arxiv](https://arxiv.org/abs/2505.16526)