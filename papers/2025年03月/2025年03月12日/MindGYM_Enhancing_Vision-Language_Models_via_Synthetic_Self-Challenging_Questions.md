# MindGYM：利用合成自我挑战问题提升视觉-语言模型性能

发布时间：2025年03月12日

`LLM理论` `计算机视觉`

> MindGYM: Enhancing Vision-Language Models via Synthetic Self-Challenging Questions

# 摘要

> 大型视觉语言模型（VLMs）在实现稳健且可迁移的推理能力方面面临挑战，主要由于依赖于劳动密集型的手动指令数据集或计算成本高昂的自监督方法。为了解决这些问题，我们引入了MindGYM框架，通过合成的自我挑战问题来增强VLMs，该框架包含三个阶段：

1. **种子单跳问题合成**：生成涵盖文本（如逻辑推理）和多模态上下文（如基于图表的查询）的八种语义领域（如伦理分析）的认知问题；
2. **挑战性多跳问题合成**：通过多样化的原则（如桥接、视觉-文本对齐）将种子问题结合，创建需要更深入推理的多步骤问题；
3. **思维诱导课程微调**：一个结构化的训练管道，逐步从支架推理到独立推理训练模型。

通过利用模型的自我合成能力，MindGYM实现了高效的数据利用（例如，在仅400个样本的情况下，MathVision-Mini的性能提升+16%），计算效率（降低了训练和推理成本），以及跨任务的鲁棒泛化能力。在七个基准测试中的广泛评估显示，MindGYM在强大的基线模型上表现出色，通过GPT-based评分验证了推理深度和广度的显著提升（+15.77%胜率）。MindGYM证明了通过自我挑战提升VLM能力的可行性，同时减少了人为干预和资源需求。代码和数据已公开，以推动多模态推理研究的发展。

> Large vision-language models (VLMs) face challenges in achieving robust, transferable reasoning abilities due to reliance on labor-intensive manual instruction datasets or computationally expensive self-supervised methods. To address these issues, we introduce MindGYM, a framework that enhances VLMs through synthetic self-challenging questions, consisting of three stages: (1) Seed Single-Hop Question Synthesis, generating cognitive questions across textual (e.g., logical deduction) and multimodal contexts (e.g., diagram-based queries) spanning eight semantic areas like ethical analysis; (2) Challenging Multi-Hop Question Synthesis, combining seed questions via diverse principles like bridging, visual-textual alignment, to create multi-step problems demanding deeper reasoning; and (3) Thinking-Induced Curriculum Fine-Tuning, a structured pipeline that progressively trains the model from scaffolded reasoning to standalone inference. By leveraging the model's self-synthesis capability, MindGYM achieves high data efficiency (e.g., +16% gains on MathVision-Mini with only 400 samples), computational efficiency (reducing both training and inference costs), and robust generalization across tasks. Extensive evaluations on seven benchmarks demonstrate superior performance over strong baselines, with notable improvements (+15.77% win rates) in reasoning depth and breadth validated via GPT-based scoring. MindGYM underscores the viability of self-challenging for refining VLM capabilities while minimizing human intervention and resource demands. Code and data are released to advance multimodal reasoning research.

[Arxiv](https://arxiv.org/abs/2503.09499)