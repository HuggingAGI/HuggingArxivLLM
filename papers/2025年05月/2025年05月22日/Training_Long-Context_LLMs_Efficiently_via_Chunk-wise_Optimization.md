# 高效训练长上下文LLMs的分块优化方法

发布时间：2025年05月22日

`LLM应用` `计算机科学`

> Training Long-Context LLMs Efficiently via Chunk-wise Optimization

# 摘要

> 长上下文大型语言模型（LLMs）在文档处理方面表现出色，但其高昂的训练成本却限制了定制化应用的发展。为解决这一难题，我们提出了	extit{Sequential Chunk-wise Optimization}（SeCO），这是一种内存高效的训练方法，通过将长输入划分为小块来优化训练过程。每个小块独立计算并进行局部反向传播，仅需内存存储单个块的前向激活。在此基础上，我们进一步推出了	extit{Sparse Chunk-wise Optimization}（SpaCO），通过选择性梯度传播减少计算开销，并加入补偿因子确保梯度估计无偏。SpaCO实现了反向传播计算成本与上下文长度的解耦，使训练时间随序列增长逐渐接近推理时间。作为轻量级训练工具，SeCO和SpaCO带来了显著的实际优势。例如，在单张RTX 3090 GPU上使用LoRA微调8B模型时，SeCO将最大序列长度从1K扩展至16K，而SpaCO则实现了更快的训练速度——在相同实验条件下，其速度比SeCO快3倍。这些创新为优化长上下文模型提供了全新视角，使其更易于实际应用。我们已将代码开源至\href{https://github.com/wenhaoli-xmu/seco}{此处}。

> While long-context large language models (LLMs) exhibit remarkable document processing capabilities, their prohibitively high training costs often hinder customized applications. To mitigate this issue, we propose \textit{Sequential Chunk-wise Optimization} (SeCO), a memory-efficient training paradigm that partitions lengthy inputs into manageable chunks. Each chunk independently constructs its computational graph and performs localized backpropagation, ensuring that only one chunk's forward activations are stored in memory. Building on SeCO, we further introduce \textit{Sparse Chunk-wise Optimization} (SpaCO), which reduces computational overhead by selectively propagating gradients to specific chunks and incorporates a carefully designed compensation factor to ensure unbiased gradient estimation. SpaCO decouples the computational cost of backpropagation from the context length, enabling training time to gradually converge to inference time as sequences become longer. Implemented as lightweight training wrappers, both SeCO and SpaCO offer substantial practical benefits. For example, when fine-tuning an 8B model with LoRA on a single RTX 3090 GPU, SeCO expands maximum sequence length from 1K to 16K tokens, while SpaCO demonstrates accelerated training speed -- achieving up to 3x faster than SeCO under the same experimental setup. These innovations provide new insights into optimizing long-context models, making them more accessible for practical applications. We have open-sourced the code at \href{https://github.com/wenhaoli-xmu/seco}{here}.

[Arxiv](https://arxiv.org/abs/2505.16710)