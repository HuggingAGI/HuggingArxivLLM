# 人人为我：大型语言模型借助其他标记传递的信息，在最后一个标记处解决心算问题

发布时间：2025年09月11日

`LLM理论` `基础理论`

> All for One: LLMs Solve Mental Math at the Last Token With Information Transferred From Other Tokens

# 摘要

> 大型语言模型（LLMs）虽在众多计算任务中表现出色，但其内部工作机制仍不明确。理论上，因果自注意力与多层感知机层的组合让每个token都能基于所有前文token访问并计算信息。但在实际中，这类操作究竟存在多少？本文针对心算任务（即无需显式推理，直接通过下一个token预测完成数学计算），通过三个步骤展开研究：在初始层抑制输入特定的token计算，在后续几层限制跨token位置的信息传输路径，在剩余层则强制所有计算集中于最后一个token。借助提出的两种技术——上下文感知均值消融（CAMA）与基于注意力的窥探（ABP），我们识别出一个“万物归一”子图（AF1）。该子图在多种心算任务中精度优异，其中有意义的计算发生得极晚（从层深度来看），且仅在最后一个token处进行；该token会在少数特定中间层接收其他token的信息。在多种模型和算术表达式上的实验证实，该子图是模型高性能的充分必要条件，能在不同模型间迁移，且适用于多种输入风格。对CAMA和ABP的不同变体进行消融实验后发现，它们相较其他方法具有独特优势，这一发现或具有独立研究价值。

> Large language models (LLMs) demonstrate proficiency across numerous computational tasks, yet their inner workings remain unclear. In theory, the combination of causal self-attention and multilayer perceptron layers allows every token to access and compute information based on all preceding tokens. In practice, to what extent are such operations present? In this paper, on mental math tasks (i.e., direct math calculation via next-token prediction without explicit reasoning), we investigate this question in three steps: inhibiting input-specific token computations in the initial layers, restricting the routes of information transfer across token positions in the next few layers, and forcing all computation to happen at the last token in the remaining layers. With two proposed techniques, Context-Aware Mean Ablation (CAMA) and Attention-Based Peeking (ABP), we identify an All-for-One subgraph (AF1) with high accuracy on a wide variety of mental math tasks, where meaningful computation occurs very late (in terms of layer depth) and only at the last token, which receives information of other tokens in few specific middle layers. Experiments on a variety of models and arithmetic expressions show that this subgraph is sufficient and necessary for high model performance, transfers across different models, and works on a variety of input styles. Ablations on different CAMA and ABP alternatives reveal their unique advantages over other methods, which may be of independent interest.

[Arxiv](https://arxiv.org/abs/2509.09650)