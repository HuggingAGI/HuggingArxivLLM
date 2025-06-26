# 反向传播编程：大型语言模型在代码训练中获得可重用的算法抽象。

发布时间：2025年06月23日

`LLM理论` `软件工程`

> Programming by Backprop: LLMs Acquire Reusable Algorithmic Abstractions During Code Training

# 摘要

> 在源代码上训练大型语言模型（LLMs）能显著提升其通用推理能力，但这种提升背后的机制尚不明确。本文提出反向传播编程（Programming by Backprop，PBB）可能是这种效果的驱动力。PBB的核心思想是仅基于源代码训练模型，使其无需输入输出示例即可评估程序。我们通过在两个程序集上微调LLMs进行了验证：一个包含源代码和输入输出示例（w/ IO），另一个仅包含源代码（w/o IO）。实验结果表明，在多种设置下，LLMs确实具备在无输入输出示例情况下评估程序的能力，并得出以下观察：首先，程序以代码形式提供时，PBB的效果远优于语义等效的语言描述。其次，LLMs能够直接通过前向传播隐式评估程序，无需输入输出示例，而通过链式思维逐步解析程序时，输出结果更为可靠。我们进一步证明，与基于反映自然数据分布的输入输出对进行训练相比，PBB在跨输入的程序评估中更具鲁棒性。这表明，通过代码训练提升推理能力的机制在于：它使LLMs能够内化可复用的算法抽象。未来的研究仍有很大空间，旨在使LLMs更有效地从符号程序中学习，而这一方向的进步也将开启其他可能性，如通过训练形式化宪法原则实现模型对齐。

> Training large language models (LLMs) on source code significantly enhances their general-purpose reasoning abilities, but the mechanisms underlying this generalisation are poorly understood. In this paper, we propose Programming by Backprop (PBB) as a potential driver of this effect - teaching a model to evaluate a program for inputs by training on its source code alone, without ever seeing I/O examples. To explore this idea, we finetune LLMs on two sets of programs representing simple maths problems and algorithms: one with source code and I/O examples (w/ IO), the other with source code only (w/o IO). We find evidence that LLMs have some ability to evaluate w/o IO programs for inputs in a range of experimental settings, and make several observations. Firstly, PBB works significantly better when programs are provided as code rather than semantically equivalent language descriptions. Secondly, LLMs can produce outputs for w/o IO programs directly, by implicitly evaluating the program within the forward pass, and more reliably when stepping through the program in-context via chain-of-thought. We further show that PBB leads to more robust evaluation of programs across inputs than training on I/O pairs drawn from a distribution that mirrors naturally occurring data. Our findings suggest a mechanism for enhanced reasoning through code training: it allows LLMs to internalise reusable algorithmic abstractions. Significant scope remains for future work to enable LLMs to more effectively learn from symbolic procedures, and progress in this direction opens other avenues like model alignment by training on formal constitutional principles.

[Arxiv](https://arxiv.org/abs/2506.18777)