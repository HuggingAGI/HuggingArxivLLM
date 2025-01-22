# 优化基于影响力的指令调优数据选择，促进多样化能力的均衡学习

发布时间：2025年01月21日

`LLM理论

理由：这篇论文主要讨论了如何通过改进训练数据选择方法来优化大型语言模型（LLMs）的指令微调过程。具体来说，论文提出了一种新的算法（BIDS）来解决现有方法在平衡多样化任务性能上的不足。这涉及到对训练数据的影响分数进行归一化处理，并通过迭代选择来优化数据平衡。这些内容属于对LLM训练和优化方法的理论研究，因此归类为“LLM理论”。` `机器学习` `数据选择`

> Improving Influence-based Instruction Tuning Data Selection for Balanced Learning of Diverse Capabilities

# 摘要

> 选择合适的训练数据对LLMs的指令微调至关重要，旨在（1）激发强大能力，（2）在多样化任务中实现平衡性能。基于影响的方法通过评估每个训练示例对模型预测的贡献，在（1）上表现出色，但在（2）上常显不足。我们发现，这种不足源于某些任务天生更具影响力，导致数据选择偏向这些任务，不仅损害其他任务的表现，甚至反噬高影响力任务本身。
    为此，我们提出BIDS算法，一种平衡且有影响力的数据选择方法。BIDS首先归一化训练数据的影响分数，然后迭代选择对最不具代表性任务影响最大的示例，实现数据平衡。在Llama-3和Mistral-v0.3上的七个基准测试中，BIDS在五种能力上均优于现有基于影响和非基于影响的算法。令人惊讶的是，使用BIDS选择的15%子集训练，性能甚至优于全数据集训练，且更加平衡。我们的分析进一步表明，实例级归一化和数据选择的迭代优化对多样化能力的平衡学习至关重要。

> Selecting appropriate training data is crucial for effective instruction fine-tuning of large language models (LLMs), which aims to (1) elicit strong capabilities, and (2) achieve balanced performance across a diverse range of tasks. Influence-based methods show promise in achieving (1) by estimating the contribution of each training example to the model's predictions, but often struggle with (2). Our systematic investigation reveals that this underperformance can be attributed to an inherent bias where certain tasks intrinsically have greater influence than others. As a result, data selection is often biased towards these tasks, not only hurting the model's performance on others but also, counterintuitively, harms performance on these high-influence tasks themselves.
  As a remedy, we propose BIDS, a Balanced and Influential Data Selection algorithm. BIDS first normalizes influence scores of the training data, and then iteratively balances data selection by choosing the training example with the highest influence on the most underrepresented task. Experiments with both Llama-3 and Mistral-v0.3 on seven benchmarks spanning five diverse capabilities show that BIDS consistently outperforms both state-of-the-art influence-based algorithms and other non-influence-based selection frameworks. Surprisingly, training on a 15% subset selected by BIDS can even outperform full-dataset training with a much more balanced performance. Our analysis further highlights the importance of both instance-level normalization and iterative optimization of selected data for balanced learning of diverse capabilities.

[Arxiv](https://arxiv.org/abs/2501.12147)