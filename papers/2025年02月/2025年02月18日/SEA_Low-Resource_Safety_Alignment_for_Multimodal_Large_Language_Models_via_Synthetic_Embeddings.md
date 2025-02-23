# # SEA：面向多模态大型语言模型的低资源安全性对齐方法——基于合成嵌入

发布时间：2025年02月18日

`LLM理论` `多模态` `模型安全`

> SEA: Low-Resource Safety Alignment for Multimodal Large Language Models via Synthetic Embeddings

# 摘要

> 多模态大型语言模型（MLLMs）面临严峻的安全漏洞问题。虽然通过包含文本和额外模态数据的多模态数据集进行安全对齐能有效提升模型安全性，但这类数据集的构建成本极高。现有低资源安全对齐方法，包括文本对齐，难以应对额外模态带来的安全威胁。为解决这一难题，我们提出了一种名为合成嵌入增强的安全对齐（SEA）方法。该方法通过梯度更新优化额外模态的嵌入，从而扩展文本数据集，实现仅凭文本数据即可完成多模态安全对齐训练。实验结果表明，基于图像、视频和音频的MLLM在单个RTX3090 GPU上只需24秒即可生成高质量嵌入。面对额外模态的威胁，SEA显著提升了MLLM的安全性。为评估视频和音频带来的安全风险，我们还推出了一项全新基准测试——VA-SafetyBench。该基准测试在多个MLLM上均表现出高攻击成功率，充分验证了其挑战性。我们的代码和数据已开源，访问地址为https://github.com/ZeroNLP/SEA。

> Multimodal Large Language Models (MLLMs) have serious security vulnerabilities.While safety alignment using multimodal datasets consisting of text and data of additional modalities can effectively enhance MLLM's security, it is costly to construct these datasets. Existing low-resource security alignment methods, including textual alignment, have been found to struggle with the security risks posed by additional modalities. To address this, we propose Synthetic Embedding augmented safety Alignment (SEA), which optimizes embeddings of additional modality through gradient updates to expand textual datasets. This enables multimodal safety alignment training even when only textual data is available. Extensive experiments on image, video, and audio-based MLLMs demonstrate that SEA can synthesize a high-quality embedding on a single RTX3090 GPU within 24 seconds. SEA significantly improves the security of MLLMs when faced with threats from additional modalities. To assess the security risks introduced by video and audio, we also introduced a new benchmark called VA-SafetyBench. High attack success rates across multiple MLLMs validate its challenge. Our code and data will be available at https://github.com/ZeroNLP/SEA.

[Arxiv](https://arxiv.org/abs/2502.12562)