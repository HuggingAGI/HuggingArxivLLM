# 降本不降准：LLM驱动的可靠数据处理

发布时间：2025年09月02日

`LLM应用` `基础理论`

> Cut Costs, Not Accuracy: LLM-Powered Data Processing with Guarantees

# 摘要

> 大型语言模型（LLMs）如今在数据系统中越来越多地扮演基石角色，用于处理海量文本数据集。为此，LLM提供商推出了多款不同规模的模型，在大规模文本处理场景中形成了成本与质量的多重权衡。顶级LLMs（如GPT-4o、Claude Sonnet）虽准确率高，但处理大量数据时成本高昂，难以负担。为控制成本，可选用更经济但精度稍低的LLMs（如GPT-4o-mini、Claude Haiku）处理数据，但需确保整体准确性与顶级模型相差不大。模型级联框架为此类权衡提供了解决方案，它借助LLMs对输出的置信度（如对数概率）来判断哪些数据应使用经济型LLM处理。但现有基于该框架的方案成本节省效果有限，理论保障也较弱，根源在于对经济型LLM输出质量的估计精度不足。为此，我们提出BARGAIN方法——一种在数据处理中灵活运用经济型LLMs的策略，既能大幅削减成本，又能为结果质量提供坚实的理论保障。BARGAIN创新地结合了自适应采样策略与统计估计流程，它充分利用数据和任务特性，依托前沿统计工具实现精准估计，且具备严密的理论支撑。BARGAIN的不同变体还能分别保障输出的准确性、精确率或召回率。在8个真实数据集上的实验显示，BARGAIN相比现有最优方法平均可多降低86%的成本，同时为输出准确性提供更强的理论保障；在保证目标精确率或召回率时，也能实现相近的性能提升。

> Large Language Models (LLMs) are being increasingly used as a building block in data systems to process large text datasets. To do so, LLM model providers offer multiple LLMs with different sizes, spanning various cost-quality trade-offs when processing text at scale. Top-of-the-line LLMs (e.g., GPT-4o, Claude Sonnet) operate with high accuracy but are prohibitively expensive when processing many records. To avoid high costs, more affordable but lower quality LLMs (e.g., GPT-4o-mini, Claude Haiku) can be used to process records, but we need to ensure that the overall accuracy does not deviate substantially from that of the top-of-the-line LLMs. The model cascade framework provides a blueprint to manage this trade-off, by using the confidence of LLMs in their output (e.g., log-probabilities) to decide on which records to use the affordable LLM. However, existing solutions following this framework provide only marginal cost savings and weak theoretical guarantees because of poor estimation of the quality of the affordable LLM's outputs. We present BARGAIN, a method that judiciously uses affordable LLMs in data processing to significantly reduce cost while providing strong theoretical guarantees on the solution quality. BARGAIN employs a novel adaptive sampling strategy and statistical estimation procedure that uses data and task characteristics and builds on recent statistical tools to make accurate estimations with tight theoretical guarantees. Variants of BARGAIN can support guarantees on accuracy, precision, or recall of the output. Experimental results across 8 real-world datasets show that BARGAIN reduces cost, on average, by up to 86% more than state-of-the-art, while providing stronger theoretical guarantees on accuracy of output, with similar gains when guaranteeing a desired level of precision or recall.

[Arxiv](https://arxiv.org/abs/2509.02896)