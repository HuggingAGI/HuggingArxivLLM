# 跨越动态感知差距：无训练的思维链草案实现动态多模态空间推理

发布时间：2025年05月22日

`LLM应用` `动态空间推理` `多模态模型`

> Bridging the Dynamic Perception Gap: Training-Free Draft Chain-of-Thought for Dynamic Multimodal Spatial Reasoning

# 摘要

> 尽管思维链（CoT）在多模态大型语言模型（MLLMs）中的复杂推理方面取得了进展，但现有方法仍局限于文本或静态视觉领域，在动态空间推理任务中往往表现不佳。为了解决这一问题，我们提出了GRASSLAND，这是一个全新的迷宫导航基准，旨在评估动态空间推理能力。我们的实验表明，通过在输入图像上叠加动态视觉草图来增强文本推理链，显著优于传统方法，为动态环境中空间推理提供了新的见解。为了推广这一能力，我们提出了D2R（Dynamic Draft-Augmented Reasoning），一个无需训练的框架，能够将文本CoT与其对应的视觉草图无缝集成到MLLMs中。大量评估表明，D2R在各种任务中始终提升性能，为动态空间推理建立了强大的基准，而无需进行模型微调。项目已开源，地址为https://github.com/Cratileo/D2R。

> While chains-of-thought (CoT) have advanced complex reasoning in multimodal large language models (MLLMs), existing methods remain confined to text or static visual domains, often faltering in dynamic spatial reasoning tasks. To bridge this gap, we present GRASSLAND, a novel maze navigation benchmark designed to evaluate dynamic spatial reasoning. Our experiments show that augmenting textual reasoning chains with dynamic visual drafts, overlaid on input images, significantly outperforms conventional approaches, offering new insights into spatial reasoning in evolving environments. To generalize this capability, we propose D2R (Dynamic Draft-Augmented Reasoning), a training-free framework that seamlessly integrates textual CoT with corresponding visual drafts into MLLMs. Extensive evaluations demonstrate that D2R consistently enhances performance across diverse tasks, establishing a robust baseline for dynamic spatial reasoning without requiring model fine-tuning. Project is open at https://github.com/Cratileo/D2R.

[Arxiv](https://arxiv.org/abs/2505.16579)