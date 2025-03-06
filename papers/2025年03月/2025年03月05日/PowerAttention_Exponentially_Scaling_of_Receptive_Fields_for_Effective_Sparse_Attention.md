# 幂次注意力：通过指数增长感受野实现高效稀疏注意力的有效方法

发布时间：2025年03月05日

`LLM理论` `机器学习`

> PowerAttention: Exponentially Scaling of Receptive Fields for Effective Sparse Attention

# 摘要

> 大型语言模型（LLMs）在处理长上下文时因注意力机制的二次复杂度特性而面临效率瓶颈。稀疏注意力方法虽具潜力，但现有方案常受限于有效上下文不完整或实现复杂度高。我们从接收域角度全面解析了自回归LLMs的稀疏注意力机制，揭示现有方法在扩展接收域方面的局限性，并提出PowerAttention——一种创新的稀疏注意力设计，通过理论分析实现有效且完整的上下文扩展。PowerAttention在$d$层LLMs中实现了指数级接收域增长，使每个输出标记可关注$2^d$个标记，确保接收域的完整性和连续性。实验结果显示，PowerAttention在现有静态稀疏注意力方法基础上提升了5%至40%的性能，尤其在Passkey Retrieval和RULER等需长距离依赖的任务中表现优异，同时保持了与滑动窗口注意力相当的时间复杂度。效率评估进一步凸显了PowerAttention在预填和解码阶段的显著加速优势（在128K上下文下比动态稀疏注意力和全注意力快3.0倍），使其成为处理LLMs长序列的高效且用户友好的解决方案。


> Large Language Models (LLMs) face efficiency bottlenecks due to the quadratic complexity of the attention mechanism when processing long contexts. Sparse attention methods offer a promising solution, but existing approaches often suffer from incomplete effective context and/or require complex implementation of pipeline. We present a comprehensive analysis of sparse attention for autoregressive LLMs from the respective of receptive field, recognize the suboptimal nature of existing methods for expanding the receptive field, and introduce PowerAttention, a novel sparse attention design that facilitates effective and complete context extension through the theoretical analysis. PowerAttention achieves exponential receptive field growth in $d$-layer LLMs, allowing each output token to attend to $2^d$ tokens, ensuring completeness and continuity of the receptive field. Experiments demonstrate that PowerAttention outperforms existing static sparse attention methods by $5\sim 40\%$, especially on tasks demanding long-range dependencies like Passkey Retrieval and RULER, while maintaining a comparable time complexity to sliding window attention. Efficiency evaluations further highlight PowerAttention's superior speedup in both prefilling and decoding phases compared with dynamic sparse attentions and full attention ($3.0\times$ faster on 128K context), making it a highly effective and user-friendly solution for processing long sequences in LLMs.

[Arxiv](https://arxiv.org/abs/2503.03588)