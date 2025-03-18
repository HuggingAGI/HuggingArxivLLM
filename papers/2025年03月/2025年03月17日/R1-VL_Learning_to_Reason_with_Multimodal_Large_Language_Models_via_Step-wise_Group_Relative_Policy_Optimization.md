# # R1-VL：通过逐步分组相对策略优化学习利用多模态大型语言模型进行推理

发布时间：2025年03月17日

`LLM理论` `人工智能`

> R1-VL: Learning to Reason with Multimodal Large Language Models via Step-wise Group Relative Policy Optimization

# 摘要

> 近期研究主要通过在高质量的链式推理数据上进行监督微调来提升多语言大模型（MLLMs）的推理能力，但这种做法往往导致模型仅能模仿成功的推理路径，而未能理解错误推理路径的本质。本研究致力于超越被动模仿成功推理路径的局限，提升多语言大模型的推理能力。为此，我们设计了基于逐步分组相对策略优化（StepGRPO）的新在线强化学习框架，通过简单、有效且密集的逐步奖励机制，使多语言大模型能够自我提升推理能力。具体而言，StepGRPO引入了两种创新性的基于规则的推理奖励机制：逐步推理准确性奖励（StepRAR）和逐步推理有效性奖励（StepRVR）。StepRAR通过软关键步骤匹配技术，奖励包含必要中间推理步骤的推理路径，而StepRVR则通过推理完整性和逻辑评估策略，奖励遵循结构良好且逻辑一致推理过程的推理路径。借助提出的StepGRPO框架，我们推出了R1-VL系列多语言大模型，该系列模型在逐步推理方面展现出卓越的能力。在8个基准测试上的广泛实验结果证明了我们方法的优越性。

> Recent studies generally enhance MLLMs' reasoning capabilities via supervised fine-tuning on high-quality chain-of-thought reasoning data, which often leads models to merely imitate successful reasoning paths without understanding what the wrong reasoning paths are. In this work, we aim to enhance the MLLMs' reasoning ability beyond passively imitating positive reasoning paths. To this end, we design Step-wise Group Relative Policy Optimization (StepGRPO), a new online reinforcement learning framework that enables MLLMs to self-improve reasoning ability via simple, effective and dense step-wise rewarding. Specifically, StepGRPO introduces two novel rule-based reasoning rewards: Step-wise Reasoning Accuracy Reward (StepRAR) and Step-wise Reasoning Validity Reward (StepRVR). StepRAR rewards the reasoning paths that contain necessary intermediate reasoning steps via a soft key-step matching technique, while StepRAR rewards reasoning paths that follow a well-structured and logically consistent reasoning process through a reasoning completeness and logic evaluation strategy. With the proposed StepGRPO, we introduce R1-VL, a series of MLLMs with outstanding capabilities in step-by-step reasoning. Extensive experiments over 8 benchmarks demonstrate the superiority of our methods.

[Arxiv](https://arxiv.org/abs/2503.12937)