# 协调Hessian信息加速与仅标量通信，实现高效联邦零阶微调

发布时间：2025年06月02日

`LLM理论` `人工智能`

> Reconciling Hessian-Informed Acceleration and Scalar-Only Communication for Efficient Federated Zeroth-Order Fine-Tuning

# 摘要

> 近期，联邦学习（FL）领域出现了一种无维度通信框架（如DeComFL），通过仅传输标量信息并采用零阶随机梯度下降（ZO-SGD），大幅减少了每轮通信的开销。这一方法在大型语言模型（LLMs）的联邦微调中具有显著优势。然而，零阶梯度估计的高方差通常会导致收敛速度缓慢。尽管已知利用Hessian信息可以提升优化速度，但将其整合到FL中面临诸多挑战，包括客户端对本地数据的限制以及保持无维度通信这一关键特性的重要性。为克服这一限制，我们首先提出了一种仅标量通信的联邦学习框架，该框架将无维度通信与标准ZO-SGD解耦，从而为集成更先进的优化策略铺平了道路。在此框架基础上，我们提出了HiSo，一种基于Hessian信息的零阶优化与仅标量通信的快速联邦微调方法。具体而言，HiSo通过利用全局曲率信息加速收敛，同时保持每轮通信的最小成本。从理论上，我们建立了与全局Lipschitz常数无关的收敛保证，并进一步证明，当全局Hessian表现出低有效秩时——这在LLMs中是一个常见现象——HiSo能够实现更快的收敛速率。实验结果表明，HiSo在基准数据集和LLM微调任务中均显著超越现有的基于ZO的FL方法，在收敛速度和通信效率方面表现尤为突出。

> Recent dimension-free communication frameworks in Federated Learning (FL), such as DeComFL, significantly reduce per-round communication by transmitting only scalars via zeroth-order stochastic gradient descent (ZO-SGD). This method is particularly advantageous for federated fine-tuning of Large Language Models (LLMs). Yet, the high variance in ZO gradient estimation typically leads to slow convergence. Although leveraging Hessian information is known to enhance optimization speed, integrating this into FL presents significant challenges. These include clients' restrictions on local data and the critical need to maintain the dimension-free communication property. To overcome this limitation, we first introduce a generalized scalar-only communication FL framework that decouples dimension-free communication from standard ZO-SGD, enabling the integration of more advanced optimization strategies. Building on this framework, we propose HiSo, a fast federated fine-tuning method via Hessian-informed zeroth-order optimization and Scalar-only communication. Specifically, it leverages global curvature information to accelerate convergence while preserving the same minimal communication cost per round. Theoretically, we establish convergence guarantees that are independent of the global Lipschitz constant, and further show that HiSo achieves faster rates when the global Hessian exhibits a low effective rank -- a common phenomenon in LLMs. Extensive experiments on benchmark datasets and LLM fine-tuning tasks confirm that HiSo significantly outperforms existing ZO-based FL methods in both convergence speed and communication efficiency.

[Arxiv](https://arxiv.org/abs/2506.02370)