# STADE：基于标准差的剪枝指标

发布时间：2025年03月28日

`LLM理论` `机器学习` `模型优化`

> STADE: Standard Deviation as a Pruning Metric

# 摘要

> # 摘要
大型语言模型（LLMs）近期广泛应用，能够处理各类任务。然而，为确保任务成功，LLMs需要更长的训练时间和更大的模型规模。这使得它们成为理想的研究对象，用于探索既能减少计算需求又不损失性能的剪枝方法。传统剪枝方法需在剪枝后重新训练以维持原模型性能，而最新剪枝方法如Wanda无需重新训练，使剪枝过程更高效。基于Wanda的研究，本研究不仅揭示了其有效性背后的理论依据，还据此优化了剪枝流程。理论分析表明，在机器学习中常见的场景下，Wanda是最优剪枝方法。进一步研究扩展到Wanda不再适用的场景，由此基于输入标准差开发出新方法STADE。STADE在理论上展现出更强的通用性。实验结果表明，在Llama和OPT模型上，Wanda的性能随训练条件变化，与理论预测一致。这些发现为理解剪枝策略及其实际应用提供了重要启示。代码已开源，可在GitHub上获取：https://github.com/Coello-dev/STADE/

> Recently, Large Language Models (LLMs) have become very widespread and are used to solve a wide variety of tasks. To successfully handle these tasks, LLMs require longer training times and larger model sizes. This makes LLMs ideal candidates for pruning methods that reduce computational demands while maintaining performance. Previous methods require a retraining phase after pruning to maintain the original model's performance. However, state-of-the-art pruning methods, such as Wanda, prune the model without retraining, making the pruning process faster and more efficient. Building upon Wanda's work, this study provides a theoretical explanation of why the method is effective and leverages these insights to enhance the pruning process. Specifically, a theoretical analysis of the pruning problem reveals a common scenario in Machine Learning where Wanda is the optimal pruning method. Furthermore, this analysis is extended to cases where Wanda is no longer optimal, leading to the development of a new method, STADE, based on the standard deviation of the input. From a theoretical standpoint, STADE demonstrates better generality across different scenarios. Finally, extensive experiments on Llama and Open Pre-trained Transformers (OPT) models validate these theoretical findings, showing that depending on the training conditions, Wanda's optimal performance varies as predicted by the theoretical framework. These insights contribute to a more robust understanding of pruning strategies and their practical implications. Code is available at: https://github.com/Coello-dev/STADE/

[Arxiv](https://arxiv.org/abs/2503.22451)