# 探索不确定性：更多上下文示例能否帮助大型语言模型减少不确定性？

发布时间：2025年05月27日

`LLM理论` `人工智能` `机器学习`

> Uncertainty Unveiled: Can Exposure to More In-context Examples Mitigate Uncertainty for Large Language Models?

# 摘要

> 长序列处理技术的突破推动了长上下文在上下文学习（ICL）研究的发展。尽管现有研究多聚焦于额外上下文示例带来的性能提升，但对生成结果可信度的影响仍鲜有研究。本文针对这一研究空白，探讨了增加示例数量对预测不确定性的影响，这是决定可信度的关键因素。我们首先系统量化了不同示例数量下的ICL不确定性，深入分析了示例数量带来的影响。通过创新的不确定性分解方法，我们提出了性能提升的新研究视角，重点关注认识论不确定性（EU）。研究发现，额外示例通过注入任务特定知识，有效降低了简单和复杂任务中的总不确定性，从而减少了EU并显著提升了模型性能。值得注意的是，复杂任务中这些优势的显现需要克服更长输入带来的噪声和不确定性增加。最后，通过分析各层内部置信度的演变过程，我们揭示了导致不确定性降低的内在机制。

> Recent advances in handling long sequences have facilitated the exploration of long-context in-context learning (ICL). While much of the existing research emphasizes performance improvements driven by additional in-context examples, the influence on the trustworthiness of generated responses remains underexplored. This paper addresses this gap by investigating how increased examples influence predictive uncertainty, an essential aspect in trustworthiness. We begin by systematically quantifying the uncertainty of ICL with varying shot counts, analyzing the impact of example quantity. Through uncertainty decomposition, we introduce a novel perspective on performance enhancement, with a focus on epistemic uncertainty (EU). Our results reveal that additional examples reduce total uncertainty in both simple and complex tasks by injecting task-specific knowledge, thereby diminishing EU and enhancing performance. For complex tasks, these advantages emerge only after addressing the increased noise and uncertainty associated with longer inputs. Finally, we explore the evolution of internal confidence across layers, unveiling the mechanisms driving the reduction in uncertainty.

[Arxiv](https://arxiv.org/abs/2505.21003)