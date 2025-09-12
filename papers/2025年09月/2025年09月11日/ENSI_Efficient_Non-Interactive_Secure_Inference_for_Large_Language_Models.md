# ENSI：面向大型语言模型的高效非交互式安全推理

发布时间：2025年09月11日

`LLM应用` `基础理论`

> ENSI: Efficient Non-Interactive Secure Inference for Large Language Models

# 摘要

> 安全推理借助加密协议实现隐私保护机器学习，这类协议支持对敏感用户数据进行计算而不泄露数据。然而，将加密协议与大型语言模型（LLMs）集成面临诸多挑战：协议本身的固有复杂性，叠加LLMs庞大的参数规模和复杂架构，严重制约了其实用性。为此，本研究提出ENSI——一种新型非交互式LLM安全推理框架，其核心在于加密协议与LLM架构的协同设计。ENSI采用优化编码策略，将CKKS方案与轻量级LLM变体BitNet无缝融合，大幅降低了加密矩阵乘法的计算复杂度。针对同态加密下softmax计算成本过高的问题，研究团队创新性地将sigmoid注意力机制与HE集成，作为无需重新训练的无缝替代方案。此外，通过将Bootstrapping操作嵌入RMSNorm过程，ENSI能高效刷新密文，同时将昂贵的Bootstrapping调用频率显著降至1%。实验结果显示，与现有最优方法相比，ENSI在CPU上的矩阵乘法速度提升约8倍，softmax推理速度提升2.6倍，且Bootstrapping操作占比仅为1%。

> Secure inference enables privacy-preserving machine learning by leveraging cryptographic protocols that support computations on sensitive user data without exposing it. However, integrating cryptographic protocols with large language models (LLMs) presents significant challenges, as the inherent complexity of these protocols, together with LLMs' massive parameter scale and sophisticated architectures, severely limits practical usability. In this work, we propose ENSI, a novel non-interactive secure inference framework for LLMs, based on the principle of co-designing the cryptographic protocols and LLM architecture. ENSI employs an optimized encoding strategy that seamlessly integrates CKKS scheme with a lightweight LLM variant, BitNet, significantly reducing the computational complexity of encrypted matrix multiplications. In response to the prohibitive computational demands of softmax under homomorphic encryption (HE), we pioneer the integration of the sigmoid attention mechanism with HE as a seamless, retraining-free alternative. Furthermore, by embedding the Bootstrapping operation within the RMSNorm process, we efficiently refresh ciphertexts while markedly decreasing the frequency of costly bootstrapping invocations. Experimental evaluations demonstrate that ENSI achieves approximately an 8x acceleration in matrix multiplications and a 2.6x speedup in softmax inference on CPU compared to state-of-the-art method, with the proportion of bootstrapping is reduced to just 1%.

[Arxiv](https://arxiv.org/abs/2509.09424)