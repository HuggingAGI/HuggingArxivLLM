# LLM 中知识与推理的分离：基于认知双系统理论的探索

发布时间：2025年07月24日

`LLM理论` `人工智能` `模型分析`

> Decoupling Knowledge and Reasoning in LLMs: An Exploration Using Cognitive Dual-System Theory

# 摘要

> 大型语言模型（LLMs）在推理过程中同时依赖知识和推理能力，但区分这两者的能力对模型分析、解释性和开发至关重要。受双系统认知理论启发，我们提出了一种认知归因框架，旨在分离知识和推理的贡献。具体而言，我们将LLMs的认知过程分解为两个既独立又互补的阶段：知识检索（阶段1）和推理调整（阶段2）。为了区分这两个阶段，我们引导LLMs在两种不同的认知模式下生成答案：快速思维和慢速思维。通过分析不同认知模式下的表现，我们量化了知识和推理的贡献。这一架构被应用于3个数据集上的15个LLMs。研究结果揭示：（1）推理调整具有领域特定性，对推理密集型领域（如数学、物理和化学）有益，但可能对知识密集型领域产生负面影响。（2）参数扩展提升了知识和推理能力，其中知识的提升更为显著。此外，参数扩展使LLMs的推理更加谨慎，同时在某种程度上更加智能。（3）知识主要存在于网络的较低层，而推理则在较高层运行。我们的框架不仅有助于从“解耦”的视角理解LLMs，还为现有研究提供了新的见解，包括缩放定律、分层知识编辑以及小型模型推理的局限性。

> While large language models (LLMs) leverage both knowledge and reasoning during inference, the capacity to distinguish between them plays a pivotal role in model analysis, interpretability, and development. Inspired by dual-system cognitive theory, we propose a cognition attribution framework to decouple the contribution of knowledge and reasoning. In particular, the cognition of LLMs is decomposed into two distinct yet complementary phases: knowledge retrieval (Phase 1) and reasoning adjustment (Phase 2). To separate these phases, LLMs are prompted to generate answers under two different cognitive modes, fast thinking and slow thinking, respectively. The performance under different cognitive modes is analyzed to quantify the contribution of knowledge and reasoning. This architecture is employed to 15 LLMs across 3 datasets. Results reveal: (1) reasoning adjustment is domain-specific, benefiting reasoning-intensive domains (e.g., mathematics, physics, and chemistry) and potentially imparing knowledge-intensive domains. (2) Parameter scaling improves both knowledge and reasoning, with knowledge improvements being more pronounced. Additionally, parameter scaling make LLMs reasoning significantly more prudent, while moderately more intelligent. (3) Knowledge primarily resides in lower network layers, while reasoning operates in higher layers. Our framework not only helps understand LLMs from a "decoupling" perspective, but also provides new insights into existing research, including scaling laws, hierarchical knowledge editing, and limitations of small-model reasoning.

[Arxiv](https://arxiv.org/abs/2507.18178)