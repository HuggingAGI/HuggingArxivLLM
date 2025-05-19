# 加法几乎万能：双二进制分解助力神经网络压缩

发布时间：2025年05月16日

`LLM应用` `人工智能` `机器学习`

> Addition is almost all you need: Compressing neural networks with double binary factorization

# 摘要

> 二值量化方法通过将权重矩阵替换为二值矩阵，并用更廉价的加法代替昂贵的乘法，为处理大型语言模型（LLMs）日益增长的计算和存储需求提供了一种计算高效的方法。然而，严格的量化约束（±1）可能导致显著的准确性下降。本文提出了一种名为双二值分解（DBF）的新方法，该方法将密集的权重矩阵分解为两个二值（符号）矩阵的乘积，每个矩阵还伴随缩放向量。DBF在保持二值表示的效率优势的同时，实现了与或优于现有最优方法的压缩率。具体而言，在1位每权重范围内，DBF优于现有的二值化方法。在2位每权重范围内，DBF与最佳量化方法（如QuIP#和QTIP）相媲美。与大多数现有压缩技术不同，后者提供的压缩级别选择有限，DBF通过调整分解的中间维度，允许对压缩比率进行精细控制。基于这一优势，我们进一步提出了一种基于先前开发的通道剪枝准则，用于估计DBF的非均匀分层压缩比率的算法。代码可在以下位置获取：https://github.com/usamec/double_binary

> Binary quantization approaches, which replace weight matrices with binary matrices and substitute costly multiplications with cheaper additions, offer a computationally efficient approach to address the increasing computational and storage requirements of Large Language Models (LLMs). However, the severe quantization constraint ($\pm1$) can lead to significant accuracy degradation. In this paper, we propose Double Binary Factorization (DBF), a novel method that factorizes dense weight matrices into products of two binary (sign) matrices, each accompanied by scaling vectors. DBF preserves the efficiency advantages of binary representations while achieving compression rates that are competitive with or superior to state-of-the-art methods. Specifically, in a 1-bit per weight range, DBF is better than existing binarization approaches. In a 2-bit per weight range, DBF is competitive with the best quantization methods like QuIP\# and QTIP. Unlike most existing compression techniques, which offer limited compression level choices, DBF allows fine-grained control over compression ratios by adjusting the factorization's intermediate dimension. Based on this advantage, we further introduce an algorithm for estimating non-uniform layer-wise compression ratios for DBF, based on previously developed channel pruning criteria.
  Code available at: https://github.com/usamec/double_binary

[Arxiv](https://arxiv.org/abs/2505.11076)