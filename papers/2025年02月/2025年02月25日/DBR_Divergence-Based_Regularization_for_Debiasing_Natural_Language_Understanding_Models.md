# DBR：基于分歧的正则化方法，用于去除自然语言理解模型中的偏见

发布时间：2025年02月25日

`LLM理论` `模型优化`

> DBR: Divergence-Based Regularization for Debiasing Natural Language Understanding Models

# 摘要

> 预训练语言模型（PLMs）在各类自然语言处理任务中取得了引人注目的成绩。然而，最新研究表明，这些模型往往过分依赖表面特征和捷径，而非真正理解语言，这一问题在自然语言理解（NLU）任务中尤为突出。因此，模型在处理域外数据时常常表现欠佳。针对这一问题，我们提出了一种基于差异的正则化方法（DBR），旨在减少模型对捷径学习的依赖。我们的方法通过测量原始示例与遮蔽捷径词的示例之间的输出分布差异，有效防止模型预测被捷径特征或偏见过度影响。我们在三个NLU任务上对模型进行了全面评估，发现它在域外性能上取得了显著提升，同时仅轻微影响了域内准确性。这一研究结果表明，减少对捷径和表面特征的依赖，可以显著提升大型预训练语言模型的泛化能力。

> Pre-trained language models (PLMs) have achieved impressive results on various natural language processing tasks. However, recent research has revealed that these models often rely on superficial features and shortcuts instead of developing a genuine understanding of language, especially for natural language understanding (NLU) tasks. Consequently, the models struggle to generalize to out-of-domain data. In this work, we propose Divergence Based Regularization (DBR) to mitigate this shortcut learning behavior. Our method measures the divergence between the output distributions for original examples and examples where shortcut tokens have been masked. This process prevents the model's predictions from being overly influenced by shortcut features or biases. We evaluate our model on three NLU tasks and find that it improves out-of-domain performance with little loss of in-domain accuracy. Our results demonstrate that reducing the reliance on shortcuts and superficial features can enhance the generalization ability of large pre-trained language models.

[Arxiv](https://arxiv.org/abs/2502.18353)