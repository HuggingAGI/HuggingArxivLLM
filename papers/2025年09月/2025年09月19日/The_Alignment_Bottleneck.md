# # 对齐瓶颈

发布时间：2025年09月19日

`LLM理论` `基础理论`

> The Alignment Bottleneck

# 摘要

> 大型语言模型的性能随规模增长而提升，但基于反馈的对齐仍与预期行为存在系统性偏差。受经济学和认知科学中有限理性理论的启发，我们将判断视为资源有限的过程，将反馈视为受限的信息渠道。在此基础上，我们将该循环建模为在给定$S$的条件下，包含认知容量【数学公式】和平均总容量【数学公式】的两阶段级联【数学公式】。我们的主要成果是一个容量耦合的对齐性能区间，该区间将在可分离码本混合上证明的、与数据大小无关的Fano下界，与KL项通过【数学公式】由同一渠道控制的PAC-Bayes上界相结合。当使用标准可观测损失且数据集取自同一混合分布时，PAC-Bayes上界即成为同一真实风险的上界。在这些匹配条件下，两个界限均由单一容量主导。其推论包括：若价值复杂度和容量固定，仅增加标签无法突破该界限；针对更复杂目标实现更低风险，需容量随【数学公式】增长；一旦有用信号使容量饱和，进一步优化往往会拟合渠道规律，这与谄媚行为和奖励黑客的相关报告一致。该分析将对齐视为接口工程：测量并分配有限容量，管理任务复杂度，同时决定信息的投放位置。

> Large language models improve with scale, yet feedback-based alignment still exhibits systematic deviations from intended behavior. Motivated by bounded rationality in economics and cognitive science, we view judgment as resource-limited and feedback as a constrained channel. On this basis, we model the loop as a two-stage cascade $U \to H \to Y$ given $S$, with cognitive capacity $C_{\text{cog}|S}$ and average total capacity $\bar{C}_{\text{tot}|S}$. Our main result is a capacity-coupled Alignment Performance Interval. It pairs a data size-independent Fano lower bound proved on a separable codebook mixture with a PAC-Bayes upper bound whose KL term is controlled by the same channel via $m \, \bar{C}_{\text{tot}|S}$. The PAC-Bayes bound becomes an upper bound on the same true risk when the canonical observable loss is used and the dataset is drawn from the same mixture. Under these matched conditions, both limits are governed by a single capacity. Consequences include that, with value complexity and capacity fixed, adding labels alone cannot cross the bound; attaining lower risk on more complex targets requires capacity that grows with $\log M$; and once useful signal saturates capacity, further optimization tends to fit channel regularities, consistent with reports of sycophancy and reward hacking. The analysis views alignment as interface engineering: measure and allocate limited capacity, manage task complexity, and decide where information is spent.

[Arxiv](https://arxiv.org/abs/2509.15932)