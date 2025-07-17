# RiemannLoRA：统一黎曼框架实现无歧义LoRA优化

发布时间：2025年07月16日

`LLM理论` `人工智能` `模型优化`

> RiemannLoRA: A Unified Riemannian Framework for Ambiguity-Free LoRA Optimization

# 摘要

> 低秩适配（LoRA）已成为大型语言模型（LLMs）参数高效微调的标准，显著降低了内存和计算需求。然而，仍面临两大挑战：寻找最优初始化策略与缓解低秩矩阵分解中的过参数化问题。本研究提出了一种创新方法，能在统一框架内同时解决这两个挑战。我们方法将固定秩的LoRA矩阵视为光滑流形，将适配器视为流形元素，从而消除过参数化问题。沿着流形确定损失下降最快方向，提供初始化策略。我们特别注重数值稳定性和计算效率，采用数值线性代数和黎曼优化的最佳实践。实验结果表明，在LLM和扩散模型架构上，黎曼LoRA（RiemannLoRA）在收敛速度和最终性能上均优于标准LoRA及其最先进修改版本。

> Low-Rank Adaptation (LoRA) has become a widely adopted standard for parameter-efficient fine-tuning of large language models (LLMs), significantly reducing memory and computational demands. However, challenges remain, including finding optimal initialization strategies or mitigating overparametrization in low-rank matrix factorization. In this work, we propose a novel approach that addresses both of the challenges simultaneously within a unified framework. Our method treats a set of fixed-rank LoRA matrices as a smooth manifold. Considering adapters as elements on this manifold removes overparametrization, while determining the direction of the fastest loss decrease along the manifold provides initialization. Special care is taken to obtain numerically stable and computationally efficient implementation of our method, using best practices from numerical linear algebra and Riemannian optimization. Experimental results on LLM and diffusion model architectures demonstrate that RiemannLoRA consistently improves both convergence speed and final performance over standard LoRA and its state-of-the-art modifications.

[Arxiv](https://arxiv.org/abs/2507.12142)