# TinyHelen的首课：在简化语言环境中训练与评估小型语言模型

发布时间：2024年12月31日

`LLM理论

理由：这篇论文主要讨论了如何通过简化语言环境来提升语言模型（LMs）的学习效率，并提出了一个优化文本数据的流程。论文的核心在于通过减少数据集的噪声和复杂性，同时保留基本的文本分布特征，来创建更精简的训练和评估数据集。这些方法旨在提高语言模型的学习效率，并减少训练和评估所需的资源。因此，这篇论文主要涉及语言模型的理论和方法改进，属于LLM理论范畴。` `机器学习`

> TinyHelen's First Curriculum: Training and Evaluating Tiny Language Models in a Simpler Language Environment

# 摘要

> 训练语言模型（LMs）及其应用代理的成本日益增加，主要由于大型数据集和模型的存在，使得测试失败的成本难以承受。简化的语言环境作为基础训练和测试平台，保留了基本的常识和沟通技能，但以更易消化的形式呈现，可能提升LMs的学习效率，从而减少有效训练和评估所需的模型大小和数据量。在这些简化环境中，适用于小型模型、数据集和代理的策略可能同样适用于复杂语言环境中的大型模型、数据集和代理。
    为了构建这样的环境，我们聚焦于两个方面：i）最小化语言数据集的噪声和复杂性，ii）保留基本的文本分布特征。与以往方法不同，我们提出了一种通过消除噪声、精简词汇并保持特定类型模式（如书籍、对话、代码等）来优化文本数据的流程。通过使用大型LMs实施这一流程，我们创建了一套更精简的LM训练和评估数据集：71M Leaner-Pretrain、7M Leaner-Instruct、用于评估语言能力的Leaner-Glue，以及用于测试指令遵循能力的Leaner-Eval。
    实验结果显示，精简的预训练显著提高了LM的学习效率。在这些数据集上训练的微型LMs在不同语言粒度级别的指令遵循任务中表现优于在原始数据集上训练的LMs。此外，Leaner-Pretrain数据集与传统大型LM训练集的对齐使得资源优化的分析成为可能，这些分析涉及学习目标、模型架构和训练技术如何影响语言建模和下游任务的性能。我们的代码和数据集可在https://github.com/EmpathYang/TinyHelen.git获取。

> Training language models (LMs) and their application agents is increasingly costly due to large datasets and models, making test failures difficult to bear. Simplified language environments serve as primordial training and testing grounds, retaining essential commonsense and communication skills but in a more digestible form, potentially enhancing the learning efficiency of LMs, and thus reducing the required model size and data volume for effective training and evaluation. In these simplified language environments, workable strategies for small models, datasets, and agents may be adaptable to larger models, datasets, and agents in complex language environments.
  To create such environments, we focus on two aspects: i) minimizing language dataset noise and complexity, and ii) preserving the essential text distribution characteristics. Unlike previous methods, we propose a pipeline to refine text data by eliminating noise, minimizing vocabulary, and maintaining genre-specific patterns (e.g., for books, conversation, code, etc.). Implementing this pipeline with large LMs, we have created a leaner suite of LM training and evaluation datasets: 71M Leaner-Pretrain, 7M Leaner-Instruct, Leaner-Glue for assessing linguistic proficiency, and Leaner-Eval for testing instruction-following ability.
  Our experiments show that leaner pre-training boosts LM learning efficiency. Tiny LMs trained on these datasets outperform those trained on original datasets in instruction-following across different language granularity levels. Moreover, the Leaner-Pretrain dataset's alignment with conventional large LM training sets enables resource-optimized analysis of how learning objectives, model architectures, and training techniques impact performance on language modeling and downstream tasks. Our code and datasets are available at https://github.com/EmpathYang/TinyHelen.git.

[Arxiv](https://arxiv.org/abs/2501.00522)