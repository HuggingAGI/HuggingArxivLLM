# PKRD-CoT：自动驾驶中多模态大型语言模型的统一思维链提示

发布时间：2024年12月02日

`LLM应用` `自动驾驶` `人工智能`

> PKRD-CoT: A Unified Chain-of-thought Prompting for Multi-Modal Large Language Models in Autonomous Driving

# 摘要

> 在自动驾驶情境中，直接借助强大的多模态大型语言模型（MLLMs）的能力，正引发日益浓厚的兴趣。然而，设计和训练端到端的自动驾驶模型成本高昂且复杂，这对众多企业和研究实体而言颇具挑战。为应对此问题，我们的研究通过提出名为 PKRD-CoT 的零样本思维链提示设计，探索了 MLLMs 与自动驾驶系统的无缝融合。PKRD-CoT 基于自动驾驶的四项基本能力：感知、知识、推理和决策。这使其尤其适合通过逐步效仿人类思维过程来理解和应对动态驾驶环境，进而增强实时场景中的决策能力。我们的设计让 MLLMs 能够在无先前经验的情况下处理问题，从而提升其在非结构化自动驾驶环境中的实用性。在实验中，我们展示了配备 PKRD-CoT 的 GPT-4.0 在自动驾驶任务中的卓越表现，凸显了其在自动驾驶场景中的有效性。此外，我们的基准分析揭示了 PKRD-CoT 对于其他 MLLMs（如 Claude、LLava1.6 和 Qwen-VL-Plus）的良好可行性。总体而言，本研究为 GPT-4.0 及其他 MLLMs 在自动驾驶领域贡献了新颖且统一的提示设计框架，同时通过全面比较严格评估了这些广受认可的 MLLMs 在自动驾驶领域的效能。

> There is growing interest in leveraging the capabilities of robust Multi-Modal Large Language Models (MLLMs) directly within autonomous driving contexts. However, the high costs and complexity of designing and training end-to-end autonomous driving models make them challenging for many enterprises and research entities. To address this, our study explores a seamless integration of MLLMs into autonomous driving systems by proposing a Zero-Shot Chain-of-Thought (Zero-Shot-CoT) prompt design named PKRD-CoT. PKRD-CoT is based on the four fundamental capabilities of autonomous driving: perception, knowledge, reasoning, and decision-making. This makes it particularly suitable for understanding and responding to dynamic driving environments by mimicking human thought processes step by step, thus enhancing decision-making in real-time scenarios. Our design enables MLLMs to tackle problems without prior experience, thereby increasing their utility within unstructured autonomous driving environments. In experiments, we demonstrate the exceptional performance of GPT-4.0 with PKRD-CoT across autonomous driving tasks, highlighting its effectiveness in autonomous driving scenarios. Additionally, our benchmark analysis reveals the promising viability of PKRD-CoT for other MLLMs, such as Claude, LLava1.6, and Qwen-VL-Plus. Overall, this study contributes a novel and unified prompt-design framework for GPT-4.0 and other MLLMs in autonomous driving, while also rigorously evaluating the efficacy of these widely recognized MLLMs in the autonomous driving domain through comprehensive comparisons.

[Arxiv](https://arxiv.org/abs/2412.02025)