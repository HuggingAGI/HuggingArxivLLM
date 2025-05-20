# 支离破碎的思维链推理

发布时间：2025年05月19日

`LLM应用

理由：论文探讨了在推理阶段通过优化策略（如截断CoT和Fractured Sampling）来提升大型语言模型的性能和效率，属于应用层面的改进。` `对话系统`

> Fractured Chain-of-Thought Reasoning

# 摘要

> 推理时的扩展技术通过在推理过程中投入额外的计算资源，而无需重新训练模型，显著增强了大型语言模型（LLMs）的推理能力。Chain-of-Thought（CoT）提示及其扩展Long CoT通过生成丰富的中间推理轨迹来提高准确性，但这些方法会带来巨大的令牌成本，阻碍了它们在对延迟敏感的场景中的部署。在本研究中，我们发现，截断的CoT（在推理完成前停止并直接生成最终答案）通常与完整的CoT采样相匹配，同时使用了大幅减少的令牌数量。基于这一发现，我们提出了Fractured Sampling，这是一种统一的推理时策略，通过三个正交轴在完整的CoT和仅解决方案采样之间进行插值：（1）推理轨迹的数量，（2）每条轨迹的最终解决方案数量，以及（3）推理轨迹被截断的深度。通过在五个多样化的推理基准测试和多个模型规模上的广泛实验，我们证明Fractured Sampling始终实现了更优的准确性和成本之间的平衡，使得Pass@k相对于令牌预算的对数线性缩放收益显著提升。我们的分析揭示了如何在这些维度上分配计算资源以实现最佳性能，为更高效和可扩展的LLM推理铺平了道路。

> Inference-time scaling techniques have significantly bolstered the reasoning capabilities of large language models (LLMs) by harnessing additional computational effort at inference without retraining. Similarly, Chain-of-Thought (CoT) prompting and its extension, Long CoT, improve accuracy by generating rich intermediate reasoning trajectories, but these approaches incur substantial token costs that impede their deployment in latency-sensitive settings. In this work, we first show that truncated CoT, which stops reasoning before completion and directly generates the final answer, often matches full CoT sampling while using dramatically fewer tokens. Building on this insight, we introduce Fractured Sampling, a unified inference-time strategy that interpolates between full CoT and solution-only sampling along three orthogonal axes: (1) the number of reasoning trajectories, (2) the number of final solutions per trajectory, and (3) the depth at which reasoning traces are truncated. Through extensive experiments on five diverse reasoning benchmarks and several model scales, we demonstrate that Fractured Sampling consistently achieves superior accuracy-cost trade-offs, yielding steep log-linear scaling gains in Pass@k versus token budget. Our analysis reveals how to allocate computation across these dimensions to maximize performance, paving the way for more efficient and scalable LLM reasoning.

[Arxiv](https://arxiv.org/abs/2505.12992)