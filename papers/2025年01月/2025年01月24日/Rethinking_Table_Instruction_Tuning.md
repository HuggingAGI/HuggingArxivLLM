# 表格指令微调的再思考

发布时间：2025年01月24日

`LLM应用

理由：这篇论文主要讨论了如何通过指令调优和超参数选择来提升大型语言模型（LLM）在表格理解任务中的表现，并提出了一个基于LLaMA的表格LLM（TAMA）。研究重点在于如何优化LLM在特定任务（表格理解）中的应用，并评估其在领域外和通用任务中的表现。因此，这篇论文属于LLM应用类别。` `表格理解`

> Rethinking Table Instruction Tuning

# 摘要

> # 摘要
近期表格理解领域的进展主要集中在为表格相关任务进行LLMs的指令调优。然而，现有研究忽略了超参数选择的影响，且缺乏对领域外表格理解能力和这些表格LLMs通用能力的全面评估。本文评估了现有表格LLMs的这些能力，发现与基础模型相比，领域外表格理解和通用能力显著下降。通过系统分析，我们发现超参数（如学习率）对表格特定能力和通用能力有显著影响。与现有研究不同，我们证明较小的学习率和较少的训练实例可以提升表格理解，同时保持通用能力。基于此，我们提出了TAMA，一个基于LLaMA 3.1 8B Instruct指令调优的表格LLM，其在表格任务上的表现与GPT-3.5和GPT-4相当甚至更优，同时具备强大的领域外泛化能力和通用能力。我们的研究揭示了通过精心选择超参数，可以降低数据注释成本并提升模型开发效率。

> Recent advances in table understanding have focused on instruction-tuning large language models (LLMs) for table-related tasks. However, existing research has overlooked the impact of hyperparameter choices and lacks a comprehensive evaluation of the out-of-domain table understanding ability and the general capabilities of these table LLMs. In this paper, we evaluate these abilities in existing table LLMs, and reveal significant declines in both out-of-domain table understanding and general capabilities compared to their base models. Through systematic analysis, we show that hyperparameters, such as learning rate, can significantly influence both table-specific and general capabilities. Contrary to the existing table instruction-tuning works, we demonstrate that smaller learning rates and fewer training instances can enhance table understanding while preserving general capabilities. Based on our findings, we introduce TAMA, a TAble LLM instruction-tuned from LLaMA 3.1 8B Instruct, which achieves performance on par with, or surpassing GPT-3.5 and GPT-4 on table tasks, while maintaining strong out-of-domain generalization and general capabilities. Our findings highlight the potential for reduced data annotation costs and more efficient model development through careful hyperparameter selection.

[Arxiv](https://arxiv.org/abs/2501.14693)