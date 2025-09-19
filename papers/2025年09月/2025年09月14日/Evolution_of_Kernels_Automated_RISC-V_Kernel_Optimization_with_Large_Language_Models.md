# 内核演进：基于大型语言模型的RISC-V内核自动化优化

发布时间：2025年09月14日

`RAG` `工业与制造`

> Evolution of Kernels: Automated RISC-V Kernel Optimization with Large Language Models

# 摘要

> 自动化内核设计是突破RISC-V等新兴硬件平台软件生态壁垒的关键。尽管大型语言模型（LLMs）在自动化内核优化方面已崭露头角，在技术文档全面、代码库成熟的CUDA领域成效显著，但在RISC-V这类参考资料匮乏的领域，其实际效果尚未得到验证。为此，我们提出了Evolution of Kernels（EoK）——一种基于LLM的新型进化式程序搜索框架，能够自动化参考资料有限领域的内核设计。EoK通过从成熟内核库的开发历史中挖掘并提炼可复用的优化思路（通用设计原则+可操作策略），有效缓解了参考资料匮乏的问题；随后，它利用这些思路指导LLM进行并行探索——这些思路通过检索增强生成（RAG）融入RISC-V特定上下文得以丰富，并优先采用历史上验证有效的技术。实证结果显示，EoK实现了中值1.27倍的性能加速，在全部80项内核设计评估任务中均超越人类专家，且较以往基于LLM的自动化内核设计方法提升了20%。这些结果不仅证实了将人类经验融入新兴领域的可行性，也彰显了基于LLM的自动化内核优化的巨大潜力。

> Automated kernel design is critical for overcoming software ecosystem barriers in emerging hardware platforms like RISC-V. While large language models (LLMs) have shown promise for automated kernel optimization, demonstrating success in CUDA domains with comprehensive technical documents and mature codebases, their effectiveness remains unproven for reference-scarce domains like RISC-V. We present Evolution of Kernels (EoK), a novel LLM-based evolutionary program search framework that automates kernel design for domains with limited reference material. EoK mitigates reference scarcity by mining and formalizing reusable optimization ideas (general design principles + actionable thoughts) from established kernel libraries' development histories; it then guides parallel LLM explorations using these ideas, enriched via Retrieval-Augmented Generation (RAG) with RISC-V-specific context, prioritizing historically effective techniques. Empirically, EoK achieves a median 1.27x speedup, surpassing human experts on all 80 evaluated kernel design tasks and improving upon prior LLM-based automated kernel design methods by 20%. These results underscore the viability of incorporating human experience into emerging domains and highlight the immense potential of LLM-based automated kernel optimization.

[Arxiv](https://arxiv.org/abs/2509.14265)