# URSA: 多模态数学中的思维链推理理解与验证

发布时间：2025年01月08日

`LLM应用

理由：这篇论文主要讨论了如何通过改进链式思维（CoT）推理来提升大型语言模型（LLMs）在多模态数学推理中的性能。论文提出了一种三模块合成策略来生成高质量的CoT推理指令微调数据集，并通过实验验证了模型在多模态数学基准上的性能提升。这些内容主要涉及如何应用和改进LLMs来解决具体问题，因此属于LLM应用范畴。`

> URSA: Understanding and Verifying Chain-of-thought Reasoning in Multimodal Mathematics

# 摘要

> # 摘要
链式思维（CoT）推理在大型语言模型（LLMs）的数学推理中得到了广泛应用。最近，CoT轨迹的衍生过程监督引发了关于测试时扩展能力的讨论，进一步提升了模型的潜力。然而，多模态数学推理中高质量CoT训练数据的稀缺，限制了现有模型的高精度推理和测试时的潜力发挥。为此，我们提出了一种三模块合成策略，结合CoT蒸馏、轨迹格式重写和格式统一，生成了高质量的多模态数学CoT推理指令微调数据集MMathCoT-1M。我们全面验证了URSA-7B模型在多个多模态数学基准上的SOTA性能。针对测试时的扩展，我们引入了一种数据合成策略，自动生成专注于解释和逻辑的过程注释数据集DualMath-1.1M。通过在DualMath-1.1M上进一步训练URSA-7B，我们将其从CoT推理能力提升为强大的监督能力。训练后的URSA-RM-7B作为验证器，显著提升了URSA-7B在测试时的性能，并展示了出色的分布外（OOD）验证能力，体现了其强大的泛化能力。模型权重、训练数据和代码将开源。

> Chain-of-thought (CoT) reasoning has been widely applied in the mathematical reasoning of Large Language Models (LLMs). Recently, the introduction of derivative process supervision on CoT trajectories has sparked discussions on enhancing scaling capabilities during test time, thereby boosting the potential of these models. However, in multimodal mathematical reasoning, the scarcity of high-quality CoT training data has hindered existing models from achieving high-precision CoT reasoning and has limited the realization of reasoning potential during test time. In this work, we propose a three-module synthesis strategy that integrates CoT distillation, trajectory-format rewriting, and format unification. It results in a high-quality CoT reasoning instruction fine-tuning dataset in multimodal mathematics, MMathCoT-1M. We comprehensively validate the state-of-the-art (SOTA) performance of the trained URSA-7B model on multiple multimodal mathematical benchmarks. For test-time scaling, we introduce a data synthesis strategy that automatically generates process annotation datasets, known as DualMath-1.1M, focusing on both interpretation and logic. By further training URSA-7B on DualMath-1.1M, we transition from CoT reasoning capabilities to robust supervision abilities. The trained URSA-RM-7B acts as a verifier, effectively enhancing the performance of URSA-7B at test time. URSA-RM-7B also demonstrates excellent out-of-distribution (OOD) verifying capabilities, showcasing its generalization. Model weights, training data and code will be open-sourced.

[Arxiv](https://arxiv.org/abs/2501.04686)