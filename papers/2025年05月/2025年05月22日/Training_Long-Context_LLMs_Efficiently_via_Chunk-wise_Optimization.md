# 分块优化：高效训练长上下文大语言模型的新方法

发布时间：2025年05月22日

`LLM理论` `机器学习`

> Training Long-Context LLMs Efficiently via Chunk-wise Optimization

# 摘要

> 长上下文大型语言模型（LLMs）虽然在文档处理方面表现出色，但其高昂的训练成本常常限制了定制化应用的开发。针对这一问题，我们提出了	extit{分块顺序优化}（SeCO），这是一种内存高效的训练方法，通过将长输入划分为多个易于处理的块来优化训练过程。每个块独立构建计算图并进行局部反向传播，从而确保内存中仅存储一个块的正向激活。在此基础上，我们进一步推出了	extit{稀疏分块优化}（SpaCO），该方法通过选择性地将梯度传播到特定块来降低计算开销，并引入了精心设计的补偿因子以确保梯度估计的无偏性。SpaCO成功地将反向传播的计算成本与上下文长度解耦，使得随着序列长度的增加，训练时间逐渐趋近于推理时间。作为轻量级训练包装器，SeCO和SpaCO均具备显著的实际优势。例如，在单个RTX 3090 GPU上使用LoRA微调8B模型时，SeCO将最大序列长度从1K扩展至16K，而SpaCO则展示了更快的训练速度——在相同实验设置下，其速度最高可达SeCO的3倍。这些创新为优化长上下文模型提供了新的思路，使其更易于在实际应用中推广。我们已将代码开源至\href{https://github.com/wenhaoli-xmu/seco}{此处}，方便研究者和开发者进一步探索与应用。

> While long-context large language models (LLMs) exhibit remarkable document processing capabilities, their prohibitively high training costs often hinder customized applications. To mitigate this issue, we propose \textit{Sequential Chunk-wise Optimization} (SeCO), a memory-efficient training paradigm that partitions lengthy inputs into manageable chunks. Each chunk independently constructs its computational graph and performs localized backpropagation, ensuring that only one chunk's forward activations are stored in memory. Building on SeCO, we further introduce \textit{Sparse Chunk-wise Optimization} (SpaCO), which reduces computational overhead by selectively propagating gradients to specific chunks and incorporates a carefully designed compensation factor to ensure unbiased gradient estimation. SpaCO decouples the computational cost of backpropagation from the context length, enabling training time to gradually converge to inference time as sequences become longer. Implemented as lightweight training wrappers, both SeCO and SpaCO offer substantial practical benefits. For example, when fine-tuning an 8B model with LoRA on a single RTX 3090 GPU, SeCO expands maximum sequence length from 1K to 16K tokens, while SpaCO demonstrates accelerated training speed -- achieving up to 3x faster than SeCO under the same experimental setup. These innovations provide new insights into optimizing long-context models, making them more accessible for practical applications. We have open-sourced the code at \href{https://github.com/wenhaoli-xmu/seco}{here}.

[Arxiv](https://arxiv.org/abs/2505.16710)