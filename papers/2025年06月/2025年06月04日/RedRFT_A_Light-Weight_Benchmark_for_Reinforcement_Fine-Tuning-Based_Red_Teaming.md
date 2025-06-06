# RedRFT：基于强化微调的轻量级红队对抗测试基准

发布时间：2025年06月04日

`LLM应用` `基准测试`

> RedRFT: A Light-Weight Benchmark for Reinforcement Fine-Tuning-Based Red Teaming

# 摘要

> 红队测试在识别和缓解大型语言模型（LLMs）漏洞方面已被证明是有效的。在现有红队测试技术中，强化微调（RFT）作为一种有前景的策略脱颖而出。然而，由于缺乏统一的基准，当前基于RFT的红队测试方法受到了限制。实现细节，尤其是在基于近端策略优化（PPO）的RFT中，对结果的稳定性和可重复性产生了显著影响。为了解决这一问题，我们引入了RedRFT，这是一个轻量级基准，旨在简化和标准化基于RFT的红队测试的实现和评估。

RedRFT结合了单文件CleanRL和高度模块化的Tianshou的设计优势，提供了高质量的单文件红队测试实现和模块化的PPO核心组件，如通用优势估计器。它支持多种分词和句子多样性指标，具备模块化的内在奖励计算功能，便于即插即用的实验。为了阐明它们对RFT性能的影响，我们对关键组件进行了广泛的消融研究，包括低秩适配（LoRA）、Kullback-Leibler（KL）散度和拉格朗日乘数。

我们希望这项工作能够有助于：1）全面理解基于RFT的红队测试算法的实现细节；2）实现基于RFT的红队测试的快速创新特性原型设计。该基准的代码可在https://github.com/x-zheng16/RedRFT.git获取。

> Red teaming has proven to be an effective method for identifying and mitigating vulnerabilities in Large Language Models (LLMs). Reinforcement Fine-Tuning (RFT) has emerged as a promising strategy among existing red teaming techniques. However, a lack of a unified benchmark hinders current RFT-based red teaming methods. Implementation details, especially in Proximal Policy Optimization (PPO)-based RFT, significantly affect outcome stability and reproducibility. To address this issue, we introduce RedRFT, a lightweight benchmark designed to simplify and standardize the implementation and evaluation of RFT-based red teaming. RedRFT combines the design strengths of both single-file CleanRL and highly modularized Tianshou, offering high-quality single-file red teaming implementations and modular PPO core components, such as the General Advantage Estimator. It supports a variety of token and sentence diversity metrics, featuring modularized intrinsic reward computation that facilitates plug-and-play experimentation. To clarify their influence on RFT performance, we conducted an extensive ablation study on key components, including Low-Rank Adaptation (LoRA), Kullback-Leibler (KL) divergence, and Lagrange Multiplier. We hope this work contributes to 1) gaining a comprehensive understanding of the implementation nuances of RFT-based red teaming algorithms, and 2) enabling rapid prototyping of innovative features for RFT-based red teaming. Code for the benchmark can be accessed at https://github.com/x-zheng16/RedRFT.git.

[Arxiv](https://arxiv.org/abs/2506.04302)