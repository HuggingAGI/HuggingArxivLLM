# 一适万变，随基更新：可迁移的参数高效微调方法

发布时间：2025年06月07日

`LLM应用

理由：这篇论文讨论了大语言模型微调方法（PEFT）在模型更新后的性能问题，并提出了改进方法Trans-PEFT。它关注的是如何在实际应用中优化模型维护，属于应用层面的改进，因此归类为LLM应用。`

> Adapt Once, Thrive with Updates: Transferable Parameter-Efficient Fine-Tuning on Evolving Base Models

# 摘要

> 参数高效微调（PEFT）已成为大语言模型微调的常见方法，基础模型通过切换PEFT模块可服务于多个用户。为了提升用户体验，基础模型需要定期更新。然而，更新后，之前版本上微调的PEFT模块在新版本上通常会面临显著性能下降。重新微调这些模块以恢复性能将产生巨大计算成本。通过对基础模型更新过程中发生的变化进行综合分析，我们发现：持续训练主要影响前馈网络（FFN）中存储的任务特定知识，而对注意力机制中的任务特定模式影响较小。基于此发现，我们提出了Trans-PEFT，这是一种专注于任务特定模式并减少对基础模型中某些知识依赖的增强PEFT模块的新方法。理论分析支持了我们的方法。在7个基础模型和12个数据集上的广泛实验表明，Trans-PEFT训练的模块可以在更新后的基础模型上保持性能，无需重新微调，从而大幅降低了实际应用中的维护开销。

> Parameter-efficient fine-tuning (PEFT) has become a common method for fine-tuning large language models, where a base model can serve multiple users through PEFT module switching. To enhance user experience, base models require periodic updates. However, once updated, PEFT modules fine-tuned on previous versions often suffer substantial performance degradation on newer versions. Re-tuning these numerous modules to restore performance would incur significant computational costs. Through a comprehensive analysis of the changes that occur during base model updates, we uncover an interesting phenomenon: continual training primarily affects task-specific knowledge stored in Feed-Forward Networks (FFN), while having less impact on the task-specific pattern in the Attention mechanism. Based on these findings, we introduce Trans-PEFT, a novel approach that enhances the PEFT module by focusing on the task-specific pattern while reducing its dependence on certain knowledge in the base model. Further theoretical analysis supports our approach. Extensive experiments across 7 base models and 12 datasets demonstrate that Trans-PEFT trained modules can maintain performance on updated base models without re-tuning, significantly reducing maintenance overhead in real-world applications.

[Arxiv](https://arxiv.org/abs/2506.06844)