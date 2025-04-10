# 基于样本级别遗忘难度，对大型语言模型遗忘现象的神经科学启发式解读

发布时间：2025年04月09日

`LLM理论` `隐私保护`

> A Neuro-inspired Interpretation of Unlearning in Large Language Models through Sample-level Unlearning Difficulty

# 摘要

> 隐私保护法规的推动下，大型语言模型（LLMs）的遗忘机制正受到越来越多的关注。然而，现有研究往往忽视了这一过程的可解释性，尤其是样本级别的遗忘难度。当前的研究通常假设所有样本的遗忘难度相同，这种简化可能导致我们将遗忘算法的表现归因于样本选择，而非算法设计，这可能会将LLM遗忘机制的发展引向错误的方向。因此，我们研究了LLM遗忘机制与样本特征之间的关系，重点在于遗忘难度。受神经科学的启发，我们提出了一种记忆移除难度（$\mathrm{MRD}$）指标，用于量化样本级别的遗忘难度。通过$\mathrm{MRD}$，我们分析了难以遗忘与容易遗忘样本的特征。此外，我们提出了一种基于$\mathrm{MRD}$的加权采样方法，以优化现有的遗忘算法，该方法优先考虑容易遗忘的样本，从而提高遗忘效率和效果。我们通过公共基准和数据集验证了所提出的指标和方法，结果证实了其有效性。

> Driven by privacy protection laws and regulations, unlearning in Large Language Models (LLMs) is gaining increasing attention. However, current research often neglects the interpretability of the unlearning process, particularly concerning sample-level unlearning difficulty. Existing studies typically assume a uniform unlearning difficulty across samples. This simplification risks attributing the performance of unlearning algorithms to sample selection rather than the algorithm's design, potentially steering the development of LLM unlearning in the wrong direction. Thus, we investigate the relationship between LLM unlearning and sample characteristics, with a focus on unlearning difficulty. Drawing inspiration from neuroscience, we propose a Memory Removal Difficulty ($\mathrm{MRD}$) metric to quantify sample-level unlearning difficulty. Using $\mathrm{MRD}$, we analyze the characteristics of hard-to-unlearn versus easy-to-unlearn samples. Furthermore, we propose an $\mathrm{MRD}$-based weighted sampling method to optimize existing unlearning algorithms, which prioritizes easily forgettable samples, thereby improving unlearning efficiency and effectiveness. We validate the proposed metric and method using public benchmarks and datasets, with results confirming its effectiveness.

[Arxiv](https://arxiv.org/abs/2504.06658)