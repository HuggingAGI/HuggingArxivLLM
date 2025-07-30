# 压缩技术对医疗领域大型多模态语言模型的影响研究

发布时间：2025年07月29日

`LLM应用` `模型优化`

> The Effect of Compression Techniques on Large Multimodal Language Models in the Medical Domain

# 摘要

> 多模态大型语言模型（MLLMs）在医疗领域蕴藏着巨大潜力，但其计算成本高昂，亟需高效的压缩技术。本文探讨了结构剪枝与激活感知量化对医疗领域微调LLAVA模型的影响。我们提出了一种创新的剪枝层选择方法，深入分析了多种量化技术，并在剪枝-SFT-量化流水线中评估了性能权衡。通过我们的方法，70亿参数规模的MLLMs可在4 GB VRAM内高效运行，与传统技术相比，相同压缩比下内存占用减少70%，同时模型性能提升4%。

> Multimodal Large Language Models (MLLMs) hold huge potential for usage in the medical domain, but their computational costs necessitate efficient compression techniques. This paper evaluates the impact of structural pruning and activation-aware quantization on a fine-tuned LLAVA model for medical applications. We propose a novel layer selection method for pruning, analyze different quantization techniques, and assess the performance trade-offs in a prune-SFT-quantize pipeline. Our proposed method enables MLLMs with 7B parameters to run within 4 GB of VRAM, reducing memory usage by 70% while achieving 4% higher model performance compared to traditional pruning and quantization techniques in the same compression ratio.

[Arxiv](https://arxiv.org/abs/2507.21976)