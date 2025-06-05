# 利用可迁移稀疏性缓解零阶联邦LLM微调中的非独立同分布漂移问题

发布时间：2025年06月03日

`模型训练与优化` `联邦学习`

> Mitigating Non-IID Drift in Zeroth-Order Federated LLM Fine-Tuning with Transferable Sparsity

# 摘要

> 联邦学习（Federated Learning）能够在去中心化的非独立同分布（Non-IID）客户端之间协作微调大型语言模型（LLMs），但此类模型的庞大参数规模带来了显著的内存和通信挑战。本研究提出了Meerkat，一种专为联邦LLM微调设计的稀疏零阶优化（ZO）方法。通过将微调限制在可转移的、静态的、极度稀疏的参数子集上，Meerkat实现了卓越的通信效率，支持成本效益高的高频同步。通过理论分析和实验，我们证明高频通信有效缓解了Non-IID数据带来的挑战，并优于全参数ZO方法。此外，实验结果表明，在相同通信频率下，Meerkat的表现优于现有稀疏基准方法。为了进一步应对Non-IID漂移，Meerkat利用可追溯的本地更新并为每个客户端构建虚拟路径。这种虚拟路径机制揭示了GradIP现象：LLM预训练梯度（由服务器维护）与通过ZO估计的客户端梯度之间的内积，在极端Non-IID客户端中趋于收敛，而在IID客户端中则呈现振荡。这种独特行为为识别数据异质性极强的客户端提供了信号。基于此信号，提出了Meerkat-vp，通过分析GradIP轨迹识别极端Non-IID客户端，并应用早期停止机制提升聚合模型质量。实验验证表明，Meerkat和Meerkat-vp显著提升了ZO联邦LLM微调的效率和效果。

> Federated Learning enables collaborative fine-tuning of Large Language Models (LLMs) across decentralized Non-Independent and Identically Distributed (Non-IID) clients, but such models' massive parameter sizes lead to significant memory and communication challenges. This work introduces Meerkat, a sparse zeroth-order optimization (ZO) method designed for federated LLM fine-tuning. By limiting fine-tuning to a transferable, static, extremely sparse subset of parameters, Meerkat achieves remarkable communication efficiency, enabling cost-effective high-frequency synchronization. With theoretical analysis and experiments, we show that this high-frequency communication effectively mitigates Non-IID data challenges and leads to superior performance compared to full-parameter ZO. Furthermore, experiment results show that Meerkat outperforms existing sparsity baselines with better performance at the same communication frequency. To further handle Non-IID drift, Meerkat leverages traceable local updates and forms a virtual path for each client. This virtual path mechanism reveals the GradIP phenomenon: the inner products between LLM pre-training gradients maintained by server and client gradients estimated via ZO converges for extreme Non-IID clients but oscillates for IID ones. This distinct behavior provides a signal for identifying clients with extreme data heterogeneity. Using this signal, Meerkat-vp is proposed to analyze GradIP trajectories to identify extreme Non-IID clients and applies early stopping to enhance aggregated model quality. Experiments confirm that Meerkat and Meerkat-vp significantly improve the efficiency and effectiveness of ZO federated LLM fine-tuning.

[Arxiv](https://arxiv.org/abs/2506.03337)