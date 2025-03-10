# Dilu：基于内省弹性机制，实现 GPU 资源按需供给，助力无服务器深度学习服务

发布时间：2025年03月06日

`其他` `云计算`

> Dilu: Enabling GPU Resourcing-on-Demand for Serverless DL Serving via Introspective Elasticity

# 摘要

> 无服务器计算因其易于管理、自动扩展和高成本效益的特点，在深度学习（DL）应用中深受欢迎，成为DL应用的首选方案。特别是针对大型语言模型的DL任务，需要大量GPU资源来保障服务质量（QoS）。然而，由于任务的动态特性和粗粒度静态GPU分配机制的共同作用，极易引发GPU碎片化问题（如15%-94%的GPU碎片率），这逐渐削弱了无服务器弹性带来的优势。

    与传统仅支持水平扩展的无服务器系统不同，我们提出了内省弹性（IE），这是一种细粒度且自适应的二维协同扩展机制，旨在为无服务器DL任务提供灵活的GPU资源支持。基于这一创新，我们打造了Dilu，一个支持IE的跨层GPU无服务器DL系统。首先，Dilu为DL任务提供多维度分析能力，并结合高效的剪枝搜索方法。其次，Dilu在资源调度中遵循互补原则，确保在保障QoS的同时提升GPU利用率。最后，Dilu采用自适应的二维协同扩展方法，实时优化GPU资源的弹性供应。实验结果表明，与现有最优基线相比，Dilu能够实现动态资源调整，展现出更低的GPU碎片化（10%-46%的去碎片化效果）、更高的吞吐量（推理吞吐量提升1.8倍，训练吞吐量提升1.1倍）以及更优质的服务质量（违反率减少11%-71%）。

> Serverless computing, with its ease of management, auto-scaling, and cost-effectiveness, is widely adopted by deep learning (DL) applications. DL workloads, especially with large language models, require substantial GPU resources to ensure QoS. However, it is prone to produce GPU fragments (e.g., 15\%-94\%) in serverless DL systems due to the dynamicity of workloads and coarse-grained static GPU allocation mechanisms, gradually eroding the profits offered by serverless elasticity.
  Different from classical serverless systems that only scale horizontally, we present introspective elasticity (IE), a fine-grained and adaptive two-dimensional co-scaling mechanism to support GPU resourcing-on-demand for serverless DL tasks. Based on this insight, we build Dilu, a cross-layer and GPU-based serverless DL system with IE support. First, Dilu provides multi-factor profiling for DL tasks with efficient pruning search methods. Second, Dilu adheres to the resourcing-complementary principles in scheduling to improve GPU utilization with QoS guarantees. Third, Dilu adopts an adaptive 2D co-scaling method to enhance the elasticity of GPU provisioning in real time. Evaluations show that it can dynamically adjust the resourcing of various DL functions with low GPU fragmentation (10\%-46\% GPU defragmentation), high throughput (up to 1.8$\times$ inference and 1.1$\times$ training throughput increment) and QoS guarantees (11\%-71\% violation rate reduction), compared to the SOTA baselines.

[Arxiv](https://arxiv.org/abs/2503.05130)