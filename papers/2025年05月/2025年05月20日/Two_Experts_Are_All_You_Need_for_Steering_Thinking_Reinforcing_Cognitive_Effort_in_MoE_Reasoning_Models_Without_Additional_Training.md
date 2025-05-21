# 两位专家就够了！无需额外训练，增强MoE推理模型的认知推理能力

发布时间：2025年05月20日

`LLM理论` `人工智能` `推理模型`

> Two Experts Are All You Need for Steering Thinking: Reinforcing Cognitive Effort in MoE Reasoning Models Without Additional Training

# 摘要

> 大型推理模型（LRMs）中的混合专家（MoE）架构通过选择性激活专家来促进结构化认知过程，展现了令人印象深刻的推理能力。尽管取得了显著进展，现有的推理模型通常会面临认知低效问题，如过度思考和思考不足。为了解决这些限制，我们引入了一种名为Reinforcing Cognitive Experts（RICE）的新型推理时控制方法，旨在无需额外训练或复杂启发式方法的情况下提升推理性能。通过归一化点互信息（nPMI），我们系统地识别出专门的专家，即''认知专家''，这些专家负责编排以''_model''等标记为特征的元级别推理操作。在严格的定量和科学推理基准上，使用领先的MoE基础LRMs（DeepSeek-R1和Qwen3-235B）进行的实证评估表明，推理准确度、认知效率和跨领域泛化能力均得到了显著且一致的提升。至关重要的是，我们的轻量化方法在推理控制技术（如提示设计和解码约束）中表现远超现有方法，同时保留了模型的一般指令遵循能力。这些结果突显了强化认知专家作为提升先进推理模型中认知效率的有前途、实用且可解释的方向。

> Mixture-of-Experts (MoE) architectures within Large Reasoning Models (LRMs) have achieved impressive reasoning capabilities by selectively activating experts to facilitate structured cognitive processes. Despite notable advances, existing reasoning models often suffer from cognitive inefficiencies like overthinking and underthinking. To address these limitations, we introduce a novel inference-time steering methodology called Reinforcing Cognitive Experts (RICE), designed to improve reasoning performance without additional training or complex heuristics. Leveraging normalized Pointwise Mutual Information (nPMI), we systematically identify specialized experts, termed ''cognitive experts'' that orchestrate meta-level reasoning operations characterized by tokens like ''<think>''. Empirical evaluations with leading MoE-based LRMs (DeepSeek-R1 and Qwen3-235B) on rigorous quantitative and scientific reasoning benchmarks demonstrate noticeable and consistent improvements in reasoning accuracy, cognitive efficiency, and cross-domain generalization. Crucially, our lightweight approach substantially outperforms prevalent reasoning-steering techniques, such as prompt design and decoding constraints, while preserving the model's general instruction-following skills. These results highlight reinforcing cognitive experts as a promising, practical, and interpretable direction to enhance cognitive efficiency within advanced reasoning models.

[Arxiv](https://arxiv.org/abs/2505.14681)