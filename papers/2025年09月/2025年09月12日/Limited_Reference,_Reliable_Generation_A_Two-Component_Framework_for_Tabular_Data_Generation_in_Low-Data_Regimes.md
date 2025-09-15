# 参考有限，生成可靠：面向低数据场景表格数据生成的双组件框架

发布时间：2025年09月12日

`LLM应用` `基础理论`

> Limited Reference, Reliable Generation: A Two-Component Framework for Tabular Data Generation in Low-Data Regimes

# 摘要

> 合成表格数据生成在数据管理领域愈发关键，尤其在现实世界高质量表格数据稀缺时，可为下游应用提供支撑。现有的表格生成方法（如生成对抗网络（GANs）、扩散模型和微调大型语言模型（LLMs））通常依赖充足的参考数据，这使其在记录稀缺的特定领域数据库中效果受限。尽管基于提示的LLMs无需参数调优即可灵活使用，但它们往往难以捕捉特定数据集的特征-标签依赖关系，还会生成冗余数据，进而导致下游任务性能降低。为解决这些问题，我们提出ReFine框架，其核心机制包括：（i）从可解释模型中提取符号化的“如果-那么”规则并嵌入提示，明确引导生成符合特定领域特征分布的数据；（ii）采用双粒度过滤策略，抑制过采样模式，同时选择性优化稀有但信息丰富的样本，以缓解分布不平衡。在多种回归和分类基准数据集上的大量实验显示，ReFine持续优于当前最先进的方法，在回归任务中R平方值绝对提升最高达0.44，在分类任务中F1分数相对提升10.0%。

> Synthetic tabular data generation is increasingly essential in data management, supporting downstream applications when real-world and high-quality tabular data is insufficient. Existing tabular generation approaches, such as generative adversarial networks (GANs), diffusion models, and fine-tuned Large Language Models (LLMs), typically require sufficient reference data, limiting their effectiveness in domain-specific databases with scarce records. While prompt-based LLMs offer flexibility without parameter tuning, they often fail to capture dataset-specific feature-label dependencies and generate redundant data, leading to degradation in downstream task performance. To overcome these issues, we propose ReFine, a framework that (i) derives symbolic "if-then" rules from interpretable models and embeds them into prompts to explicitly guide generation toward domain-specific feature distribution, and (ii) applies a dual-granularity filtering strategy that suppresses over-sampling patterns and selectively refines rare but informative samples to reduce distributional imbalance. Extensive experiments on various regression and classification benchmarks demonstrate that ReFine consistently outperforms state-of-the-art methods, achieving up to 0.44 absolute improvement in R-squared for regression and 10.0 percent relative improvement in F1 score for classification tasks.

[Arxiv](https://arxiv.org/abs/2509.09960)