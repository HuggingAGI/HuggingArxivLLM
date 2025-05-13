# 通过部分运行时重构实现服务质量高效的多个专家混合型大语言模型服务

发布时间：2025年05月09日

`LLM应用` `人工智能`

> QoS-Efficient Serving of Multiple Mixture-of-Expert LLMs Using Partial Runtime Reconfiguration

# 摘要

> 混合专家大型语言模型在多租户环境中的部署挑战与解决方案
混合专家（MoE）大型语言模型的部署因高内存需求而面临重大挑战。在多租户环境中，这些挑战尤为突出，因为共享资源需要支持多个模型，这限制了传统虚拟化技术的有效性。

本文探讨了如何在单GPU上高效服务多个微调后的MoE-LLM。我们提出了一种基于相似性专家整合的 serving 系统，通过跨模型共享相似专家来减少整体内存占用。为了保证输出质量，我们引入了运行时部分重新配置，动态替换处理不同模型请求时的非专家层。

因此，我们的方法在保持与单模型服务相当的吞吐量的同时，实现了具有竞争力的输出质量，并仅带来微小的首token响应时间（TTFT）增加。在配备单块NVIDIA A100 GPU（80GB）的服务器上使用Mixtral-8x7B模型进行的实验表明，与NVIDIA的多实例GPU（MIG）相比，平均周转时间减少了85%。此外，针对Google的Switch Transformer Base-8模型及其四种变体的实验展示了我们方法在保持输出质量方面的可扩展性和鲁棒性，相较于其他模型合并基线，凸显了其有效性。

> The deployment of mixture-of-experts (MoE) large language models (LLMs) presents significant challenges due to their high memory demands. These challenges become even more pronounced in multi-tenant environments, where shared resources must accommodate multiple models, limiting the effectiveness of conventional virtualization techniques. This paper addresses the problem of efficiently serving multiple fine-tuned MoE-LLMs on a single-GPU. We propose a serving system that employs \textit{similarity-based expert consolidation} to reduce the overall memory footprint by sharing similar experts across models. To ensure output quality, we introduce \textit{runtime partial reconfiguration}, dynamically replacing non-expert layers when processing requests from different models. As a result, our approach achieves a competitive output quality while maintaining throughput comparable to serving a single model while incurring a negligible increase in time-to-first-token (TTFT). Experiments on a server with a single NVIDIA A100 GPU (80GB) using Mixtral-8x7B models demonstrate an 85\% average reduction in turnaround time compared to NVIDIA's multi-instance GPU (MIG). Furthermore, experiments on Google's Switch Transformer Base-8 model with up to four variants demonstrate the scalability and resilience of our approach in maintaining output quality compared to other model merging baselines, highlighting its effectiveness.

[Arxiv](https://arxiv.org/abs/2505.06481)