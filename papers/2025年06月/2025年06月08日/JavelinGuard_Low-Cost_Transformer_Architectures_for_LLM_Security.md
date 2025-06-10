# JavelinGuard：面向LLM安全的低成本Transformer架构

发布时间：2025年06月08日

`LLM应用` `人工智能安全` `模型安全`

> JavelinGuard: Low-Cost Transformer Architectures for LLM Security

# 摘要

> 我们推出了JavelinGuard，一套专为检测大型语言模型（LLM）交互中的恶意意图设计的低成本、高性能模型架构，并针对生产部署进行了优化。近期在变换器架构方面的进展，包括紧凑型BERT（Devlin等人，2019）变体（例如ModernBERT（Warner等人，2024）），使我们能够构建高度准确的分类器，参数量低至约400M，甚至在标准CPU硬件上也能实现快速推理速度。我们系统地探索了五种逐渐复杂的基于变换器的架构：Sharanga（基线变换器分类器）、Mahendra（增强注意力加权池化和更深的头部）、Vaishnava和Ashwina（混合神经集成架构）、以及Raudra（一个带有专用损失函数的先进多任务框架）。我们的模型在九种多样化的对抗数据集上进行了严格的基准测试，包括流行的NotInject系列、BIPIA、Garak、ImprovedLLM、ToxicChat、WildGuard，以及我们新引入的JavelinBench，后者专门设计用于测试在具有挑战性的边界和硬负样本上的泛化能力。此外，我们将我们的架构与领先的开源护栏模型以及大型解码器-only LLM（如gpt-4o）进行了比较，展示了在准确性和延迟方面的优越成本性能权衡。我们的研究发现，尽管Raudra的多任务设计提供了最稳健的整体性能，但每种架构在速度、可解释性和资源要求方面都有独特的权衡，指导 practitioners 选择适合实际LLM安全应用的复杂性和效率的最佳平衡。


> We present JavelinGuard, a suite of low-cost, high-performance model architectures designed for detecting malicious intent in Large Language Model (LLM) interactions, optimized specifically for production deployment. Recent advances in transformer architectures, including compact BERT(Devlin et al. 2019) variants (e.g., ModernBERT (Warner et al. 2024)), allow us to build highly accurate classifiers with as few as approximately 400M parameters that achieve rapid inference speeds even on standard CPU hardware. We systematically explore five progressively sophisticated transformer-based architectures: Sharanga (baseline transformer classifier), Mahendra (enhanced attention-weighted pooling with deeper heads), Vaishnava and Ashwina (hybrid neural ensemble architectures), and Raudra (an advanced multi-task framework with specialized loss functions). Our models are rigorously benchmarked across nine diverse adversarial datasets, including popular sets like the NotInject series, BIPIA, Garak, ImprovedLLM, ToxicChat, WildGuard, and our newly introduced JavelinBench, specifically crafted to test generalization on challenging borderline and hard-negative cases. Additionally, we compare our architectures against leading open-source guardrail models as well as large decoder-only LLMs such as gpt-4o, demonstrating superior cost-performance trade-offs in terms of accuracy, and latency. Our findings reveal that while Raudra's multi-task design offers the most robust performance overall, each architecture presents unique trade-offs in speed, interpretability, and resource requirements, guiding practitioners in selecting the optimal balance of complexity and efficiency for real-world LLM security applications.

[Arxiv](https://arxiv.org/abs/2506.07330)