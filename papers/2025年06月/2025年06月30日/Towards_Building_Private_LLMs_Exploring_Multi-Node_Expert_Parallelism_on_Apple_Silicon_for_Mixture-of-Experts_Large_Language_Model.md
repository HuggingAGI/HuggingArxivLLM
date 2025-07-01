# # 摘要  
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月30日

`LLM应用

摘要讨论了在私有环境中高效部署大型语言模型的技术优化和成本效益分析，属于应用层面的优化，因此归类为LLM应用。` `人工智能` `智能服务`

> Towards Building Private LLMs: Exploring Multi-Node Expert Parallelism on Apple Silicon for Mixture-of-Experts Large Language Model

# 摘要

> 大型语言模型（LLMs）凭借 OpenAI 的 ChatGPT、Meta 的 Llama 以及 Databricks 的 DBRX 等显著的技术进步，彻底改变了人工智能领域。本文针对苹果智能在构建个人或小群体服务的私有 LLM 系统时所遇到的成本和扩展性挑战进行了深入探讨。我们提出了一种经济高效的解决方案——配备苹果 M2 Ultra 芯片的 Mac Studio 集群，用于托管和加速具有专家混合（MoE）架构的预训练 DBRX 模型。通过性能分析，我们发现将模型的专家在两到四个机器节点间进行并行执行，能够显著减少推理时间。值得注意的是，专家的计算时间与交换输出的通信时间相当，这表明网络延迟相较于带宽更为关键。此外，我们观察到由于苹果软件堆栈的内存管理逻辑导致了显著的管理开销。基于这些发现，我们开发了优化方案以消除内存管理开销。最终，Mac Studio 集群的成本效益比配备 NVIDIA H100 GPU 的最新 AI 超算高出 1.15 倍。此外，我们构建了一个性能模型，用于在不同配置下估算系统性能，该模型为设计私有 LLM 系统提供了宝贵的见解。

> Large Language Models (LLMs) have revolutionized Artificial Intelligence (AI) with significant advancements such as OpenAI's ChatGPT, Meta's Llama, and Databricks' DBRX. This paper addresses the cost and scalability challenges encountered when constructing private LLM systems for personal or small group services, as aimed by Apple Intelligence. A Mac Studio cluster with Apple's M2 Ultra chips is established as a cost-efficient solution to host and accelerate the pretrained DBRX model with the Mixture-of-Experts (MoE) architecture. Our performance analysis reveal that parallel execution of the model's experts across two to four machine nodes significantly reduces inference time. We find that computation time for the experts is comparable to the communication time for exchanging their outputs, emphasizing the importance of network latency over bandwidth. We also observe significant management overhead due to Apple software stack's memory management logic. Based on these findings, we develop optimization schemes to eliminate the memory management overhead. As a result, the Mac Studio cluster is 1.15 times more cost-efficient than the state-of-the-art AI supercomputer with NVIDIA H100 GPUs. In addition, we construct a performance model to estimate system performance under varying configurations, and the model provides valuable insights for designing private LLM systems.

[Arxiv](https://arxiv.org/abs/2506.23635)