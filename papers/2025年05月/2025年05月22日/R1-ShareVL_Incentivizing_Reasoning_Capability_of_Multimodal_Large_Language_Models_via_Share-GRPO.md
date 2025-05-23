# R1-ShareVL：提升多模态大型语言模型的推理能力

发布时间：2025年05月22日

`LLM理论` `推理系统`

> R1-ShareVL: Incentivizing Reasoning Capability of Multimodal Large Language Models via Share-GRPO

# 摘要

> 本研究旨在通过强化学习（RL）激励多模态大型语言模型（MLLMs）的推理能力，并提出了一种名为Share-GRPO的新方法，有效缓解了RL中的稀疏奖励和优势消失问题。具体而言，Share-GRPO通过数据变换技术扩展问题空间，鼓励MLLM在扩展空间中探索多样化的推理轨迹，并在问题间共享这些轨迹。此外，该方法在优势计算中共享奖励信息，层次化估计问题变体间的解决方案优势，从而更精确地评估相对优势并提升策略训练的稳定性。在六个推理基准上的实验结果验证了我们方法的优越性。代码即将在https://github.com/HJYao00/R1-ShareVL上开源。

> In this work, we aim to incentivize the reasoning ability of Multimodal Large Language Models (MLLMs) via reinforcement learning (RL) and develop an effective approach that mitigates the sparse reward and advantage vanishing issues during RL. To this end, we propose Share-GRPO, a novel RL approach that tackle these issues by exploring and sharing diverse reasoning trajectories over expanded question space. Specifically, Share-GRPO first expands the question space for a given question via data transformation techniques, and then encourages MLLM to effectively explore diverse reasoning trajectories over the expanded question space and shares the discovered reasoning trajectories across the expanded questions during RL. In addition, Share-GRPO also shares reward information during advantage computation, which estimates solution advantages hierarchically across and within question variants, allowing more accurate estimation of relative advantages and improving the stability of policy training. Extensive evaluations over six widely-used reasoning benchmarks showcase the superior performance of our method. Code will be available at https://github.com/HJYao00/R1-ShareVL.

[Arxiv](https://arxiv.org/abs/2505.16673)