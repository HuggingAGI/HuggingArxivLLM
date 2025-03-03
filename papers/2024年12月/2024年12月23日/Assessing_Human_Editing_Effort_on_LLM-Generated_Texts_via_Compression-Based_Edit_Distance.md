# 借助基于压缩的编辑距离来评估人类针对 LLM 生成文本的编辑工作量

发布时间：2024年12月23日

`LLM应用` `文本编辑`

> Assessing Human Editing Effort on LLM-Generated Texts via Compression-Based Edit Distance

# 摘要

> 评估大型语言模型（LLMs）生成的文本中人类编辑的程度，对于理解人类与人工智能的交互以及提升自动文本生成系统的质量极为关键。现有的编辑距离度量标准，像莱文斯坦、BLEU、ROUGE 以及 TER 等，常常难以精确衡量后期编辑所需的工作量，尤其是在编辑涉及大量修改（比如块操作）的情况下。在本文中，我们基于莱姆佩尔 - 齐夫 - 77 算法引入了一种新颖的基于压缩的编辑距离度量标准，旨在量化对 LLM 生成文本的后期编辑量。我们的方法借助文本压缩的特性来测量原始文本与编辑后文本之间的信息差异。通过在真实世界的人类编辑数据集上开展实验，我们证明了我们所提出的度量标准与实际编辑时间和工作量高度相关。我们还展示了 LLM 对编辑速度有一种隐含的理解，这与我们的度量标准十分契合。此外，我们将我们的度量标准与现有的进行了对比，凸显了其在以线性计算效率捕获复杂编辑方面的优势。我们的代码和数据可在：https://github.com/NDV-tiime/CompressionDistance 获取。

> Assessing the extent of human edits on texts generated by Large Language Models (LLMs) is crucial to understanding the human-AI interactions and improving the quality of automated text generation systems. Existing edit distance metrics, such as Levenshtein, BLEU, ROUGE, and TER, often fail to accurately measure the effort required for post-editing, especially when edits involve substantial modifications, such as block operations. In this paper, we introduce a novel compression-based edit distance metric grounded in the Lempel-Ziv-77 algorithm, designed to quantify the amount of post-editing applied to LLM-generated texts. Our method leverages the properties of text compression to measure the informational difference between the original and edited texts. Through experiments on real-world human edits datasets, we demonstrate that our proposed metric is highly correlated with actual edit time and effort. We also show that LLMs exhibit an implicit understanding of editing speed, that aligns well with our metric. Furthermore, we compare our metric with existing ones, highlighting its advantages in capturing complex edits with linear computational efficiency. Our code and data are available at: https://github.com/NDV-tiime/CompressionDistance

[Arxiv](https://arxiv.org/abs/2412.17321)