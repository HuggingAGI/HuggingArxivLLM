# 如何在 LLM 预训练中发现 Grokking？无需测试，实时追踪记忆到泛化的转变。

发布时间：2025年06月26日

`LLM理论` `人工智能`

> Where to find Grokking in LLM Pretraining? Monitor Memorization-to-Generalization without Test

# 摘要

> Grokking现象，即训练损失收敛后测试性能仍持续提升，最近在神经网络训练中被观察到，使得模型的泛化机制及推理等新兴能力充满神秘感。虽然以往研究通常在少量玩具任务或高度特定任务上训练小型模型，持续数千个 epochs，但我们首次在70亿参数大型语言模型（LLM）的一次性预训练中研究了Grokking现象，即OLMoE。我们在数学推理、代码生成及常识/领域特定知识检索等多样化基准任务上评估了模型的泛化能力。

本研究首次证实，尽管不同数据可能异步进入Grokking阶段，但Grokking现象仍然存在于大规模基础模型的预训练过程中。通过探究LLM的内部动态，我们揭示了Grokking“泛化能力的涌现”之谜。具体而言，训练样本的路径（即各层中专家选择的路径）在Grokking过程中从随机、特定实例逐渐演变为更具结构化且可在样本间共享的形式。尽管损失已收敛，单个样本路径的复杂度却有所降低。这些发现表明了从记忆向泛化的转换，为延迟泛化现象提供了机制解释。

在研究中，我们开发了两个新指标来量化路径距离和单个路径的复杂度。这些指标高效且易于计算，仅依赖于训练数据，因此在预训练过程中具有实用价值，使我们无需微调和测试即可监控泛化性能。从理论上讲，更结构化的路径降低了模型复杂度，改善了泛化界限。

> Grokking, i.e., test performance keeps improving long after training loss converged, has been recently witnessed in neural network training, making the mechanism of generalization and other emerging capabilities such as reasoning mysterious. While prior studies usually train small models on a few toy or highly-specific tasks for thousands of epochs, we conduct the first study of grokking on checkpoints during one-pass pretraining of a 7B large language model (LLM), i.e., OLMoE. We compute the training loss and evaluate generalization on diverse benchmark tasks, including math reasoning, code generation, and commonsense/domain-specific knowledge retrieval tasks.
  Our study, for the first time, verifies that grokking still happens in the pretraining of large-scale foundation models, though different data may enter grokking stages asynchronously. We further demystify grokking's "emergence of generalization" by investigating LLM internal dynamics. Specifically, we find that training samples' pathways (i.e., expert choices across layers) evolve from random, instance-specific to more structured and shareable between samples during grokking. Also, the complexity of a sample's pathway reduces despite the converged loss. These indicate a memorization-to-generalization conversion, providing a mechanistic explanation of delayed generalization. In the study, we develop two novel metrics to quantify pathway distance and the complexity of a single pathway. We show their ability to predict the generalization improvement on diverse downstream tasks. They are efficient, simple to compute and solely dependent on training data. Hence, they have practical value for pretraining, enabling us to monitor the generalization performance without finetuning and test. Theoretically, we show that more structured pathways reduce model complexity and improve the generalization bound.

[Arxiv](https://arxiv.org/abs/2506.21551)