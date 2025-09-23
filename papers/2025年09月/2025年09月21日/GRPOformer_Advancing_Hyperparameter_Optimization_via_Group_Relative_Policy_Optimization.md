# GRPOformer：借助群体相对策略优化进阶超参数优化

发布时间：2025年09月21日

`强化学习` `基础理论`

> GRPOformer: Advancing Hyperparameter Optimization via Group Relative Policy Optimization

# 摘要

> 超参数优化（HPO）对提升模型性能至关重要。基于Transformer的超参数优化方法潜力巨大，但现有方法过度依赖大规模历史优化轨迹，且缺乏有效的强化学习（RL）技术支持，导致效率与性能提升受限。受组相对策略优化（GRPO）在大型语言模型（LLMs）中成功应用的启发，我们提出GRPOformer——一种融合强化学习（RL）与Transformer的新型超参数优化框架。该框架中，Transformer负责从历史优化轨迹生成新超参数配置，GRPO则实现快速轨迹构建与从零开始的优化策略学习。此外，我们还引入策略波动正则化（PCR）来增强GRPO训练的稳定性。在OpenML上的实验结果显示，GRPOformer在各类任务中均持续优于基线方法，为强化学习在超参数优化领域的应用带来了新启示。

> Hyperparameter optimization (HPO) plays a critical role in improving model performance. Transformer-based HPO methods have shown great potential; however, existing approaches rely heavily on large-scale historical optimization trajectories and lack effective reinforcement learning (RL) techniques, thereby limiting their efficiency and performance improvements. Inspired by the success of Group Relative Policy Optimization (GRPO) in large language models (LLMs), we propose GRPOformer -- a novel hyperparameter optimization framework that integrates reinforcement learning (RL) with Transformers. In GRPOformer, Transformers are employed to generate new hyperparameter configurations from historical optimization trajectories, while GRPO enables rapid trajectory construction and optimization strategy learning from scratch. Moreover, we introduce Policy Churn Regularization (PCR) to enhance the stability of GRPO training. Experimental results on OpenML demonstrate that GRPOformer consistently outperforms baseline methods across diverse tasks, offering new insights into the application of RL for HPO.

[Arxiv](https://arxiv.org/abs/2509.17105)