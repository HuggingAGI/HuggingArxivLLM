# END：高效上下文去噪的早期噪声丢弃方法

发布时间：2025年02月26日

`LLM理论` `信息检索` `问答系统`

> END: Early Noise Dropping for Efficient and Effective Context Denoising

# 摘要

> 大型语言模型（LLMs）在多种自然语言处理任务中表现出色，但输入中无关或噪声的上下文会显著影响输出质量，这一问题在长上下文和短上下文场景中尤为突出，例如检索增强生成、表格问答和上下文学习。我们发现LLMs能在生成token前的早期层隐式识别输入中是否有用信息。基于此，我们提出无需微调LLMs的Early Noise Dropping（END）方法。END通过将输入序列分割为块，并利用LLMs早期层的线性探测器区分信息块与噪声块。通过在早期丢弃噪声块，END保留关键信息，减少干扰，降低计算开销。实验表明，END显著提升了LLMs在多个数据集上的性能和效率。此外，这项工作通过研究LLMs对输入的隐式理解，进一步揭示了其内部上下文推理机制。

> Large Language Models (LLMs) have demonstrated remarkable performance across a wide range of natural language processing tasks. However, they are often distracted by irrelevant or noisy context in input sequences that degrades output quality. This problem affects both long- and short-context scenarios, such as retrieval-augmented generation, table question-answering, and in-context learning. We reveal that LLMs can implicitly identify whether input sequences contain useful information at early layers, prior to token generation. Leveraging this insight, we introduce Early Noise Dropping (\textsc{END}), a novel approach to mitigate this issue without requiring fine-tuning the LLMs. \textsc{END} segments input sequences into chunks and employs a linear prober on the early layers of LLMs to differentiate between informative and noisy chunks. By discarding noisy chunks early in the process, \textsc{END} preserves critical information, reduces distraction, and lowers computational overhead. Extensive experiments demonstrate that \textsc{END} significantly improves both performance and efficiency across different LLMs on multiple evaluation datasets. Furthermore, by investigating LLMs' implicit understanding to the input with the prober, this work also deepens understanding of how LLMs do reasoning with contexts internally.

[Arxiv](https://arxiv.org/abs/2502.18915)