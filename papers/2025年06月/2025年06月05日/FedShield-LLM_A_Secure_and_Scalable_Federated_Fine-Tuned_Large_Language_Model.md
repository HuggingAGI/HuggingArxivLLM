# FedShield-LLM：一个安全且可扩展的联邦微调大型语言模型

发布时间：2025年06月05日

`LLM应用` `联邦学习` `隐私保护`

> FedShield-LLM: A Secure and Scalable Federated Fine-Tuned Large Language Model

# 摘要

> 联邦学习 (FL) 提供了一种去中心化的框架，通过利用组织间的计算资源，对大型语言模型 (LLMs) 进行训练和微调，同时将敏感数据保留在本地设备上。它在解决隐私和安全问题的同时，有效应对了 LLMs 大规模计算需求带来的挑战，这对小型和中型组织来说可能难以承受。FL 通过微调支持跨领域应用的任务特定 LLMs 的开发，但仍然容易受到推理攻击（如成员推断和梯度反转）的威胁，这些攻击会危及数据隐私。先前的研究在 LLM 微调中应用了差分隐私 (DP)，尽管这种方法在保护隐私方面有效，却可能损害模型性能。为了解决这些挑战，我们提出了一种新颖的方法 FedShield-LLM，该方法结合剪枝和全同态加密 (FHE) 技术对低秩适应 (LoRA) 参数进行处理，从而在加密模型更新上实现安全计算，同时通过停用不重要的 LoRA 参数来降低攻击面。此外，针对跨领域环境优化的联邦算法提升了扩展性和效率。参数高效的微调技术如 LoRA 大幅降低了计算和通信的开销，使 FL 对资源受限的客户端成为可行的选择。实验结果表明，所提出的方法在保持强大的隐私保护的同时，优于现有方法，使组织能够协作训练安全且高效的 LLMs。
  代码和数据可在 https://github.com/solidlabnetwork/fedshield-llm 获取

> Federated Learning (FL) offers a decentralized framework for training and fine-tuning Large Language Models (LLMs) by leveraging computational resources across organizations while keeping sensitive data on local devices. It addresses privacy and security concerns while navigating challenges associated with the substantial computational demands of LLMs, which can be prohibitive for small and medium-sized organizations. FL supports the development of task-specific LLMs for cross-silo applications through fine-tuning but remains vulnerable to inference attacks, such as membership inference and gradient inversion, which threaten data privacy. Prior studies have utilized Differential Privacy (DP) in LLM fine-tuning, which, despite being effective at preserving privacy, can degrade model performance. To overcome these challenges, we propose a novel method, FedShield-LLM, that uses pruning with Fully Homomorphic Encryption (FHE) for Low-Rank Adaptation (LoRA) parameters, enabling secure computations on encrypted model updates while mitigating the attack surface by deactivating less important LoRA parameters. Furthermore, optimized federated algorithms for cross-silo environments enhance scalability and efficiency. Parameter-efficient fine-tuning techniques like LoRA substantially reduce computational and communication overhead, making FL feasible for resource-constrained clients. Experimental results show that the proposed method outperforms existing methods while maintaining robust privacy protection, enabling organizations to collaboratively train secure and efficient LLMs.
  The code and data are available at, https://github.com/solidlabnetwork/fedshield-llm

[Arxiv](https://arxiv.org/abs/2506.05640)