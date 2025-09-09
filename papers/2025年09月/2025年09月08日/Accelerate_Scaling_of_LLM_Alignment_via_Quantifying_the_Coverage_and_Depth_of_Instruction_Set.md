# 通过量化指令集的覆盖度与深度加速大型语言模型对齐的规模化

发布时间：2025年09月08日

`LLM应用` `基础理论`

> Accelerate Scaling of LLM Alignment via Quantifying the Coverage and Depth of Instruction Set

# 摘要

> 随着大型语言模型在下游任务中应用需求的不断增加，提升模型的对齐性能与效率已成为关键。这一过程需要从候选指令池中筛选出信息量大的指令。但由于指令集分布复杂，影响对齐模型性能的关键因素至今尚不明确。因此，随着指令池持续扩大，现有的指令集优化方法已难以提升性能。为解决这一问题，我们首先探究了影响指令数据集分布与对齐模型性能关联的关键因素。基于这些发现，我们提出了一种全新的指令数据选择方法。研究发现，指令深度和语义空间覆盖率是决定下游性能的核心因素，这两个因素可解释开发集上超过70%的模型损失。随后，我们设计了一种指令选择算法，可同时最大化所选指令的深度和语义覆盖率。实验结果显示，与当前最先进的基线方法相比，该方法能以更快速度持续提升模型性能，进而实现“加速扩展”。

> With the growing demand for applying large language models to downstream tasks, improving model alignment performance and efficiency has become crucial. Such a process involves selecting informative instructions from a candidate pool. However, due to the complexity of instruction set distributions, the key factors driving the performance of aligned models remain unclear. As a result, current instruction set refinement methods fail to improve performance as the instruction pool expands continuously. To address this issue, we first investigate the key factors that influence the relationship between instruction dataset distribution and aligned model performance. Based on these insights, we propose a novel instruction data selection method. We identify that the depth of instructions and the coverage of the semantic space are the crucial factors determining downstream performance, which could explain over 70\% of the model loss on the development set. We then design an instruction selection algorithm to simultaneously maximize the depth and semantic coverage of the selected instructions. Experimental results demonstrate that, compared to state-of-the-art baseline methods, it can sustainably improve model performance at a faster pace and thus achieve \emph{``Accelerated Scaling''}.

[Arxiv](https://arxiv.org/abs/2509.06463)