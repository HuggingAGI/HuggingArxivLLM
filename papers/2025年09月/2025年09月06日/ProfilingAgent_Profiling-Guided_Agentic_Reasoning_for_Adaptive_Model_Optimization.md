# ProfilingAgent：剖析引导的智能体推理用于自适应模型优化

发布时间：2025年09月06日

`Agent` `基础理论`

> ProfilingAgent: Profiling-Guided Agentic Reasoning for Adaptive Model Optimization

# 摘要

> 基础模型正面临越来越严峻的计算与内存瓶颈，这阻碍了其在资源受限平台上的部署。尽管剪枝、量化等压缩技术已被广泛应用，但多数方法依赖统一的启发式策略，忽略了架构与运行时的异质性。分析工具虽能暴露每层的延迟、内存及计算成本，却鲜少被整合到自动化流程中。为此，我们提出ProfilingAgent——一种基于分析的智能体方案，它利用大型语言模型（LLMs），通过结构化剪枝与训练后动态量化实现压缩过程的自动化。我们的模块化多智能体系统会综合静态指标（如MACs、参数数量）与动态信号（如延迟、内存）进行推理，从而制定特定于架构的策略。与启发式基线不同，ProfilingAgent能针对瓶颈定制分层决策。在ImageNet-1K、CIFAR-10、CIFAR-100数据集上，结合ResNet-101、ViT-B/16、Swin-B及DeiT-B/16模型的实验显示：剪枝能保持精度竞争力甚至提升精度（ImageNet-1K上精度下降约1%，ViT-B/16在小数据集上精度提升+2%）；量化则可节省高达74%的内存，且精度损失<0.5%。此外，我们的量化方法还能实现稳定的推理加速，最高达1.74倍。与GPT-4o、GPT-4-Turbo的对比研究进一步强调了LLM推理质量对迭代剪枝的重要性。这些结果证实，智能体系统可作为分析引导模型优化的可扩展解决方案。

> Foundation models face growing compute and memory bottlenecks, hindering deployment on resource-limited platforms. While compression techniques such as pruning and quantization are widely used, most rely on uniform heuristics that ignore architectural and runtime heterogeneity. Profiling tools expose per-layer latency, memory, and compute cost, yet are rarely integrated into automated pipelines. We propose ProfilingAgent, a profiling-guided, agentic approach that uses large language models (LLMs) to automate compression via structured pruning and post-training dynamic quantization. Our modular multi-agent system reasons over static metrics (MACs, parameter counts) and dynamic signals (latency, memory) to design architecture-specific strategies. Unlike heuristic baselines, ProfilingAgent tailors layer-wise decisions to bottlenecks. Experiments on ImageNet-1K, CIFAR-10, and CIFAR-100 with ResNet-101, ViT-B/16, Swin-B, and DeiT-B/16 show pruning maintains competitive or improved accuracy (about 1% drop on ImageNet-1K, +2% gains for ViT-B/16 on smaller datasets), while quantization achieves up to 74% memory savings with <0.5% accuracy loss. Our quantization also yields consistent inference speedups of up to 1.74 times faster. Comparative studies with GPT-4o and GPT-4-Turbo highlight the importance of LLM reasoning quality for iterative pruning. These results establish agentic systems as scalable solutions for profiling-guided model optimization.

[Arxiv](https://arxiv.org/abs/2509.05584)