# 静默思考，快速思考：大型语言模型推理链的动态潜在压缩

发布时间：2025年05月22日

`LLM应用`

> Think Silently, Think Fast: Dynamic Latent Compression of LLM Reasoning Chains

# 摘要

> 大型语言模型（LLMs）通过链式推理（CoT）展现出了卓越的能力，但这种基于token的推理链在计算上成本高昂且效率低下。本文中，我们引入了压缩潜在推理（CoLaR），这是一种新颖的框架，通过两阶段的训练方法在潜在空间中动态压缩推理过程。首先，在监督微调阶段，CoLaR超越了传统的下一个token预测，引入了辅助的下一个压缩嵌入预测目标。这一过程通过随机采样预定义范围内的压缩因子，将连续token的嵌入进行融合，并训练一个专门的潜在头来预测后续压缩嵌入的分布。其次，我们通过强化学习（RL）进一步优化CoLaR，利用潜在头的非确定性特性，探索多样化的推理路径，并利用更紧凑的推理链。这一方法使CoLaR能够：i）在密集潜在层面（即静默地）进行推理，大幅缩短推理链长度；ii）在推理时，通过简单的提示指定压缩因子，动态调整推理速度。在四个数学推理数据集上的广泛实验表明，与基于潜在的基线方法相比，CoLaR在相近的压缩比下准确率提高了14.1%，相较于显式的CoT方法，推理链长度缩短了53.3%，性能仅下降4.8%。此外，当应用于更具挑战性的数学推理任务时，我们的强化学习增强的CoLaR实现了高达5.4%的性能提升，同时将潜在推理链长度大幅缩减了82.8%。代码和模型将在接收后发布。

> Large Language Models (LLMs) achieve superior performance through Chain-of-Thought (CoT) reasoning, but these token-level reasoning chains are computationally expensive and inefficient. In this paper, we introduce Compressed Latent Reasoning (CoLaR), a novel framework that dynamically compresses reasoning processes in latent space through a two-stage training approach. First, during supervised fine-tuning, CoLaR extends beyond next-token prediction by incorporating an auxiliary next compressed embedding prediction objective. This process merges embeddings of consecutive tokens using a compression factor randomly sampled from a predefined range, and trains a specialized latent head to predict distributions of subsequent compressed embeddings. Second, we enhance CoLaR through reinforcement learning (RL) that leverages the latent head's non-deterministic nature to explore diverse reasoning paths and exploit more compact ones. This approach enables CoLaR to: i) perform reasoning at a dense latent level (i.e., silently), substantially reducing reasoning chain length, and ii) dynamically adjust reasoning speed at inference time by simply prompting the desired compression factor. Extensive experiments across four mathematical reasoning datasets demonstrate that CoLaR achieves 14.1% higher accuracy than latent-based baseline methods at comparable compression ratios, and reduces reasoning chain length by 53.3% with only 4.8% performance degradation compared to explicit CoT method. Moreover, when applied to more challenging mathematical reasoning tasks, our RL-enhanced CoLaR demonstrates performance gains of up to 5.4% while dramatically reducing latent reasoning chain length by 82.8%. The code and models will be released upon acceptance.

[Arxiv](https://arxiv.org/abs/2505.16552)