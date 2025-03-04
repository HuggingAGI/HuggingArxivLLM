# 两难困境：在边缘计算系统中，联合LLM量化与分布式LLM推理的协同

发布时间：2025年03月03日

`LLM应用` `智能城市` `边缘计算`

> DILEMMA: Joint LLM Quantization and Distributed LLM Inference Over Edge Computing Systems

# 摘要

> 近年来，随着大型语言模型（LLMs）在智能城市中的广泛应用，如何在保持性能的同时将其部署到网络边缘成为一个重要课题。边缘计算（EC）作为一种更靠近用户的计算资源，能够有效降低为LLM依赖服务的最终用户任务的通信延迟。然而，EC服务器在通信、计算和存储能力方面存在局限性。本文提出了一种名为DILEMMA的创新框架，通过在EC系统中联合优化层放置和层量化，解决了在EC系统中部署LLMs所面临的挑战。DILEMMA利用层量化和知识蒸馏技术，制定了一种整数线性规划方法，旨在最小化总推理延迟，同时确保LLM性能达到可接受水平。实验结果表明，在OPT-350模型上使用SQuAD数据集进行评估时，DILEMMA实现了高达12.75%的量化率，同时保持了模型性能，充分证明了其在资源受限环境中的有效性。

> With a recent trend of using Large Language Models (LLMs) for different applications within smart cities, there is a need for pushing these models toward the edge of network while still preserving their performance. Edge Computing (EC) as a physically closer computing resource to the end users can help to reduce the communication delay for serving end users' tasks for LLM-dependent services. However, EC servers have limited capacity in terms of communication, computation, and storage capacity. This paper introduces DILEMMA, a novel framework addressing the challenges of deploying LLMs in EC systems by jointly optimizing layer placement and layer quantization in EC systems. DILEMMA formulates an Integer Linear Programming problem to minimize total inference delay while ensuring acceptable LLM performance levels, leveraging layer-wise quantization and knowledge distillation for LLM performance control. Experimental evaluations on OPT-350 model using the SQuAD dataset demonstrate that DILEMMA achieves a quantization ratio of up to 12.75% while preserving model loss, highlighting its effectiveness in resource-constrained environments.

[Arxiv](https://arxiv.org/abs/2503.01704)