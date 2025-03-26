# OS-Kairos：面向多语言大模型驱动的图形用户界面智能体的自适应交互

发布时间：2025年02月26日

`Agent` `人机交互` `软件工程`

> OS-Kairos: Adaptive Interaction for MLLM-Powered GUI Agents

# 摘要

> 多模态大型语言模型驱动的自主图形用户界面 (GUI) 代理展现了巨大潜力。然而，一个关键但尚未充分探索的问题仍待解决：过度执行。这种情况发生时，代理在没有充分评估行动信心的情况下完全自主执行任务，破坏了与人类的自适应协作。这在涉及模糊指令、意外中断和环境干扰的复杂场景中尤为危险。为应对这一挑战，我们推出了 OS-Kairos，这是一种自适应 GUI 代理，能够预测每一步交互的信心水平，并高效决定是自主行动还是寻求人类干预。OS-Kairos 的开发基于两大关键机制：(i) 协作探查，即在每一步交互中注释信心分数；(ii) 信心驱动的交互，利用这些信心分数实现自适应交互能力。实验结果表明，OS-Kairos 在复杂场景数据集以及 AITZ 和 Meta-GUI 等 established benchmarks 上显著优于现有模型，任务成功率提高了 24.59\% 至 87.29\%。OS-Kairos 通过优先考虑有效性、通用性、可扩展性和效率，实现了自适应的人机协作，推动了现实世界 GUI 交互的发展。数据集和代码可在 https://github.com/Wuzheng02/OS-Kairos 获取。

> Autonomous graphical user interface (GUI) agents powered by multimodal large language models have shown great promise. However, a critical yet underexplored issue persists: over-execution, where the agent executes tasks in a fully autonomous way, without adequate assessment of its action confidence to compromise an adaptive human-agent collaboration. This poses substantial risks in complex scenarios, such as those involving ambiguous user instructions, unexpected interruptions, and environmental hijacks. To address the issue, we introduce OS-Kairos, an adaptive GUI agent capable of predicting confidence levels at each interaction step and efficiently deciding whether to act autonomously or seek human intervention. OS-Kairos is developed through two key mechanisms: (i) collaborative probing that annotates confidence scores at each interaction step; (ii) confidence-driven interaction that leverages these confidence scores to elicit the ability of adaptive interaction. Experimental results show that OS-Kairos substantially outperforms existing models on our curated dataset featuring complex scenarios, as well as on established benchmarks such as AITZ and Meta-GUI, with 24.59\%$\sim$87.29\% improvements in task success rate. OS-Kairos facilitates an adaptive human-agent collaboration, prioritizing effectiveness, generality, scalability, and efficiency for real-world GUI interaction. The dataset and codes are available at https://github.com/Wuzheng02/OS-Kairos.

[Arxiv](https://arxiv.org/abs/2503.16465)