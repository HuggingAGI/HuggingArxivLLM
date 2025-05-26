# # 大型语言模型的多标签分类表现有何不同？

发布时间：2025年05月23日

`LLM应用

理由：这篇论文探讨了大型语言模型在多标签分类任务中的行为，特别是自回归模型在主观任务中的表现。研究分析了模型在生成过程中的输出分布，发现模型倾向于抑制其他标签，只生成一个标签，并观察到随着模型规模增加，token分布的熵降低，但标签排序有所改善。此外，论文还提出了分布对齐任务的方法，以提升模型的性能。这些内容都属于大型语言模型在具体任务中的应用和优化，因此归类为LLM应用。` `机器学习`

> Large Language Models Do Multi-Label Classification Differently

# 摘要

> 多标签分类在现实场景中广泛存在，但大型语言模型（LLMs）在这一场景中的行为研究尚不充分。我们研究了自回归LLMs在多标签分类任务中的表现，特别是主观任务，通过分析模型在每一步生成过程中的输出分布。我们发现，模型的预测行为反映了生成所有相关标签所需的多步语言建模过程，因为它们倾向于在每一步抑制除一个标签以外的所有标签。我们进一步观察到，随着模型规模的增加，其token分布的熵降低，但标签的内部排序却有所改善。监督微调和强化学习等微调方法会放大这一现象。为了进一步研究这一问题，我们引入了多标签场景下的分布对齐任务：将LLM生成的标签分布与从主观任务中注释者响应估计的经验分布对齐。我们提出了零样本和监督两种方法，与现有方法相比，这些方法在对齐和预测性能方面都有所提升。

> Multi-label classification is prevalent in real-world settings, but the behavior of Large Language Models (LLMs) in this setting is understudied. We investigate how autoregressive LLMs perform multi-label classification, with a focus on subjective tasks, by analyzing the output distributions of the models in each generation step. We find that their predictive behavior reflects the multiple steps in the underlying language modeling required to generate all relevant labels as they tend to suppress all but one label at each step. We further observe that as model scale increases, their token distributions exhibit lower entropy, yet the internal ranking of the labels improves. Finetuning methods such as supervised finetuning and reinforcement learning amplify this phenomenon. To further study this issue, we introduce the task of distribution alignment for multi-label settings: aligning LLM-derived label distributions with empirical distributions estimated from annotator responses in subjective tasks. We propose both zero-shot and supervised methods which improve both alignment and predictive performance over existing approaches.

[Arxiv](https://arxiv.org/abs/2505.17510)