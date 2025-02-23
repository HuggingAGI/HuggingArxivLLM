# 发现与缓解知识编辑中的过度关注

发布时间：2025年02月20日

`LLM理论` `机器学习`

> Revealing and Mitigating Over-Attention in Knowledge Editing

# 摘要

> 大型语言模型在各类任务中展现出卓越能力，但因从训练数据中学习到的错误知识，仍会产生令人不快的失误。为解决这一问题，知识编辑方法应运而生，通过高效修改极小比例的参数，精准编辑模型的特定知识。然而，这些方法可能引发特异性失败：当与编辑知识相关的内容出现在上下文中时，可能无意中破坏其他已有知识。

我们的研究表明，特异性失败主要源于模型注意力头对编辑知识相关实体分配了过高的注意力分数，从而不当地专注于上下文中的特定片段，我们将其称为注意力漂移现象。为缓解这一问题，我们提出了一种简单而有效的方法：选择性注意力漂移限制（SADR）。该方法在知识编辑过程中引入额外的正则化项，限制注意力权重分布的变化，从而防止对编辑实体的过度关注。

在五个常用强大LLM上的实验验证了我们方法的有效性：SADR能够显著缓解主要知识编辑任务中的特异性失败问题。

> Large Language Models have demonstrated superior performance across a wide range of tasks, but they still exhibit undesirable errors due to incorrect knowledge learned from the training data. To avoid this, knowledge editing methods emerged to precisely edit the specific model knowledge via efficiently modifying a very small percentage of parameters. % However, those methods can lead to the problem of Specificity Failure: when the content related to the edited knowledge occurs in the context, it can inadvertently corrupt other pre-existing knowledge. However, those methods can lead to the problem of Specificity Failure, where the existing knowledge and capabilities are severely degraded due to editing. Our preliminary indicates that Specificity Failure primarily stems from the model's attention heads assigning excessive attention scores to entities related to the edited knowledge, thereby unduly focusing on specific snippets within the context, which we denote as the Attention Drift phenomenon. To mitigate such Attention Drift issue, we introduce a simple yet effective method Selective Attention Drift Restriction}(SADR), which introduces an additional regularization term during the knowledge editing process to restrict changes in the attention weight distribution, thereby preventing undue focus on the edited entity. Experiments on five frequently used strong LLMs demonstrate the effectiveness of our method, where SADR can significantly mitigate Specificity Failure in the predominant knowledge editing tasks.

[Arxiv](https://arxiv.org/abs/2502.14838)