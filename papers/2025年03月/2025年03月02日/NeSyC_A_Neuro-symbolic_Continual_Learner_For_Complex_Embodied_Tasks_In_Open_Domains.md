# NeSyC：针对开放领域中的复杂具身任务的神经符号持续学习方法

发布时间：2025年03月02日

`Agent` `机器人` `人工智能`

> NeSyC: A Neuro-symbolic Continual Learner For Complex Embodied Tasks In Open Domains

# 摘要

> 我们探索神经符号方法，以实现可操作知识的泛化，使具身智能体在开放域环境中更高效地处理复杂任务。具身智能体面临的关键挑战在于如何在不同环境和情境下实现知识的泛化，因为有限的经验往往限制了它们的知识范围。

为了解决这一问题，我们提出了一种新型框架NeSyC，这是一种神经符号持续学习器。它通过结合大型语言模型（LLMs）和符号工具，持续地从有限经验中构建和验证知识，模拟假说演绎模型。

具体而言，我们在NeSyC中设计了一种对比泛化改进方案。该方案通过LLMs迭代生成假设，并借助符号工具进行对比验证。这一方案不仅强化了对可接受动作的合理性论证，还减少了对不可接受动作的推理。

此外，我们还引入了一种基于记忆的监控方案。该方案能够高效检测动作错误，并在跨域环境中触发知识精炼过程。

我们在多样化的具身任务基准上进行了实验，包括ALFWorld、VirtualHome、Minecraft、RLBench和一个真实世界的机器人场景。实验结果表明，NeSyC在解决开放域环境中各种复杂具身任务方面表现出色。


> We explore neuro-symbolic approaches to generalize actionable knowledge, enabling embodied agents to tackle complex tasks more effectively in open-domain environments. A key challenge for embodied agents is the generalization of knowledge across diverse environments and situations, as limited experiences often confine them to their prior knowledge. To address this issue, we introduce a novel framework, NeSyC, a neuro-symbolic continual learner that emulates the hypothetico-deductive model by continually formulating and validating knowledge from limited experiences through the combined use of Large Language Models (LLMs) and symbolic tools. Specifically, we devise a contrastive generality improvement scheme within NeSyC, which iteratively generates hypotheses using LLMs and conducts contrastive validation via symbolic tools. This scheme reinforces the justification for admissible actions while minimizing the inference of inadmissible ones. Additionally, we incorporate a memory-based monitoring scheme that efficiently detects action errors and triggers the knowledge refinement process across domains. Experiments conducted on diverse embodied task benchmarks-including ALFWorld, VirtualHome, Minecraft, RLBench, and a real-world robotic scenario-demonstrate that NeSyC is highly effective in solving complex embodied tasks across a range of open-domain environments.

[Arxiv](https://arxiv.org/abs/2503.00870)