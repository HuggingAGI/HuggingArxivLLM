# TOPLOC: 无信任可验证推理的局部敏感哈希方案

发布时间：2025年01月27日

`LLM应用

**理由**：这篇论文主要讨论了如何通过TOPLOC方法来验证大型语言模型（LLMs）的推理过程，确保模型配置的透明性和可信度。这属于LLM在实际应用中的技术改进和优化，因此归类为LLM应用。` `人工智能` `区块链`

> TOPLOC: A Locality Sensitive Hashing Scheme for Trustless Verifiable Inference

# 摘要

> 大型语言模型（LLMs）表现出色，但访问顶级模型依赖推理服务提供商，这带来了信任问题——如何确保提供商使用的是他们声称的模型配置？我们提出了TOPLOC，一种创新的可验证推理方法。TOPLOC采用紧凑的局部敏感哈希机制处理中间激活，能够100%准确检测对模型、提示或精度的未经授权修改，实证评估中实现了零误报和漏报。该方法在各种硬件配置、GPU类型和代数重排序中均表现出色，验证速度远超原始推理。通过多项式编码方案，TOPLOC将提交的内存开销减少了$1000	imes$，每32个新标记仅需258字节存储，而Llama-3.1-8B-Instruct的标记嵌入直接存储则需要262KB。TOPLOC使用户能高效验证LLM推理计算，提升开放生态系统的信任与透明度，为去中心化和可验证的AI服务奠定基础。

> Large language models (LLMs) have proven to be very capable, but access to the best models currently rely on inference providers which introduces trust challenges -- how can we be sure that the provider is using the model configuration they claim? We propose TOPLOC, a novel method for verifiable inference that addresses this problem. TOPLOC leverages a compact locality sensitive hashing mechanism for intermediate activations which can detect unauthorized modifications to models, prompts, or precision with 100% accuracy, achieving no false positives or negatives in our empirical evaluations. Our approach is robust across diverse hardware configurations, GPU types, and algebraic reorderings, which allows for validation speeds significantly faster than the original inference. By introducing a polynomial encoding scheme, TOPLOC minimizes memory overhead of the generated commits by $1000\times$, requiring only 258 bytes of storage per 32 new tokens compared to the 262KB requirement of storing the token embeddings directly for Llama-3.1-8B-Instruct. Our method empowers users to verify LLM inference computations efficiently, fostering greater trust and transparency in open ecosystems and lays a foundation for decentralized and verifiable AI services.

[Arxiv](https://arxiv.org/abs/2501.16007)