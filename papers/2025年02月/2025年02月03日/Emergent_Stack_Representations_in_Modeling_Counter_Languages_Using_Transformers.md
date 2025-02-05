# Transformer 建模计数器语言中的涌现堆栈表示

发布时间：2025年02月03日

`LLM理论

理由：这篇论文主要探讨了Transformer架构的内部工作机制，特别是其在计数器语言上的学习能力。通过研究模型在特定语言上的表现，论文试图揭示Transformer学习语言的算法细节。这属于对大型语言模型（LLM）内部机制的理论研究，因此归类为“LLM理论”。` `机器学习`

> Emergent Stack Representations in Modeling Counter Languages Using Transformers

# 摘要

> Transformer 架构是现代语言模型的基石，但其内部工作机制仍是一个谜。过去的研究通过在已知形式语言上训练这些模型，来探究其学习能力。我们进一步研究了在计数器语言上训练的Transformer模型，这些语言可以用计数器变量建模。我们在4种计数器语言上训练模型，并用堆栈表示这些语言，堆栈深度对应计数器值。通过探测每个输入标记的堆栈深度表示，我们发现模型在作为下一个标记预测器训练时，学会了类似堆栈的表示。这让我们更接近理解Transformer学习语言的算法细节，并有助于电路发现。

> Transformer architectures are the backbone of most modern language models, but understanding the inner workings of these models still largely remains an open problem. One way that research in the past has tackled this problem is by isolating the learning capabilities of these architectures by training them over well-understood classes of formal languages. We extend this literature by analyzing models trained over counter languages, which can be modeled using counter variables. We train transformer models on 4 counter languages, and equivalently formulate these languages using stacks, whose depths can be understood as the counter values. We then probe their internal representations for stack depths at each input token to show that these models when trained as next token predictors learn stack-like representations. This brings us closer to understanding the algorithmic details of how transformers learn languages and helps in circuit discovery.

[Arxiv](https://arxiv.org/abs/2502.01432)