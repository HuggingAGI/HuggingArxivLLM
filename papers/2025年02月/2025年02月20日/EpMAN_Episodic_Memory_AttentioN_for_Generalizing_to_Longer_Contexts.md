# EpMAN: 通过情景记忆注意力机制实现更长上下文的泛化能力

发布时间：2025年02月20日

`LLM理论

理由：这篇论文探讨了大型语言模型在处理长上下文时的挑战，并提出了一种新的方法（EpMAN）来改进模型的注意力机制。该研究专注于模型的内部机制优化，属于理论层面的探讨，因此归类为LLM理论。` `问答系统`

> EpMAN: Episodic Memory AttentioN for Generalizing to Longer Contexts

# 摘要

> 大型语言模型（LLMs）在多种语言任务中取得了显著成功，但高效处理长上下文仍是重大挑战。我们提出	extbf{EpMAN}，一种结合	extit{情景记忆}模块和	extit{整体关注}语义相关片段的方法，用于处理长上下文。通过	extit{情景注意力}的输出，该方法在训练和生成过程中重新加权解码器的自注意力机制，使其更关注存储的上下文KV缓存。实验表明，采用	extbf{EpMAN}训练的LLM解码器在单跳长上下文回忆和问答任务中表现更优，且在16k到256k个标记范围内比传统自注意力基线解码器及流行检索增强生成框架更具优势。

> Recent advances in Large Language Models (LLMs) have yielded impressive successes on many language tasks. However, efficient processing of long contexts using LLMs remains a significant challenge. We introduce \textbf{EpMAN} -- a method for processing long contexts in an \textit{episodic memory} module while \textit{holistically attending to} semantically relevant context chunks. The output of \textit{episodic attention} is then used to reweigh the decoder's self-attention to the stored KV cache of the context during training and generation. When an LLM decoder is trained using \textbf{EpMAN}, its performance on multiple challenging single-hop long-context recall and question-answering benchmarks is found to be stronger and more robust across the range from 16k to 256k tokens than baseline decoders trained with self-attention, and popular retrieval-augmented generation frameworks.

[Arxiv](https://arxiv.org/abs/2502.14280)