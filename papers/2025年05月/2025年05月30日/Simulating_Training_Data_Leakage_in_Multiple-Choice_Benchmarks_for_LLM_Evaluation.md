# 模拟训练数据泄露在多选题基准中的LLM评估

发布时间：2025年05月30日

`LLM理论` `模型评估` `数据泄漏检测`

> Simulating Training Data Leakage in Multiple-Choice Benchmarks for LLM Evaluation

# 摘要

> 大型语言模型 (LLMs) 的性能持续提升，这一点从其在标准基准测试中的分数上涨中可见一斑。然而，围绕训练数据的缺乏透明度引发了对潜在评估集重叠和报告结果公平性的担忧。尽管先前的研究提出了检测数据泄漏的方法，但这些方法主要集中在识别异常值，并未在受控的模拟泄漏条件下进行评估。在本研究中，我们对比了现有的泄漏检测技术，即置换法和n-gram基方法，在模拟真实世界泄漏场景的持续预训练设置下进行比较，并额外探索了一种名为半问法的轻量级方法。尽管半问法提供了一个低成本的替代方案，但我们的分析表明，n-gram方法始终实现了最高的F1分数。我们还优化了这些技术以支持实例级检测并降低计算开销。利用表现最佳的方法，我们创建了MMLU和HellaSwag的清理版本，并重新评估了多个LLMs。我们的发现为实现更可靠和透明的评估提供了一条实用路径，我们建议在发布基准结果前进行污染检查作为标准步骤。

> The performance of large language models (LLMs) continues to improve, as reflected in rising scores on standard benchmarks. However, the lack of transparency around training data raises concerns about potential overlap with evaluation sets and the fairness of reported results. Although prior work has proposed methods for detecting data leakage, these approaches primarily focus on identifying outliers and have not been evaluated under controlled simulated leakage conditions. In this work, we compare existing leakage detection techniques, namely permutation and n-gram-based methods, under a continual pretraining setup that simulates real-world leakage scenarios, and additionally explore a lightweight method we call semi-half question. Although semi-half offers a low-cost alternative, our analysis shows that the n-gram method consistently achieves the highest F1-score. We also refine these techniques to support instance-level detection and reduce computational overhead. Leveraging the best-performing method, we create cleaned versions of MMLU and HellaSwag, and re-evaluate several LLMs. Our findings present a practical path toward more reliable and transparent evaluations, and we recommend contamination checks as a standard step before releasing benchmark results.

[Arxiv](https://arxiv.org/abs/2505.24263)