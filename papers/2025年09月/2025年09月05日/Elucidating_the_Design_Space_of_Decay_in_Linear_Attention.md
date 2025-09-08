# 解析线性注意力中衰减的设计空间

发布时间：2025年09月05日

`LLM理论` `基础理论`

> Elucidating the Design Space of Decay in Linear Attention

# 摘要

> 本文全面研究了线性复杂度序列模型中固有的衰减机制。我们从四个关键维度系统界定了衰减机制的设计空间：参数化策略（即衰减的计算方法）、参数共享（即衰减计算中辅助参数的使用方式）、衰减粒度（对比标量衰减与向量衰减），以及与相对位置编码方法（如旋转位置嵌入RoPE）的兼容性。通过在多种语言建模任务上开展大量实验，我们得出了几个关键见解。首先，衰减参数化策略的设计需仔细考量——研究发现，有效的配置通常局限于特定参数范围。其次，参数共享不可随意使用，因其可能导致衰减值过大或过小，进而严重影响性能。第三，在相同参数化策略下，标量衰减性能通常不及向量衰减；但在某些采用替代参数化策略的场景中，标量衰减效果可能意外超过向量衰减。最后，分析表明，常用的相对位置编码方法（如旋转位置嵌入RoPE）通常无法为大多数线性注意力机制带来实质性益处。

> This paper presents a comprehensive investigation into the decay mechanisms inherent in linear complexity sequence models. We systematically delineate the design space of decay mechanisms across four pivotal dimensions: parameterization strategy, which refers to the computational methodology for decay; parameter sharing, which involves the utilization of supplementary parameters for decay computation; decay granularity, comparing scalar versus vector-based decay; and compatibility with relative positional encoding methods, such as Rotary Position Embedding (RoPE). Through an extensive series of experiments conducted on diverse language modeling tasks, we uncovered several critical insights. Firstly, the design of the parameterization strategy for decay requires meticulous consideration. Our findings indicate that effective configurations are typically confined to a specific range of parameters. Secondly, parameter sharing cannot be used arbitrarily, as it may cause decay values to be too large or too small, thereby significantly impacting performance. Thirdly, under identical parameterization strategies, scalar decay generally underperforms compared to its vector-based counterpart. However, in certain scenarios with alternative parameterization strategies, scalar decay may unexpectedly surpass vector decay in efficacy. Lastly, our analysis reveals that RoPE, a commonly employed relative positional encoding method, typically fails to provide tangible benefits to the majority of linear attention mechanisms.

[Arxiv](https://arxiv.org/abs/2509.05282)