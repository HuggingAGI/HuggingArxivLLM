# VideoAgent2：基于不确定性感知的CoT方法，提升LLM智能体系统对长视频的理解能力。

发布时间：2025年04月06日

`Agent` `计算机视觉` `长视频分析`

> VideoAgent2: Enhancing the LLM-Based Agent System for Long-Form Video Understanding by Uncertainty-Aware CoT

# 摘要

> 长视频理解在计算机视觉领域日益重要，同时也是一个极具挑战性的任务。基于智能体的方法正逐渐成为处理长视频的热门选择，因为它们能够处理较长的视频序列，并整合多种工具以捕捉细微信息。然而，现有方法仍面临多重挑战：(1) 它们往往仅依赖大型语言模型（LLMs）的推理能力，缺乏专门针对长视频场景的推理增强机制；(2) 它们对外部工具的错误或噪声仍然较为敏感。

为解决这些问题，我们提出了一种专为长视频分析设计的思维链（CoT）流程。我们的具有计划调整模式的CoT使LLM能够逐步规划并适应其信息收集策略。我们还引入了对LLM和外部工具的启发式不确定性估计，以指导CoT过程。这使得LLM能够评估新收集信息的可靠性，优化其收集策略，并在合成最终答案时做出更稳健的决策。

实证实验表明，我们的不确定性感知CoT有效缓解了外部工具的噪声问题，从而生成了更可靠的输出。我们将在名为VideoAgent2的系统中实现这一方法，该系统还包括通用上下文获取和专用工具设计等额外模块。在三个专门的长视频基准测试（及其子集）上的评估表明，VideoAgent2相较于前一代基于智能体的方法VideoAgent平均提升了13.1%的性能，并在所有零样本方法中取得了领先表现。


> Long video understanding has emerged as an increasingly important yet challenging task in computer vision. Agent-based approaches are gaining popularity for processing long videos, as they can handle extended sequences and integrate various tools to capture fine-grained information. However, existing methods still face several challenges: (1) they often rely solely on the reasoning ability of large language models (LLMs) without dedicated mechanisms to enhance reasoning in long video scenarios; and (2) they remain vulnerable to errors or noise from external tools. To address these issues, we propose a specialized chain-of-thought (CoT) process tailored for long video analysis. Our proposed CoT with plan-adjust mode enables the LLM to incrementally plan and adapt its information-gathering strategy. We further incorporate heuristic uncertainty estimation of both the LLM and external tools to guide the CoT process. This allows the LLM to assess the reliability of newly collected information, refine its collection strategy, and make more robust decisions when synthesizing final answers. Empirical experiments show that our uncertainty-aware CoT effectively mitigates noise from external tools, leading to more reliable outputs. We implement our approach in a system called VideoAgent2, which also includes additional modules such as general context acquisition and specialized tool design. Evaluation on three dedicated long video benchmarks (and their subsets) demonstrates that VideoAgent2 outperforms the previous state-of-the-art agent-based method, VideoAgent, by an average of 13.1% and achieves leading performance among all zero-shot approaches

[Arxiv](https://arxiv.org/abs/2504.04471)