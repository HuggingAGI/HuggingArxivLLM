# EfficientLLM: 大型语言模型中的高效性

发布时间：2025年05月19日

`LLM理论` `计算机科学` `计算机视觉`

> EfficientLLM: Efficiency in Large Language Models

# 摘要

> 大型语言模型（LLMs）虽然推动了显著的进步，但其日益增长的参数数量和上下文窗口带来了高昂的计算、能源和成本代价。我们很高兴推出EfficientLLM，这是一个全新的基准测试，也是首个全面的实证研究，旨在评估大规模LLMs的效率技术。我们的研究在生产级集群（48xGH200，8xH200 GPU）上进行，系统性地探索了三个关键方向：(1) 架构预训练（高效注意力机制变体：MQA、GQA、MLA、NSA；稀疏专家混合（MoE）），(2) 微调（参数高效方法：LoRA、RSLoRA、DoRA），以及(3) 推理（量化方法：int4、float16）。我们定义了六个精细指标（内存利用率、计算利用率、延迟、吞吐量、能源消耗、压缩率），以捕捉硬件饱和度、延迟-吞吐量平衡和碳排放成本。通过对超过100种模型-技术组合（0.5B-72B参数）的评估，我们得出了三个核心见解：(i) 效率涉及可量化的权衡：没有单一方法是普遍最优的；例如，MoE减少了计算量并提高了准确性，但增加了40%的VRAM，而int4量化在3-5%的精度下降内将内存/能源消耗降低了3.9倍。(ii) 最优解取决于任务和规模：MQA为资源受限的设备提供了最优的内存-延迟权衡，MLA在质量关键任务中实现了最低的困惑度，而RSLoRA仅在超过14B参数时才超越LoRA的效率。(iii) 技术跨模态通用：我们将评估扩展到大型视觉模型（Stable Diffusion 3.5，Wan 2.1）和视觉-语言模型（Qwen2.5-VL），证实了这些技术的有效迁移性。通过开源数据集、评估管道和排行榜，EfficientLLM为研究人员和工程师在下一代基础模型的效率-性能领域提供了至关重要的指导。


> Large Language Models (LLMs) have driven significant progress, yet their growing parameter counts and context windows incur prohibitive compute, energy, and monetary costs. We introduce EfficientLLM, a novel benchmark and the first comprehensive empirical study evaluating efficiency techniques for LLMs at scale. Conducted on a production-class cluster (48xGH200, 8xH200 GPUs), our study systematically explores three key axes: (1) architecture pretraining (efficient attention variants: MQA, GQA, MLA, NSA; sparse Mixture-of-Experts (MoE)), (2) fine-tuning (parameter-efficient methods: LoRA, RSLoRA, DoRA), and (3) inference (quantization methods: int4, float16). We define six fine-grained metrics (Memory Utilization, Compute Utilization, Latency, Throughput, Energy Consumption, Compression Rate) to capture hardware saturation, latency-throughput balance, and carbon cost. Evaluating over 100 model-technique pairs (0.5B-72B parameters), we derive three core insights: (i) Efficiency involves quantifiable trade-offs: no single method is universally optimal; e.g., MoE reduces FLOPs and improves accuracy but increases VRAM by 40%, while int4 quantization cuts memory/energy by up to 3.9x at a 3-5% accuracy drop. (ii) Optima are task- and scale-dependent: MQA offers optimal memory-latency trade-offs for constrained devices, MLA achieves lowest perplexity for quality-critical tasks, and RSLoRA surpasses LoRA efficiency only beyond 14B parameters. (iii) Techniques generalize across modalities: we extend evaluations to Large Vision Models (Stable Diffusion 3.5, Wan 2.1) and Vision-Language Models (Qwen2.5-VL), confirming effective transferability. By open-sourcing datasets, evaluation pipelines, and leaderboards, EfficientLLM provides essential guidance for researchers and engineers navigating the efficiency-performance landscape of next-generation foundation models.

[Arxiv](https://arxiv.org/abs/2505.13840)