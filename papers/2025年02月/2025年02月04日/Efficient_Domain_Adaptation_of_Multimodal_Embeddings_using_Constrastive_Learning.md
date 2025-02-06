# 基于对比学习的多模态嵌入高效领域适应

发布时间：2025年02月04日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）和视觉模型的冻结嵌入，通过对比学习训练一个小的、任务特定的非线性投影，从而在资源受限的环境中实现高效的下游任务应用。这属于LLM在实际应用中的优化和使用，因此归类为LLM应用。` `机器学习`

> Efficient Domain Adaptation of Multimodal Embeddings using Constrastive Learning

# 摘要

> # 摘要
近年来，机器学习（ML）、自然语言处理（NLP）和基础模型的突破在医疗等计算资源受限的关键领域展现了实际应用的潜力。在这些领域，结合基础模型与监督式机器学习，有望实现诊断和治疗计划等任务的自动化。然而，现场计算资源的有限性在有效应用这些技术之前带来了重大挑战：当前方法要么在使用未经任务特定调整的预训练模型时表现不佳，要么需要大量计算资源进行微调，这在这些环境中往往是一个进入壁垒。这使得它们在性能和质量标准高但计算资源稀缺的应用中难以实现。为了弥合最佳性能和可访问性之间的差距，我们提出了一种新颖的方法，用于将基础的多模态嵌入适应下游任务，而无需昂贵的微调过程。我们的方法利用大型语言模型（LLMs）和视觉模型的冻结嵌入，并通过对比学习训练一个小的、任务特定的非线性投影，该投影可用于下游任务，而无需微调原始基础模型。我们展示了这种高效的方法在各种下游任务中带来了显著的性能提升，更重要的是，计算开销极小，为在资源受限的环境中使用先进的基础ML模型提供了实用的解决方案。

> Recent advancements in machine learning (ML), natural language processing (NLP), and foundational models have shown promise for real-life applications in critical, albeit compute-constrainted fields like healthcare.
  In such areas, combining foundational models with supervised ML offers potential for automating tasks like diagnosis and treatment planning, but the limited availability of onsite computational resources pose significant challenges before applying these technologies effectively: Current approaches either yield subpar results when using pretrained models without task-specific adaptation, or require substantial computational resources for fine-tuning, which is often a barrier to entry in such environments.
  This renders them inaccessible in applications where performance and quality standards are high, but computational resources are scarce.
  To bridge the gap between best-in-class performance and accessibility, we propose a novel method for adapting foundational, multimodal embeddings to downstream tasks, without the need of expensive fine-tuning processes.
  Our method leverages frozen embeddings from Large Language Models (LLMs) and Vision Models, and uses contrastive learning to train a small, task-specific nonlinear projection that can be used in the downstream task, without having to fine-tune the original foundational models.
  We show that this efficient procedure leads to significant performance improvements across various downstream tasks, and perhaps more importantly with minimal computational overhead, offering a practical solution for the use of advanced, foundational ML models in resource-constrained settings.

[Arxiv](https://arxiv.org/abs/2502.02048)