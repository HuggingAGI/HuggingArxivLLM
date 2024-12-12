# 大型语言模型的计数能力及其受标记化的影响

发布时间：2024年10月25日

`LLM理论` `语言模型` `推理任务`

> Counting Ability of Large Language Models and Impact of Tokenization

# 摘要

> Transformers 作为现代大型语言模型（LLMs）的核心架构，存在着一些固有的局限性，影响了其推理能力。和递归网络不同，Transformers 没有递归连接，这使其计算深度受限。这种限制让其处于 TC$^0$复杂类别中，理论上，随着输入长度增加，它们难以应对需要深度推理的任务。计数作为众多推理任务的基础组成部分，需要推理深度随输入线性增长才能得以归纳执行。此前的研究虽已明确基于 Transformer 的专家模型（即专为计数任务训练的模型）的计数能力上限，但由于推理机制的差异，这些成果无法直接应用于通用的 LLMs。近期的研究表明，思维链（CoT）推理能够在一定程度上缓解 Transformers 在计数任务中的架构限制。然而，这些模型中标记化的作用却鲜有关注。与常采用字符级标记化的专家模型不同，LLMs 通常依赖字节级（BPE）标记器，这从根本上改变了推理的处理方式。我们的工作探究了标记化对 LLMs 计数能力的影响，根据输入标记化的差异揭示了显著的性能变化。我们提供了理论和实验分析，深入阐释了标记化选择如何影响模型的理论可计算性，进而为设计新的标记化方法以增强 LLMs 的推理能力带来启发。

> Transformers, the backbone of modern large language models (LLMs), face inherent architectural limitations that impede their reasoning capabilities. Unlike recurrent networks, Transformers lack recurrent connections, confining them to constant-depth computation. This restriction places them in the complexity class TC$^0$, making them theoretically incapable of solving tasks that demand increasingly deep reasoning as input length grows. Counting, a fundamental component of many reasoning tasks, also requires reasoning depth to grow linearly to be performed inductively. While previous studies have established the upper limits of counting ability in Transformer-based expert models (i.e., models specifically trained for counting tasks), these findings do not directly extend to general-purpose LLMs due to differences in reasoning mechanisms. Recent work has highlighted how Chain of Thought (CoT) reasoning can help alleviate some of the architectural limitations of Transformers in counting tasks. However, little attention has been paid to the role of tokenization in these models. Unlike expert models that often use character-level tokenization, LLMs typically rely on byte-level (BPE) tokenizers, which fundamentally alters the way reasoning is processed. Our work investigates the impact of tokenization on the counting abilities of LLMs, uncovering substantial performance variations based on input tokenization differences. We provide both theoretical and experimental analyses, offering insights into how tokenization choices can undermine models' theoretical computability, thereby inspiring the design of new tokenization methods to enhance reasoning in LLMs.

[Arxiv](https://arxiv.org/abs/2410.19730)