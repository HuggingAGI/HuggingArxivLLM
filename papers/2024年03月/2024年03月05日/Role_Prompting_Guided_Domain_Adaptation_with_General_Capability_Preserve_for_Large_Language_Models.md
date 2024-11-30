# 在保持LLM广泛能力的前提下，我们提出了一种通过角色提示驱动的领域适应技术。

发布时间：2024年03月05日

`Agent`

> Role Prompting Guided Domain Adaptation with General Capability Preserve for Large Language Models

# 摘要

> 随着LLMs在专业应用中的热度攀升，一个问题愈发突出：一旦对特定领域进行定制，LLMs常会遭遇灾难性遗忘，这不仅削弱其普遍适用性，还可能造成用户体验下滑。同时，兼顾多个领域打造一款全能模型时，由于领域间相互混淆，往往会使整体性能下滑。因此，我们提出了一种名为“REGA”的角色提示引导多领域适应策略。该新颖方法通过三大核心机制来高效应对多领域LLM的适应难题：1) 自我蒸馏技术构造和回放一般领域样本，减轻灾难性遗忘的影响；2) 角色提示为一般领域设定中心提示，并为每个特定领域赋予专属角色提示，从而在训练阶段最大限度减少领域间的混淆；3) 角色整合则将一小部分特定领域数据巧妙融入一般领域数据中，在中心提示的引导下共同训练。在实际推理阶段，只需采用中心提示即可，无需根据不同领域频繁切换提示。实验结果显示，REGA能有效缓解灾难性遗忘与领域间混淆的问题，从而在保持强大通用性的同时，提升特定领域的性能表现，优于常规微调模型。

> The growing interest in Large Language Models (LLMs) for specialized applications has revealed a significant challenge: when tailored to specific domains, LLMs tend to experience catastrophic forgetting, compromising their general capabilities and leading to a suboptimal user experience. Additionally, crafting a versatile model for multiple domains simultaneously often results in a decline in overall performance due to confusion between domains. In response to these issues, we present the RolE Prompting Guided Multi-Domain Adaptation (REGA) strategy. This novel approach effectively manages multi-domain LLM adaptation through three key components: 1) Self-Distillation constructs and replays general-domain exemplars to alleviate catastrophic forgetting. 2) Role Prompting assigns a central prompt to the general domain and a unique role prompt to each specific domain to minimize inter-domain confusion during training. 3) Role Integration reuses and integrates a small portion of domain-specific data to the general-domain data, which are trained under the guidance of the central prompt. The central prompt is used for a streamlined inference process, removing the necessity to switch prompts for different domains. Empirical results demonstrate that REGA effectively alleviates catastrophic forgetting and inter-domain confusion. This leads to improved domain-specific performance compared to standard fine-tuned models, while still preserving robust general capabilities.

[Arxiv](https://arxiv.org/abs/2403.02756)