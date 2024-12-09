# MAmmoTH-VL：借助大规模指令调优激发多模态推理

发布时间：2024年12月06日

`LLM应用` `多模态` `语言模型`

> MAmmoTH-VL: Eliciting Multimodal Reasoning with Instruction Tuning at Scale

# 摘要

> 开源的多模态大型语言模型（MLLMs）在众多多模态任务里展现出极大的潜力。然而，现有的指令调优数据集主要从诸如 VQA、AI2D 和 ChartQA 等学术数据集复用而来，这限制了 MLLMs 的推理能力。这些数据集针对的是简单任务，仅提供短语级答案，没有任何中间推理依据。为应对这些挑战，我们引入了一种可扩展且经济高效的方法，构建一个具有丰富中间推理依据、旨在引发 CoT 推理的大规模多模态指令调优数据集。仅使用开源模型，我们创建了一个包含 1200 万个指令 - 响应对的数据集，涵盖了各类推理密集型任务，并提供了详尽且可靠的推理依据。实验表明，在该数据集上训练 MLLMs 显著提升了推理能力，在 MathVerse（+8.1%）、MMMU-Pro（+7%）和 MuirBench（+13.3%）等基准测试中达到了领先水平。此外，该模型在非推理型基准测试中的表现也有高达 4%的显著提升。消融研究进一步凸显了关键组件（如重写和自我过滤）在数据集构建过程中的重要性。

> Open-source multimodal large language models (MLLMs) have shown significant potential in a broad range of multimodal tasks. However, their reasoning capabilities remain constrained by existing instruction-tuning datasets, which were predominately repurposed from academic datasets such as VQA, AI2D, and ChartQA. These datasets target simplistic tasks, and only provide phrase-level answers without any intermediate rationales. To address these challenges, we introduce a scalable and cost-effective method to construct a large-scale multimodal instruction-tuning dataset with rich intermediate rationales designed to elicit CoT reasoning. Using only open models, we create a dataset containing 12M instruction-response pairs to cover diverse, reasoning-intensive tasks with detailed and faithful rationales. Experiments demonstrate that training MLLMs on this dataset significantly improves reasoning capabilities, achieving state-of-the-art performance on benchmarks such as MathVerse (+8.1%), MMMU-Pro (+7%), and MuirBench (+13.3%). Additionally, the model demonstrates notable improvements of up to 4% on non-reasoning-based benchmarks. Ablation studies further highlight the importance of key components, such as rewriting and self-filtering, in the dataset construction process.

[Arxiv](https://arxiv.org/abs/2412.05237)