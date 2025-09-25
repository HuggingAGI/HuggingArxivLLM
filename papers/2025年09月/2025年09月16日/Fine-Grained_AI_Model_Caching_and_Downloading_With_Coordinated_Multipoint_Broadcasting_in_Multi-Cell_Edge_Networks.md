# 多小区边缘网络中基于协作多点广播的细粒度AI模型缓存与下载

发布时间：2025年09月16日

`Agent` `基础理论`

> Fine-Grained AI Model Caching and Downloading With Coordinated Multipoint Broadcasting in Multi-Cell Edge Networks

# 摘要

> 6G网络有望支持按需AI模型下载，以满足终端用户多样化的推理需求。通过在边缘节点主动缓存模型，用户能够低延迟获取所需模型，实现设备端AI推理。然而，当代AI模型体量庞大，在存储容量有限的情况下，给边缘缓存以及无线信道上异构模型的并发传输带来了巨大挑战。为应对这些挑战，我们提出一种细粒度AI模型缓存与下载系统，该系统利用参数可重用性——这一特性源于从共享预训练模型（参数冻结）微调特定任务模型的常见做法。该系统在边缘节点选择性缓存模型参数块（PBs），从而消除不同缓存模型间可重用参数的冗余存储。此外，系统还融入协作多点（CoMP）广播技术，可同时向多个用户传输可重用PBs，进而提升下行频谱利用率。在此架构下，我们构建模型下载延迟最小化问题，对PB缓存、迁移（边缘节点间）及广播波束成形进行联合优化。为解决这一难题，我们开发了分布式多智能体学习框架，该框架能让边缘节点明确学习彼此行动间的相互影响，从而促进协作。此外，我们还提出数据增强方法，通过预测模型自适应生成合成训练样本，以提高样本效率并加速策略学习。理论分析与仿真实验均验证了所提学习框架的优异收敛性能。

> 6G networks are envisioned to support on-demand AI model downloading to accommodate diverse inference requirements of end users. By proactively caching models at edge nodes, users can retrieve the requested models with low latency for on-device AI inference. However, the substantial size of contemporary AI models poses significant challenges for edge caching under limited storage capacity, as well as for the concurrent delivery of heterogeneous models over wireless channels. To address these challenges, we propose a fine-grained AI model caching and downloading system that exploits parameter reusability, stemming from the common practice of fine-tuning task-specific models from a shared pre-trained model with frozen parameters. This system selectively caches model parameter blocks (PBs) at edge nodes, eliminating redundant storage of reusable parameters across different cached models. Additionally, it incorporates coordinated multipoint (CoMP) broadcasting to simultaneously deliver reusable PBs to multiple users, thereby enhancing downlink spectrum utilization. Under this arrangement, we formulate a model downloading delay minimization problem to jointly optimize PB caching, migration (among edge nodes), and broadcasting beamforming. To tackle this intractable problem, we develop a distributed multi-agent learning framework that enables edge nodes to explicitly learn mutual influence among their actions, thereby facilitating cooperation. Furthermore, a data augmentation approach is proposed to adaptively generate synthetic training samples through a predictive model, boosting sample efficiency and accelerating policy learning. Both theoretical analysis and simulation experiments validate the superior convergence performance of the proposed learning framework.

[Arxiv](https://arxiv.org/abs/2509.19341)