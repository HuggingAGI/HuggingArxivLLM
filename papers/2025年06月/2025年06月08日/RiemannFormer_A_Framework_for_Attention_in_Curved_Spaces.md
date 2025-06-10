# RiemannFormer：曲面空间注意力机制的框架

发布时间：2025年06月08日

`LLM理论` `计算机视觉`

> RiemannFormer: A Framework for Attention in Curved Spaces

# 摘要

> 本研究致力于揭示进一步释放基于Transformer架构潜力的见解，其中一个核心动机是为Transformer的注意力机制提供几何解释。在我们的框架中，注意力机制主要涉及度量张量、切空间、内积及其相互关系。这些量和结构在离散位置上通过切向量的平行传输紧密相连。为了提高学习效率，我们通过巧妙的预定义配置减少参数数量。此外，考虑到Transformer本身忽略了局部归纳偏置，我们引入了一种显式机制，通过衰减远程值来突出邻域。实验结果表明，我们的模块相对于基线模型在性能上有显著提升。接下来，我们还将陆续开展更多针对视觉模型和大型语言模型的评估实验。

> This research endeavors to offer insights into unlocking the further potential of transformer-based architectures. One of the primary motivations is to offer a geometric interpretation for the attention mechanism in transformers. In our framework, the attention mainly involves metric tensors, tangent spaces, inner product, and how they relate to each other. These quantities and structures at discrete positions are intricately interconnected via the parallel transport of tangent vectors. To make the learning process more efficient, we reduce the number of parameters through ingenious predefined configurations. Moreover, we introduce an explicit mechanism to highlight a neighborhood by attenuating the remote values, given that transformers inherently neglect local inductive bias. Experimental results demonstrate that our modules deliver significant performance improvements relative to the baseline. More evaluation experiments on visual and large language models will be launched successively.

[Arxiv](https://arxiv.org/abs/2506.07405)