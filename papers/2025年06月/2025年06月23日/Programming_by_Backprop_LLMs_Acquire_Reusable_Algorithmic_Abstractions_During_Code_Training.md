# LLMs在代码训练中掌握可重用算法抽象：反向传播编程新视角

发布时间：2025年06月23日

`LLM应用` `人工智能` `软件工程`

> Programming by Backprop: LLMs Acquire Reusable Algorithmic Abstractions During Code Training

# 摘要

> 在源代码上训练大型语言模型（LLMs）可以显著提升其通用推理能力，但这种提升背后的机制尚不明确。本文提出了一种名为编程通过反向传播（Programming by Backprop，简称PBB）的方法，旨在通过仅训练模型的源代码，而无需输入输出示例，来提升其推理能力。我们通过在两组程序上微调LLMs进行了实验验证：一组包含源代码和输入输出示例（w/ IO），另一组仅包含源代码（w/o IO）。实验结果表明，LLMs在多种实验设置下具备评估w/o IO程序的能力，并得出以下结论：

首先，当程序以代码形式呈现而非语义等价的语言描述时，PBB的效果显著提升。其次，LLMs可以通过在前向传播过程中隐式评估程序直接生成w/o IO程序的输出，而通过链式思维在上下文中逐步解析程序时，输出结果更为可靠。此外，我们发现相较于基于与自然发生数据分布相匹配的输入输出对进行训练，PBB能够实现更稳健的程序评估。这些发现揭示了一种通过代码训练提升推理能力的机制：它使LLMs能够内化可复用的算法抽象。未来研究仍有许多探索空间，以期使LLMs更有效地从符号化流程中学习，而这方面的进展将开启其他研究方向，例如通过训练模型遵守正式的宪法原则来实现模型对齐。

> Training large language models (LLMs) on source code significantly enhances their general-purpose reasoning abilities, but the mechanisms underlying this generalisation are poorly understood. In this paper, we propose Programming by Backprop (PBB) as a potential driver of this effect - teaching a model to evaluate a program for inputs by training on its source code alone, without ever seeing I/O examples. To explore this idea, we finetune LLMs on two sets of programs representing simple maths problems and algorithms: one with source code and I/O examples (w/ IO), the other with source code only (w/o IO). We find evidence that LLMs have some ability to evaluate w/o IO programs for inputs in a range of experimental settings, and make several observations. Firstly, PBB works significantly better when programs are provided as code rather than semantically equivalent language descriptions. Secondly, LLMs can produce outputs for w/o IO programs directly, by implicitly evaluating the program within the forward pass, and more reliably when stepping through the program in-context via chain-of-thought. We further show that PBB leads to more robust evaluation of programs across inputs than training on I/O pairs drawn from a distribution that mirrors naturally occurring data. Our findings suggest a mechanism for enhanced reasoning through code training: it allows LLMs to internalise reusable algorithmic abstractions. Significant scope remains for future work to enable LLMs to more effectively learn from symbolic procedures, and progress in this direction opens other avenues like model alignment by training on formal constitutional principles.

[Arxiv](https://arxiv.org/abs/2506.18777)