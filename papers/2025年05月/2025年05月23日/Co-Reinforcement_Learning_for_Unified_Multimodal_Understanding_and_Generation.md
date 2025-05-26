# 协作强化学习实现统一的多模态理解和生成

发布时间：2025年05月23日

`LLM理论` `多模态`

> Co-Reinforcement Learning for Unified Multimodal Understanding and Generation

# 摘要

> 本文提出了一种基于群体相对策略优化的强化学习（RL）的开创性探索，旨在同时强化统一多模态大语言模型（ULMs）的生成与理解能力。通过系统性的试点研究，我们发现ULMs在共享策略优化框架下实现双能力协同共进化方面具有显著潜力。基于这一发现，我们引入了	extbf{CoRL}，一个协同强化学习框架，包含一个统一强化学习阶段进行联合优化，以及一个精炼强化学习阶段进行任务特异性增强。借助提出的CoRL框架，我们的最终模型	extbf{ULM-R1}在三个文本到图像生成数据集上实现了平均7%的性能提升，以及在九个多模态理解基准测试中实现了23%的提升。这些结果不仅验证了CoRL的有效性，还突显了强化学习在促进ULMs跨任务协同与优化方面的显著优势。

> This paper presents a pioneering exploration of reinforcement learning (RL) via group relative policy optimization for unified multimodal large language models (ULMs), aimed at simultaneously reinforcing generation and understanding capabilities. Through systematic pilot studies, we uncover the significant potential of ULMs to enable the synergistic co-evolution of dual capabilities within a shared policy optimization framework. Building on this insight, we introduce \textbf{CoRL}, a co-reinforcement learning framework comprising a unified RL stage for joint optimization and a refined RL stage for task-specific enhancement. With the proposed CoRL, our resulting model, \textbf{ULM-R1}, achieves average improvements of \textbf{7%} on three text-to-image generation datasets and \textbf{23%} on nine multimodal understanding benchmarks. These results demonstrate the effectiveness of CoRL and highlight the substantial benefit of reinforcement learning in facilitating cross-task synergy and optimization for ULMs.

[Arxiv](https://arxiv.org/abs/2505.17534)