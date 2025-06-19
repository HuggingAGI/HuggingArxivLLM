# 大型语言模型中词嵌入学习率的最优值：词汇量的影响

发布时间：2025年06月17日

`LLM理论` `人工智能` `机器学习`

> Optimal Embedding Learning Rate in LLMs: The Effect of Vocabulary Size

# 摘要

> 预训练大型语言模型成本高昂。为了提高效率，已有多种方法被提出，用于优化模型架构、参数化和硬件使用。在参数化方面，$μP$通过一种使超参数可随宽度转移的方式对模型权重和学习率进行参数化：超参数可以在小模型上进行调整，并直接用于更大模型，无需额外调参。尽管$μP$在实践中表现出色，但近期针对大型语言模型的实证研究表明，其应用结果存在相互矛盾的观察。$μP$理论的一个局限性在于，当宽度趋近于无穷大时，输入维度（即词汇量大小）被视为固定值。这一假设并不现实，因为实际应用中词汇量通常远大于宽度。在本研究中，我们对词汇量大小对训练动态的影响进行了理论分析，并证明，随着词汇量的增加，训练动态会在$μP$模式和另一种我们称之为“大词汇量”（LV）模式之间进行插值，其中最优缩放规则与$μP$的预测结果有所不同。我们的分析揭示，在LV模式下，最优嵌入LR与隐藏LR的比例应大致按$Θ(\sqrt{width})$的速率缩放，这一结果令人惊讶地接近文献中先前报告的实证发现，与$μP$预测的$Θ(width)$比例有所不同。我们进行了多项实验以验证我们的理论，并从头预训练了一个10亿参数规模的模型，以展示我们建议的嵌入LR缩放规则带来的优势。


> Pretraining large language models is a costly process. To make this process more efficient, several methods have been proposed to optimize model architecture/parametrization and hardware use. On the parametrization side, $μP$ (Maximal Update Parametrization) parametrizes model weights and learning rate (LR) in a way that makes hyperparameters (HPs) transferable with width (embedding dimension): HPs can be tuned for a small model and used for larger models without additional tuning. While $μ$P showed impressive results in practice, recent empirical studies have reported conflicting observations when applied to LLMs. One limitation of the theory behind $μ$P is the fact that input dimension (vocabulary size in LLMs) is considered fixed when taking the width to infinity. This is unrealistic since vocabulary size is generally much larger than width in practice. In this work, we provide a theoretical analysis of the effect of vocabulary size on training dynamics, and subsequently show that as vocabulary size increases, the training dynamics \emph{interpolate between the $μ$P regime and another regime that we call Large Vocab (LV) Regime}, where optimal scaling rules are different from those predicted by $μ$P. Our analysis reveals that in the LV regime, the optimal embedding LR to hidden LR ratio should roughly scale as $Θ(\sqrt{width})$, surprisingly close to the empirical findings previously reported in the literature, and different from the $Θ(width)$ ratio predicted by $μ$P. We conduct several experiments to validate our theory, and pretrain a 1B model from scratch to show the benefit of our suggested scaling rule for the embedding LR.

[Arxiv](https://arxiv.org/abs/2506.15025)