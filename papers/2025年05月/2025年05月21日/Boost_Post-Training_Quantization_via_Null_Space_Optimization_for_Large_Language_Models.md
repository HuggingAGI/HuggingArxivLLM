# 提升大型语言模型的后训练量化效果，通过零空间优化实现性能增强。

发布时间：2025年05月21日

`LLM应用` `机器学习`

> Boost Post-Training Quantization via Null Space Optimization for Large Language Models

# 摘要

> 现有的LLMs后训练量化方法虽然成功，但性能提升的边际收益递减表明现有策略难以支持更高效的模型压缩。为启发未来研究，我们首次将空域概念引入LLMs量化，提出了一种名为Q2N的即插即用空域投影模块。通过将量化后权重扰动限制在输入激活的空域内，我们有效缓解了量化误差。具体而言，我们设计了一种专门针对LLMs特性的高效精确空域投影近似方法，并推导出满足实际推理条件的闭合形式等效向量解，避免额外内存开销。在LLaMA3、DeepSeek、Qwen3等先进LLMs和基线上的大量实验证明了Q2N方法和空域优化视角的有效性。这是基于空域见解缓解量化误差的第一步，希望为未来设计更先进的量化方法提供启发。代码已开源：https://github.com/zjq0455/q2n。

> Existing post-training quantization methods for large language models (LLMs) offer remarkable success. However, the increasingly marginal performance gains suggest that existing quantization strategies are insufficient to support the development of more compressed models. To inspire new directions for future research, this paper introduces the concept of null space into LLMs quantization. We argue that the quantization error can be effectively alleviated by constraining the post-quantization weight perturbation to lie within the null space of input activations. To prove this idea, we propose a plug-and-play null space projection module for existing milestone PTQ baselines named Q2N. Specifically, we first design an efficient and accurate null space projection approximation method tailored to the characteristics of LLMs. Subsequently, we theoretically derive a closed-form solution for an equivalent vector of the obtained projection matrix, which satisfies practical inference condition while avoiding additional memory overhead. Extensive experiments are conducted on various state-of-the-art LLMs (LLaMA3, DeepSeek, Qwen3) and baselines, demonstrating the effectiveness of both our Q2N and the perspective of null space optimization for LLMs quantization. We view this paper the first step to further alleviate the quantization error based on the insights of null space, hoping it inspiring future researchers to design more advanced quantization methods. Codes are available at https://github.com/zjq0455/q2n.

[Arxiv](https://arxiv.org/abs/2506.11044)