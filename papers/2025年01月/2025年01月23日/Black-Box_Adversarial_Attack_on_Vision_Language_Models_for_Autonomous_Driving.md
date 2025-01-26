# 自动驾驶视觉语言模型的黑盒对抗攻击

发布时间：2025年01月23日

`LLM应用

理由：这篇论文主要讨论了视觉语言模型（VLMs）在自动驾驶（AD）中的应用，并针对这些模型的黑盒对抗性攻击提出了新的方法。虽然论文中提到了对抗性攻击和模型的安全性，但其核心内容仍然是关于如何在实际应用（自动驾驶）中使用和改进这些模型。因此，这篇论文更适合归类为“LLM应用”。` `自动驾驶` `对抗性攻击`

> Black-Box Adversarial Attack on Vision Language Models for Autonomous Driving

# 摘要

> # 摘要
视觉语言模型（VLMs）通过增强推理能力显著推动了自动驾驶（AD）的发展，但这些模型仍极易受到对抗性攻击。尽管现有研究已对白盒攻击有所探索，但更具挑战性的黑盒场景因其固有难度而鲜有涉足。本文首次针对AD中的VLMs设计了黑盒对抗性攻击。我们识别了两个关键挑战：AD系统中驾驶推理链的有效性和驾驶场景的动态性。为此，我们提出了级联对抗性破坏（CAD）。CAD首先通过生成和注入欺骗性语义，针对低级推理崩溃进行决策链破坏，确保扰动在整个决策链中持续有效。在此基础上，我们提出风险场景诱导，利用替代VLM理解和构建在当前驾驶环境中可能导致关键错误的高级风险场景，以应对动态适应问题。在多个AD VLMs和基准上的广泛实验表明，CAD的攻击效果达到业界领先水平，显著优于现有方法（平均提升13.43%）。此外，我们通过对VLMs驱动的AD车辆进行实际攻击验证了其适用性，结果显示路线完成率下降61.11%，车辆直接撞上带有对抗性补丁的障碍车辆。最后，我们发布了包含18,808个对抗性视觉-问题-答案对的CADA数据集，以推动该领域的进一步研究。代码和数据集将在论文被接受后公开。

> Vision-language models (VLMs) have significantly advanced autonomous driving (AD) by enhancing reasoning capabilities; however, these models remain highly susceptible to adversarial attacks. While existing research has explored white-box attacks to some extent, the more practical and challenging black-box scenarios remain largely underexplored due to their inherent difficulty. In this paper, we take the first step toward designing black-box adversarial attacks specifically targeting VLMs in AD. We identify two key challenges for achieving effective black-box attacks in this context: the effectiveness across driving reasoning chains in AD systems and the dynamic nature of driving scenarios. To address this, we propose Cascading Adversarial Disruption (CAD). It first introduces Decision Chain Disruption, which targets low-level reasoning breakdown by generating and injecting deceptive semantics, ensuring the perturbations remain effective across the entire decision-making chain. Building on this, we present Risky Scene Induction, which addresses dynamic adaptation by leveraging a surrogate VLM to understand and construct high-level risky scenarios that are likely to result in critical errors in the current driving contexts. Extensive experiments conducted on multiple AD VLMs and benchmarks demonstrate that CAD achieves state-of-the-art attack effectiveness, significantly outperforming existing methods (+13.43% on average). Moreover, we validate its practical applicability through real-world attacks on AD vehicles powered by VLMs, where the route completion rate drops by 61.11% and the vehicle crashes directly into the obstacle vehicle with adversarial patches. Finally, we release CADA dataset, comprising 18,808 adversarial visual-question-answer pairs, to facilitate further evaluation and research in this critical domain. Our codes and dataset will be available after paper's acceptance.

[Arxiv](https://arxiv.org/abs/2501.13563)