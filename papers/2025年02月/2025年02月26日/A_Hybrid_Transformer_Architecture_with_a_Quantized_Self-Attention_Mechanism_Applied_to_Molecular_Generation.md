# 混合型Transformer架构结合量化自注意力机制，应用于分子生成

发布时间：2025年02月26日

`LLM理论

论文摘要：自注意力机制在经典机器学习模型中的成功启发了量子模拟的发展，旨在减少计算开销。该机制通过整合查询和键矩阵计算序列中所有令牌对的注意力分数，并与值矩阵相乘生成输出矩阵，从而捕捉输入序列的长程依赖。在此，我们提出一种混合量子-经典自注意力机制，作为大型语言模型（LLMs）中变压器解码器的一部分。为展示其在化学领域的潜力，我们在QM9数据集上训练模型，以SMILES字符串为输入，每个字符串附带理化性质作为推理条件。理论分析表明，查询-键点积的时间复杂度从经典模型的数学公式降至量子模型的数学公式（其中$n$和$d$分别为序列长度和嵌入维度）。我们使用NVIDIA的CUDA-Q平台进行模拟，该平台专为高效GPU扩展设计。这项研究为量子增强的自然语言处理（NLP）提供了有前景的途径。

LLM理论`

> A Hybrid Transformer Architecture with a Quantized Self-Attention Mechanism Applied to Molecular Generation

# 摘要

> 自注意力机制在经典机器学习模型中的成功启发了量子模拟的发展，旨在减少计算开销。该机制通过整合查询和键矩阵计算序列中所有令牌对的注意力分数，并与值矩阵相乘生成输出矩阵，从而捕捉输入序列的长程依赖。在此，我们提出一种混合量子-经典自注意力机制，作为大型语言模型（LLMs）中变压器解码器的一部分。为展示其在化学领域的潜力，我们在QM9数据集上训练模型，以SMILES字符串为输入，每个字符串附带理化性质作为推理条件。理论分析表明，查询-键点积的时间复杂度从经典模型的【数学公式】降至量子模型的【数学公式】（其中$n$和$d$分别为序列长度和嵌入维度）。我们使用NVIDIA的CUDA-Q平台进行模拟，该平台专为高效GPU扩展设计。这项研究为量子增强的自然语言处理（NLP）提供了有前景的途径。

> The success of the self-attention mechanism in classical machine learning models has inspired the development of quantum analogs aimed at reducing computational overhead. Self-attention integrates learnable query and key matrices to calculate attention scores between all pairs of tokens in a sequence. These scores are then multiplied by a learnable value matrix to obtain the output self-attention matrix, enabling the model to effectively capture long-range dependencies within the input sequence. Here, we propose a hybrid quantum-classical self-attention mechanism as part of a transformer decoder, the architecture underlying large language models (LLMs). To demonstrate its utility in chemistry, we train this model on the QM9 dataset for conditional generation, using SMILES strings as input, each labeled with a set of physicochemical properties that serve as conditions during inference. Our theoretical analysis shows that the time complexity of the query-key dot product is reduced from $\mathcal{O}(n^2 d)$ in a classical model to $\mathcal{O}(n^2\log d)$ in our quantum model, where $n$ and $d$ represent the sequence length and embedding dimension, respectively. We perform simulations using NVIDIA's CUDA-Q platform, which is designed for efficient GPU scalability. This work provides a promising avenue for quantum-enhanced natural language processing (NLP).

[Arxiv](https://arxiv.org/abs/2502.19214)