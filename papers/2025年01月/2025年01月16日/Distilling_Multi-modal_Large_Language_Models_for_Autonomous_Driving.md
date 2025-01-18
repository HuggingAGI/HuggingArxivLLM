# 多模态大型语言模型的蒸馏与自动驾驶应用

发布时间：2025年01月16日

`Agent

理由：这篇论文主要讨论了自动驾驶系统中的运动规划问题，并提出了一个名为DiMA的系统。DiMA通过将多模态大型语言模型（LLMs）的知识蒸馏到基于视觉的端到端规划器中，从而在保持高效性的同时提升规划器的性能。论文的核心在于如何利用LLMs的知识来增强自动驾驶代理（Agent）的规划能力，因此将其分类为Agent是合适的。` `自动驾驶` `运动规划`

> Distilling Multi-modal Large Language Models for Autonomous Driving

# 摘要

> 自动驾驶对运动规划的安全性要求极高，尤其是在“长尾”场景中。近期，端到端自动驾驶系统通过引入大型语言模型（LLMs）作为规划器，显著提升了对罕见事件的泛化能力。然而，测试时使用LLMs会带来高昂的计算成本。为此，我们提出了DiMA系统，它既能保持无LLM（或基于视觉的）规划器的高效性，又能充分利用LLM的世界知识。DiMA通过一系列精心设计的代理任务，将多模态LLM的知识蒸馏到基于视觉的端到端规划器中。在联合训练策略下，两个网络共享的场景编码器生成结构化表示，这些表示不仅语义清晰，还与规划目标高度一致。值得一提的是，LLM在推理阶段是可选的，从而在不牺牲效率的前提下实现稳健的规划。实验表明，使用DiMA训练后，基于视觉的规划器的L2轨迹误差降低了37%，碰撞率减少了80%，长尾场景中的轨迹误差也减少了44%。此外，DiMA在nuScenes规划基准上达到了业界领先水平。

> Autonomous driving demands safe motion planning, especially in critical "long-tail" scenarios. Recent end-to-end autonomous driving systems leverage large language models (LLMs) as planners to improve generalizability to rare events. However, using LLMs at test time introduces high computational costs. To address this, we propose DiMA, an end-to-end autonomous driving system that maintains the efficiency of an LLM-free (or vision-based) planner while leveraging the world knowledge of an LLM. DiMA distills the information from a multi-modal LLM to a vision-based end-to-end planner through a set of specially designed surrogate tasks. Under a joint training strategy, a scene encoder common to both networks produces structured representations that are semantically grounded as well as aligned to the final planning objective. Notably, the LLM is optional at inference, enabling robust planning without compromising on efficiency. Training with DiMA results in a 37% reduction in the L2 trajectory error and an 80% reduction in the collision rate of the vision-based planner, as well as a 44% trajectory error reduction in longtail scenarios. DiMA also achieves state-of-the-art performance on the nuScenes planning benchmark.

[Arxiv](https://arxiv.org/abs/2501.09757)