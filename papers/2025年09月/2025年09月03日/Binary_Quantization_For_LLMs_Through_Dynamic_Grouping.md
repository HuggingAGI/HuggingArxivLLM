# 基于动态分组的大型语言模型（LLMs）二进制量化

发布时间：2025年09月03日

`LLM理论` `基础理论`

> Binary Quantization For LLMs Through Dynamic Grouping

# 摘要

> 大型语言模型（LLMs）虽在众多自然语言处理（NLP）任务中表现卓越，却需占用大量内存和计算资源。二进制量化技术可将模型权重从16位脑浮点数压缩至{-1, 1}的1位表示，显著降低存储与推理成本。但这种激进的量化方式与更保守的4位量化相比，常导致明显的性能损耗。为此，本研究提出一种专为二进制量化定制的新型优化目标，并设计了三种算法以高效实现该目标。我们的方法通过自适应分组策略动态识别最优非结构化子矩阵，改进了分块量化效果。实验显示，该方法平均位长仅1.007位，且能保持较高模型质量：量化后的LLaMA 3.2 3B模型困惑度达8.23，与原始模型的7.81极为接近，远超此前SOTA模型BiLLM（困惑度123.90）。此外，其性能与效率均可与GPTQ等SOTA 4位量化方法相媲美。压缩过程高效，单个CPU核心量化完整的LLaMA 3.2 3B权重仅需14秒，全程耗时不足100分钟，且具备高度并行特性。
  代码 - https://github.com/johnnyzheng0636/WGM_bi_quan

> Large Language Models (LLMs) have demonstrated remarkable performance across a wide range of Natural Language Processing (NLP) tasks, but require substantial memory and computational resources. Binary quantization, which compresses model weights from 16-bit Brain Float to 1-bit representations in {-1, 1}, offers significant reductions in storage and inference costs. However, such aggressive quantization often leads to notable performance degradation compared to more conservative 4-bit quantization methods. In this research, we propose a novel optimization objective tailored for binary quantization, along with three algorithms designed to realize it effectively. Our method enhances blocked quantization by dynamically identifying optimal unstructured sub-matrices through adaptive grouping strategies. Experimental results demonstrate that our approach achieves an average bit length of just 1.007 bits, while maintaining high model quality. Specifically, our quantized LLaMA 3.2 3B model attains a perplexity of 8.23, remarkably close to the original 7.81, and surpasses previous SOTA BiLLM with a perplexity of only 123.90. Furthermore, our method is competitive with SOTA 4-bit approaches such as GPTQ in both performance and efficiency. The compression process is highly efficient, requiring only 14 seconds to quantize the full LLaMA 3.2 3B weights on a single CPU core, with the entire process completing in under 100 minutes and exhibiting embarrassingly parallel properties.
  Code - https://github.com/johnnyzheng0636/WGM_bi_quan

[Arxiv](https://arxiv.org/abs/2509.03054)