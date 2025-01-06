# 基于全同态加密的微调大语言模型实用安全推理算法

发布时间：2025年01月03日

`LLM应用

理由：这篇论文主要讨论了如何通过结合全同态加密（FHE）、可证明安全理论和参数高效微调（PEFT）来提高大型语言模型（LLMs）推理的安全性和效率。论文聚焦于依赖开源基础模型并通过LoRA使用私有数据集微调的预训练LLMs，提出了保护私有数据的方法，并展示了在开源模型ChatGLM2-6B上的实验结果。这些内容主要涉及LLMs在实际应用中的安全性和效率优化，因此归类为“LLM应用”。` `隐私保护` `机器学习`

> Practical Secure Inference Algorithm for Fine-tuned Large Language Model Based on Fully Homomorphic Encryption

# 摘要

> # 摘要
大型语言模型（LLMs）如今在机器学习领域独占鳌头，展现出广阔的应用前景，但也伴随着隐私泄露的风险。我们巧妙地将全同态加密（FHE）、可证明安全理论与参数高效微调（PEFT）相结合，提出了一种既高效又安全的LLMs推理方案。具体来说，我们聚焦于那些依赖开源基础模型并通过LoRA使用私有数据集微调的预训练LLMs，这是LawGPT和BenTsao等垂直领域模型的常见路径。我们采用了以下两项关键技术：首先，我们将模型划分为公共部分和私有部分。公共部分的权重（如开源基础模型）公开可见，而私有部分（如LoRA矩阵）则需严密保护，从而大幅降低私有数据计算的开销。其次，我们提出了一种通用方法，将线性层转化为具备抗模型提取攻击能力且功能不变的私有线性层（PLL）。我们将此方法应用于LoRA矩阵，确保服务器在保护私有权重的同时，不限制用户输入。我们还证明了PLL抵御模型提取攻击的难度可归结为著名的带误差学习（LWE）难题。结合FHE，我们还能同时保护用户输入。这种转换方法适用于任何线性层，为其提供额外的模型提取攻击防护。本文以开源模型ChatGLM2-6B为基础，通过LoRA微调进行实验。结果显示，我们的方案推理效率高达1.61秒/令牌，充分证明了其良好的实用性。

> Large language models(LLMs) are currently at the forefront of the machine learning field, which show a broad application prospect but at the same time expose some risks of privacy leakage. We combined Fully Homomorphic Encryption(FHE) and provable security theory with Parameter-Efficient Fine-Tuning(PEFT) to propose an efficient and secure inference scheme for LLMs. More specially, we focus on pre-trained LLMs who rely on open-sourced base model and then fine-tuned with the private datasets by LoRA. This is a popular road-map for Vertical Domain Models such as LawGPT and BenTsao. We use two key technologies below. Firstly, we divide the whole model into the public part and the private part. The weights of public part are publicly accessible(e.g. the open-sourced base model) while the private part needs to be protected(e.g. the LoRA matrices). In this way, the overhead brought by computing on private data can be greatly reduced. Secondly, we propose a general method to transform a linear layer into another one which provides security against model extraction attacks and preserves its original functionality, which denotes as Private Linear Layer(PLL). Then we use this method on the LoRA matrices to make sure that the server protects their private weights without restricting the user's input. We also show that the difficulty of performing model extraction attacks for PLL can be generalized to the well-known hard problem Learning with Errors(LWE). Combing this method with FHE, we can protect user's input at the same time. This transform method can be applied to any linear layer to gain an extra protection against model extraction attacks. In this paper, we use the open-source model ChatGLM2-6B as the base model which is fine-tuned by LoRA. Experimental results show the inference efficiency of our scheme reaches 1.61s/token which shows that the scheme has good practicality.

[Arxiv](https://arxiv.org/abs/2501.01672)