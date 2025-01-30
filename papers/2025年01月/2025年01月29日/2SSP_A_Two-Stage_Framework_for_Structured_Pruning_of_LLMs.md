# 2SSP: 大型语言模型结构化剪枝的两阶段框架

发布时间：2025年01月29日

`LLM理论

理由：这篇论文主要讨论了一种新颖的两阶段结构化剪枝框架（2SSP），用于剪枝大型语言模型（LLMs）。剪枝是一种优化模型的技术，属于模型压缩和优化的范畴，通常与模型的理论和结构相关。因此，这篇论文更适合归类为LLM理论，因为它涉及对LLM内部结构和性能的优化研究。` `机器学习`

> 2SSP: A Two-Stage Framework for Structured Pruning of LLMs

# 摘要

> 我们提出了一种新颖的两阶段结构化剪枝框架（2SSP），用于剪枝大型语言模型（LLMs），结合了宽度剪枝和深度剪枝两种策略。第一阶段（宽度剪枝）通过移除整个神经元及其对应的行和列，保留每个Transformer块中前馈网络中间状态的连接性，基于神经元对输出幅度的重要性评分。第二阶段（深度剪枝）则通过迭代过程移除对困惑度影响最小的注意力子模块。我们还提出了一种平衡两阶段稀疏率与全局稀疏率的机制。在四个LLM家族和三个稀疏率（25%、37.5%和50%）上测试2SSP，测量了三个语言建模数据集的困惑度和六个下游任务的性能。我们的方法在三个语言建模和六个下游任务上始终优于五个最先进的竞争对手，剪枝时间最多提高了两个数量级。代码可在url{https://github.com/FabrizioSandri/2SSP}获取。

> We propose a novel Two-Stage framework for Structured Pruning (2SSP) for pruning Large Language Models (LLMs), which combines two different strategies of pruning, namely Width and Depth Pruning. The first stage (Width Pruning) removes entire neurons, hence their corresponding rows and columns, aiming to preserve the connectivity among the pruned structures in the intermediate state of the Feed-Forward Networks in each Transformer block. This is done based on an importance score measuring the impact of each neuron over the output magnitude. The second stage (Depth Pruning), instead, removes entire Attention submodules. This is done by applying an iterative process that removes the Attention submodules with the minimum impact on a given metric of interest (in our case, perplexity). We also propose a novel mechanism to balance the sparsity rate of the two stages w.r.t. to the desired global sparsity. We test 2SSP on four LLM families and three sparsity rates (25\%, 37.5\%, and 50\%), measuring the resulting perplexity over three language modeling datasets as well as the performance over six downstream tasks. Our method consistently outperforms five state-of-the-art competitors over three language modeling and six downstream tasks, with an up to two-order-of-magnitude gain in terms of pruning time. The code is available at available at url{https://github.com/FabrizioSandri/2SSP}.

[Arxiv](https://arxiv.org/abs/2501.17771)