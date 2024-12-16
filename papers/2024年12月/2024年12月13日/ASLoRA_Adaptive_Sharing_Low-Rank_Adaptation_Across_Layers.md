# ASLoRA：跨层的自适应共享低秩适配

发布时间：2024年12月13日

`LLM应用` `模型优化`

> ASLoRA: Adaptive Sharing Low-Rank Adaptation Across Layers

# 摘要

> 随着大型语言模型（LLMs）规模不断扩大，传统的全量微调因计算和存储成本过高而愈发难以实行。虽然像LoRA这类热门的参数高效微调方法大幅减少了可调参数的数量，但仍有优化余地。在此项工作中，我们提出了ASLoRA，这是一种将全局共享与部分自适应共享相结合的跨层参数共享策略。具体而言，我们在所有层共享低秩矩阵A，并在训练时自适应合并矩阵B。这种共享机制不但能有效缓解过拟合，还能捕捉层间依赖关系，显著提升模型的表征能力。我们在各类NLP任务上开展了大量实验，表明ASLoRA在使用少于25%的参数时优于LoRA，彰显了其灵活性和卓越的参数效率。此外，对自适应共享策略的深入分析证实了其在增强模型灵活性和任务适应性方面的显著优势。

> As large language models (LLMs) grow in size, traditional full fine-tuning becomes increasingly impractical due to its high computational and storage costs. Although popular parameter-efficient fine-tuning methods, such as LoRA, have significantly reduced the number of tunable parameters, there is still room for further optimization. In this work, we propose ASLoRA, a cross-layer parameter-sharing strategy combining global sharing with partial adaptive sharing. Specifically, we share the low-rank matrix A across all layers and adaptively merge matrix B during training. This sharing mechanism not only mitigates overfitting effectively but also captures inter-layer dependencies, significantly enhancing the model's representational capability. We conduct extensive experiments on various NLP tasks, showing that ASLoRA outperforms LoRA while using less than 25% of the parameters, highlighting its flexibility and superior parameter efficiency. Furthermore, in-depth analyses of the adaptive sharing strategy confirm its significant advantages in enhancing both model flexibility and task adaptability.

[Arxiv](https://arxiv.org/abs/2412.10135)