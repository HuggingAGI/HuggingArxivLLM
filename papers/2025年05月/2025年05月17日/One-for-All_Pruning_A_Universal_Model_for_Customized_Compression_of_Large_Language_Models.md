# One-for-All 剪枝：适用于大型语言模型的定制化压缩通用模型

发布时间：2025年05月17日

`LLM理论` `模型压缩` `模型优化`

> One-for-All Pruning: A Universal Model for Customized Compression of Large Language Models

# 摘要

> 现有的大型语言模型（LLMs）剪枝方法主要集中在实现高压缩率的同时保持模型性能。尽管这些方法在处理单个用户的压缩请求时表现优异，但面对多个同时请求的场景时效率低下。为了解决这一问题，我们提出了一种面向定制化压缩的通用模型 UniCuCo，该模型引入了一种策略网络 StratNet，能够学习将任意请求映射到其最优剪枝策略。训练 StratNet 的主要挑战在于评估剪枝策略的高计算成本以及剪枝过程的不可微特性，这阻碍了对 StratNet 的梯度反向传播更新。为克服这些挑战，我们采用高斯过程来近似评估过程。由于高斯过程的梯度是可计算的，我们可以利用它来近似不可微剪枝过程的梯度，从而实现 StratNet 的更新。实验结果表明，与基线方法相比，UniCuCo 在处理 64 个请求时速度提高了 28 倍，同时保持了与基线相当的准确性。

> Existing pruning methods for large language models (LLMs) focus on achieving high compression rates while maintaining model performance. Although these methods have demonstrated satisfactory performance in handling a single user's compression request, their processing time increases linearly with the number of requests, making them inefficient for real-world scenarios with multiple simultaneous requests. To address this limitation, we propose a Univeral Model for Customized Compression (UniCuCo) for LLMs, which introduces a StratNet that learns to map arbitrary requests to their optimal pruning strategy. The challenge in training StratNet lies in the high computational cost of evaluating pruning strategies and the non-differentiable nature of the pruning process, which hinders gradient backpropagation for StratNet updates. To overcome these challenges, we leverage a Gaussian process to approximate the evaluation process. Since the gradient of the Gaussian process is computable, we can use it to approximate the gradient of the non-differentiable pruning process, thereby enabling StratNet updates. Experimental results show that UniCuCo is 28 times faster than baselines in processing 64 requests, while maintaining comparable accuracy to baselines.

[Arxiv](https://arxiv.org/abs/2505.12216)