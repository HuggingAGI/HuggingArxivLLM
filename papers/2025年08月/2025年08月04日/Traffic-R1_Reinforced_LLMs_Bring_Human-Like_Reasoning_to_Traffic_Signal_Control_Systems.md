# Traffic-R1：强化大型语言模型为交通信号控制系统注入类人推理能力

发布时间：2025年08月04日

`LLM应用` `交通管理` `城市交通优化`

> Traffic-R1: Reinforced LLMs Bring Human-Like Reasoning to Traffic Signal Control Systems

# 摘要

> # 摘要  
交通信号控制（TSC）对缓解交通拥堵和维持城市交通流动性至关重要。本文介绍了Traffic-R1，一个具备类人推理能力的TSC系统基础模型。该模型通过在模拟交通环境中结合专家指导，对强化大型语言模型（LLMs）进行自我探索和迭代开发而成。与传统强化学习（RL）和近期基于LLM的方法相比，Traffic-R1具有三大优势：  
1. 实现零样本泛化，通过内部交通控制策略和类人推理能力，无缝适应新道路网络和分布外事件。  
2. 30亿参数架构轻量化，支持移动级芯片实时推理，实现大规模边缘部署。  
3. 提供可解释的TSC过程，并通过自迭代和新型同步通信网络，促进多路口间有效沟通。  
大量基准测试显示，Traffic-R1达到新的先进水平，超越强大基线模型和训练密集型RL控制器。实际应用中，该模型每天为55,000名司机管理信号灯，平均缩短5%以上的排队时间，同时将操作员工作量减少一半。模型检查点可在https://huggingface.co/Season998/Traffic-R1获取。

> Traffic signal control (TSC) is vital for mitigating congestion and sustaining urban mobility. In this paper, we introduce Traffic-R1, a foundation model with human-like reasoning for TSC systems. Our model is developed through self-exploration and iteration of reinforced large language models (LLMs) with expert guidance in a simulated traffic environment. Compared to traditional reinforcement learning (RL) and recent LLM-based methods, Traffic-R1 offers three significant advantages. First, Traffic-R1 delivers zero-shot generalisation, transferring unchanged to new road networks and out-of-distribution incidents by utilizing its internal traffic control policies and human-like reasoning. Second, its 3B-parameter architecture is lightweight enough for real-time inference on mobile-class chips, enabling large-scale edge deployment. Third, Traffic-R1 provides an explainable TSC process and facilitates multi-intersection communication through its self-iteration and a new synchronous communication network. Extensive benchmarks demonstrate that Traffic-R1 sets a new state of the art, outperforming strong baselines and training-intensive RL controllers. In practice, the model now manages signals for more than 55,000 drivers daily, shortening average queues by over 5% and halving operator workload. Our checkpoint is available at https://huggingface.co/Season998/Traffic-R1.

[Arxiv](https://arxiv.org/abs/2508.02344)