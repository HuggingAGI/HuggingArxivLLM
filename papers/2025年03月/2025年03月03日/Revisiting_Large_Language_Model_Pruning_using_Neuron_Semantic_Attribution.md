# 基于神经元语义归属的大型语言模型剪枝方法再探

发布时间：2025年03月03日

`LLM应用` `模型剪枝`

> Revisiting Large Language Model Pruning using Neuron Semantic Attribution

# 摘要

> 模型剪枝技术是加速大型语言模型的关键，因为它通过精简模型规模和计算需求来实现目标。然而，现有剪枝方法在不同数据集和任务上的泛化能力仍有待验证。为此，我们使用流行的剪枝方法对24个数据集和4个任务进行了全面评估。基于评估结果，我们发现校准集对剪枝方法的性能影响显著。此外，我们惊讶地发现现有剪枝方法在情感分类任务中的性能出现了显著下降。为了探究性能下降与被剪枝神经元之间的联系，我们提出了神经元语义归属方法，该方法能够将每个神经元与特定语义相关联。此方法首先使大型语言模型中未被剪枝的神经元具有可解释性。

> Model pruning technique is vital for accelerating large language models by reducing their size and computational requirements. However, the generalizability of existing pruning methods across diverse datasets and tasks remains unclear. Thus, we conduct extensive evaluations on 24 datasets and 4 tasks using popular pruning methods. Based on these evaluations, we find and then investigate that calibration set greatly affect the performance of pruning methods. In addition, we surprisingly find a significant performance drop of existing pruning methods in sentiment classification tasks. To understand the link between performance drop and pruned neurons, we propose Neuron Semantic Attribution, which learns to associate each neuron with specific semantics. This method first makes the unpruned neurons of LLMs explainable.

[Arxiv](https://arxiv.org/abs/2503.01542)