# SecFwT: 高效隐私保护的大型语言模型微调方法——仅前向传递

发布时间：2025年06月18日

`LLM理论`

> SecFwT: Efficient Privacy-Preserving Fine-Tuning of Large Language Models Using Forward-Only Passes

# 摘要

> 大型语言模型（LLMs）正在改变世界，但在医疗和金融等隐私敏感领域，严格的隐私要求导致可用数据匮乏，限制了其在专业任务中的应用。基于安全多方计算（MPC）的隐私保护机器学习虽然能在保护模型参数和用户数据的同时提供强大功能，但目前主要局限于LLMs的推理阶段。微调过程中的隐私保护反向传播和优化器操作带来了巨大的计算挑战。

本文指出，基于MPC的隐私保护LLMs微调面临两大核心难题：（1）反向传播和优化器过程的高昂计算成本；（2）MPC环境下softmax注意力机制效率低下。为了解决这些难题，我们提出了SecFwT——首个专为高效、隐私保护的LLMs微调设计的基于MPC的框架。

SecFwT采用创新的仅前向微调范式，完全消除反向传播和优化器计算，并通过MPC友好的随机特征注意力机制替代传统的softmax注意力，大幅减少非线性运算和计算复杂度。实验结果表明，SecFwT在效率和隐私保护方面实现了突破性提升，使LLMs能够实现可扩展、安全可靠的微调，为隐私关键型应用提供了强大支持。

> Large language models (LLMs) have transformed numerous fields, yet their adaptation to specialized tasks in privacy-sensitive domains, such as healthcare and finance, is constrained by the scarcity of accessible training data due to stringent privacy requirements. Secure multi-party computation (MPC)-based privacy-preserving machine learning offers a powerful approach to protect both model parameters and user data, but its application to LLMs has been largely limited to inference, as fine-tuning introduces significant computational challenges, particularly in privacy-preserving backward propagation and optimizer operations. This paper identifies two primary obstacles to MPC-based privacy-preserving fine-tuning of LLMs: (1) the substantial computational overhead of backward and optimizer processes, and (2) the inefficiency of softmax-based attention mechanisms in MPC settings. To address these challenges, we propose SecFwT, the first MPC-based framework designed for efficient, privacy-preserving LLM fine-tuning. SecFwT introduces a forward-only tuning paradigm to eliminate backward and optimizer computations and employs MPC-friendly Random Feature Attention to approximate softmax attention, significantly reducing costly non-linear operations and computational complexity. Experimental results demonstrate that SecFwT delivers substantial improvements in efficiency and privacy preservation, enabling scalable and secure fine-tuning of LLMs for privacy-critical applications.

[Arxiv](https://arxiv.org/abs/2506.15307)