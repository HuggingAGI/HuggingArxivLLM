# # 摘要
大型语言模型是局部线性映射，这一发现揭示了其在不同输入区域中的线性特性。

发布时间：2025年05月30日

`LLM理论` `大型语言模型` `模型理解`

> Large Language Models are Locally Linear Mappings

# 摘要

> 我们发现，多个开源大型语言模型（LLMs）的推理过程可以被转换为一个精确的线性系统，无需改变模型参数或预测结果。通过借鉴图像扩散模型中的局部线性技术，我们调整了针对下一个词预测的梯度计算，使得模型的Jacobian矩阵能够几乎完美地通过线性系统还原预测结果。我们在包括Llama 3、Gemma 3、Qwen 3、Phi 4、Mistral Ministral和OLMo 2等在内的多个模型上验证了这一方法，并通过奇异值分解发现，这些模型实际上运行在极低维的空间中，其中最大的奇异向量大多与最可能输出的词相关。这种方法不仅让我们能够将每一层（包括注意力机制和MLP组件）视为精确的线性系统，还揭示了语义概念的形成过程。尽管现代LLMs具有强大的非线性表达能力，但通过局部线性分解，我们得以深入理解其内部运作机制，并在下一个词预测过程中发现清晰的语义结构。

> We demonstrate that the inference operations of several open-weight large language models (LLMs) can be mapped to an exactly equivalent linear system for an input sequence without modifying the model weights or altering output predictions. Extending techniques from image diffusion models that exhibit local or piecewise linearity, we strategically alter the gradient computation with respect to a given input sequence for a next-token prediction such that the Jacobian of the model nearly exactly reproduces the forward prediction with a linear system. We demonstrate this approach across models (Llama 3, Gemma 3, Qwen 3, Phi 4, Mistral Ministral and OLMo 2, up to Llama 3.3 70B Q4) and show through the singular value decomposition of the detached Jacobian that these LLMs operate in extremely low-dimensional subspaces where many of the largest singular vectors decode to concepts related to the most-likely output token. This approach also allows us to examine the operation of each successive layer (and its attention and MLP components) as nearly-exact linear systems and observe the emergence of semantic concepts. Despite their expressive power and global nonlinearity, modern LLMs can be interpreted through nearly-exact locally linear decompositions that provide insights into their internal representations and reveal interpretable semantic structures in the next-token prediction process.

[Arxiv](https://arxiv.org/abs/2505.24293)