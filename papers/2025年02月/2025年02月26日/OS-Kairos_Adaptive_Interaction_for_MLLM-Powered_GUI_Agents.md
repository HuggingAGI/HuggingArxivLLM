# OS-Kairos：基于多模态大型语言模型的图形用户界面代理自适应交互。

发布时间：2025年02月26日

`Agent` `人机交互` `协作与交互`

> OS-Kairos: Adaptive Interaction for MLLM-Powered GUI Agents

# 摘要

> 基于多模态大型语言模型的自主图形用户界面（GUI）代理展现出巨大潜力。然而，一个关键但尚未充分探索的问题仍然存在：过度执行，即代理以完全自主的方式执行任务，未能充分评估其行动信心，从而可能破坏自适应的人机协作。这在复杂场景中带来了重大风险，例如涉及模糊用户指令、意外中断和环境干扰的情况。为了解决这一问题，我们引入了OS-Kairos，这是一种自适应GUI代理，能够预测每一步交互的信心水平，并高效决定是自主执行还是寻求人类干预。OS-Kairos通过两种关键机制开发而成：(i) 协作探测，为每一步交互标注信心分数；(ii) 基于信心的交互，利用这些信心分数来实现自适应交互的能力。实验结果表明，OS-Kairos在我们精心策划的复杂场景数据集以及 established benchmarks such as AITZ and Meta-GUI 上显著优于现有模型，任务成功率提高了24.59%至87.29%。OS-Kairos促进了自适应的人机协作，优先考虑有效性、通用性、可扩展性和效率，以实现现实世界的GUI交互。数据集和代码可在https://github.com/Wuzheng02/OS-Kairos获取。

> Autonomous graphical user interface (GUI) agents powered by multimodal large language models have shown great promise. However, a critical yet underexplored issue persists: over-execution, where the agent executes tasks in a fully autonomous way, without adequate assessment of its action confidence to compromise an adaptive human-agent collaboration. This poses substantial risks in complex scenarios, such as those involving ambiguous user instructions, unexpected interruptions, and environmental hijacks. To address the issue, we introduce OS-Kairos, an adaptive GUI agent capable of predicting confidence levels at each interaction step and efficiently deciding whether to act autonomously or seek human intervention. OS-Kairos is developed through two key mechanisms: (i) collaborative probing that annotates confidence scores at each interaction step; (ii) confidence-driven interaction that leverages these confidence scores to elicit the ability of adaptive interaction. Experimental results show that OS-Kairos substantially outperforms existing models on our curated dataset featuring complex scenarios, as well as on established benchmarks such as AITZ and Meta-GUI, with 24.59\%$\sim$87.29\% improvements in task success rate. OS-Kairos facilitates an adaptive human-agent collaboration, prioritizing effectiveness, generality, scalability, and efficiency for real-world GUI interaction. The dataset and codes are available at https://github.com/Wuzheng02/OS-Kairos.

[Arxiv](https://arxiv.org/abs/2503.16465)