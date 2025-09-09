# floq：基于流匹配训练评论家以扩展基于价值的强化学习中的计算

发布时间：2025年09月08日

`强化学习` `基础理论`

> floq: Training Critics via Flow-Matching for Scaling Compute in Value-Based RL

# 摘要

> 现代大规模机器学习技术的一大特色是采用能为中间计算提供密集监督的训练目标，例如语言模型中通过教师强制预测下一个token，或是扩散模型中逐步去噪。这让模型能以可泛化的方式掌握复杂函数。基于这一发现，我们探索了迭代计算对强化学习（RL）中时序差分（TD）方法的提升作用。这类方法通常以整体形式表示价值函数，不涉及迭代计算。为此，我们提出了floq（流匹配Q函数）——一种利用速度场对Q函数进行参数化，并采用生成建模中常用的流匹配技术进行训练的方法。该流对应的速度场通过TD学习目标训练，其自举过程利用目标速度场生成的值，而目标速度场则通过多步数值积分计算得出。关键在于，通过合理设置积分步数，floq相比整体架构能更精细地控制和扩展Q函数的容量。在一系列高难度的离线RL基准测试和在线微调任务中，floq将性能提升了近1.8倍。其容量扩展能力远超标准TD学习架构，充分彰显了迭代计算在价值学习中的巨大潜力。

> A hallmark of modern large-scale machine learning techniques is the use of training objectives that provide dense supervision to intermediate computations, such as teacher forcing the next token in language models or denoising step-by-step in diffusion models. This enables models to learn complex functions in a generalizable manner. Motivated by this observation, we investigate the benefits of iterative computation for temporal difference (TD) methods in reinforcement learning (RL). Typically they represent value functions in a monolithic fashion, without iterative compute. We introduce floq (flow-matching Q-functions), an approach that parameterizes the Q-function using a velocity field and trains it using techniques from flow-matching, typically used in generative modeling. This velocity field underneath the flow is trained using a TD-learning objective, which bootstraps from values produced by a target velocity field, computed by running multiple steps of numerical integration. Crucially, floq allows for more fine-grained control and scaling of the Q-function capacity than monolithic architectures, by appropriately setting the number of integration steps. Across a suite of challenging offline RL benchmarks and online fine-tuning tasks, floq improves performance by nearly 1.8x. floq scales capacity far better than standard TD-learning architectures, highlighting the potential of iterative computation for value learning.

[Arxiv](https://arxiv.org/abs/2509.06863)