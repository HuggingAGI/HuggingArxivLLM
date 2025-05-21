# 基于LLM的AVSR扩展与优化：稀疏投影器混合方法

发布时间：2025年05月20日

`LLM应用` `语音识别` `多模态`

> Scaling and Enhancing LLM-based AVSR: A Sparse Mixture of Projectors Approach

# 摘要

> 音频-视觉语音识别（AVSR）通过融合视觉信息提升了在噪声环境中的识别鲁棒性。尽管近期研究将大型语言模型（LLMs）引入AVSR领域，但其高计算成本却限制了在资源受限场景中的实际应用。为解决这一难题，我们提出了一种高效多模态LLM——Llama-SMoP，该模型采用稀疏门控专家混合投影器（SMoP）模块，在不增加推理成本的前提下实现了模型容量的扩展。通过引入稀疏门控的专家混合投影器，Llama-SMoP不仅性能强劲，还能有效降低模型规模。我们深入探讨了三种SMoP配置方案，并发现采用模态专用路由器和专家的Llama-SMoP DEDR在ASR、VSR和AVSR任务中表现尤为突出。进一步的消融研究表明，该方法在专家激活效率、模型扩展性和噪声鲁棒性方面均表现出色.

> Audio-Visual Speech Recognition (AVSR) enhances robustness in noisy environments by integrating visual cues. While recent advances integrate Large Language Models (LLMs) into AVSR, their high computational cost hinders deployment in resource-constrained settings. To address this, we propose Llama-SMoP, an efficient Multimodal LLM that employs a Sparse Mixture of Projectors (SMoP) module to scale model capacity without increasing inference costs. By incorporating sparsely-gated mixture-of-experts (MoE) projectors, Llama-SMoP enables the use of smaller LLMs while maintaining strong performance. We explore three SMoP configurations and show that Llama-SMoP DEDR (Disjoint-Experts, Disjoint-Routers), which uses modality-specific routers and experts, achieves superior performance on ASR, VSR, and AVSR tasks. Ablation studies confirm its effectiveness in expert activation, scalability, and noise robustness.

[Arxiv](https://arxiv.org/abs/2505.14336)