# DSSD: 高效边缘设备部署方案与协同推理

发布时间：2025年07月16日

`LLM应用

论文摘要讨论了大型语言模型在资源受限和通信开销较高的设备-边缘系统中的部署挑战，并提出了一种协作框架和创新架构来优化系统效率。这属于LLM的实际应用和优化，因此归类为LLM应用。` `边缘计算` `分布式计算`

> DSSD: Efficient Edge-Device Deployment and Collaborative Inference via Distributed Split Speculative Decoding

# 摘要

> 大型语言模型 (LLMs) 已经彻底改变了自然语言处理领域，但在资源受限和通信开销较高的设备-边缘系统中部署时，面临着重大挑战。针对这些问题，我们提出了一种协作框架，通过结合设备端的小型语言模型 (SLMs) 和边缘端的大型语言模型 (LLMs)，并引入投机性解码 (SD) 技术，显著提升了系统效率。然而，现有解决方案往往在推理精度与延迟之间做出妥协，或者在验证候选标记时产生高昂的上行传输成本。本文提出了一种名为分布式分割投机性解码 (DSSD) 的创新架构，该架构不仅延续了 SLM-LLM 的分工模式，还将验证阶段巧妙地分配到设备和边缘端。通过这种方式，DSSD 以单一的下行传输取代了多个词汇分布的上行传输，大幅降低了通信延迟，同时保持了推理质量。实验结果表明，我们的解决方案在性能上优于现有方法，相关代码已开源，地址为：https://github.com/JasonNing96/DSSD-Efficient-Edge-Computing。


> Large language models (LLMs) have transformed natural language processing but face critical deployment challenges in device-edge systems due to resource limitations and communication overhead. To address these issues, collaborative frameworks have emerged that combine small language models (SLMs) on devices with LLMs at the edge, using speculative decoding (SD) to improve efficiency. However, existing solutions often trade inference accuracy for latency or suffer from high uplink transmission costs when verifying candidate tokens. In this paper, we propose Distributed Split Speculative Decoding (DSSD), a novel architecture that not only preserves the SLM-LLM split but also partitions the verification phase between the device and edge. In this way, DSSD replaces the uplink transmission of multiple vocabulary distributions with a single downlink transmission, significantly reducing communication latency while maintaining inference quality. Experiments show that our solution outperforms current methods, and codes are at: https://github.com/JasonNing96/DSSD-Efficient-Edge-Computing

[Arxiv](https://arxiv.org/abs/2507.12000)