# # 影响
大型语言模型生成标注中的标签噪声对诊断模型性能评估的影响

发布时间：2025年06月08日

`LLM应用` `人工智能`

> Impact of Label Noise from Large Language Models Generated Annotations on Evaluation of Diagnostic Model Performance

# 摘要

> 大型语言模型（LLMs）正越来越多地被用于从放射科报告中生成标签，以支持大规模AI评估。然而，LLMs生成的标签噪声可能会对性能评估引入偏差，尤其是在疾病患病率和模型质量变化的情况下。本研究量化了LLM标注错误对下游诊断模型评估的影响。

我们开发了一个仿真框架，用于评估LLM标签错误如何影响观察到的模型性能。在不同患病率水平下生成了包含10,000个病例的合成数据集。LLM的灵敏度和特异性分别在90%到100%之间独立变化。我们模拟了灵敏度和特异性在90%到100%之间的诊断模型。使用LLM生成的标签作为参考计算观察性能。我们推导了分析性能边界，并在每种条件下运行了5,000次蒙特卡罗试验以估计经验不确定性。

观察到的性能对LLM标签质量高度敏感，偏差强烈受患病率影响。在低患病率设置中，LLM特异性的小幅下降会导致灵敏度的严重低估。例如，在10%患病率下，特异性为95%的LLM会导致观察灵敏度约为53%，即使模型完美。在高患病率场景中，LLM灵敏度的降低会导致模型特异性的低估。蒙特卡罗模拟始终显示出向下偏差，观察性能经常低于真实值，即使在理论边界内。

LLM生成的标签可能会在模型评估中引入系统性、患病率相关的偏差。在低患病率任务中，特异性更为关键，而在高患病率设置中，灵敏度占据主导地位。这些发现强调了在临床AI中使用LLMs进行部署后模型评估时，设计考虑患病率的提示和错误特征化的重要性。

> Large language models (LLMs) are increasingly used to generate labels from radiology reports to enable large-scale AI evaluation. However, label noise from LLMs can introduce bias into performance estimates, especially under varying disease prevalence and model quality. This study quantifies how LLM labeling errors impact downstream diagnostic model evaluation. We developed a simulation framework to assess how LLM label errors affect observed model performance. A synthetic dataset of 10,000 cases was generated across different prevalence levels. LLM sensitivity and specificity were varied independently between 90% and 100%. We simulated diagnostic models with true sensitivity and specificity ranging from 90% to 100%. Observed performance was computed using LLM-generated labels as the reference. We derived analytical performance bounds and ran 5,000 Monte Carlo trials per condition to estimate empirical uncertainty. Observed performance was highly sensitive to LLM label quality, with bias strongly influenced by disease prevalence. In low-prevalence settings, small reductions in LLM specificity led to substantial underestimation of sensitivity. For example, at 10% prevalence, an LLM with 95% specificity yielded an observed sensitivity of ~53% despite a perfect model. In high-prevalence scenarios, reduced LLM sensitivity caused underestimation of model specificity. Monte Carlo simulations consistently revealed downward bias, with observed performance often falling below true values even when within theoretical bounds. LLM-generated labels can introduce systematic, prevalence-dependent bias into model evaluation. Specificity is more critical in low-prevalence tasks, while sensitivity dominates in high-prevalence settings. These findings highlight the importance of prevalence-aware prompt design and error characterization when using LLMs for post-deployment model assessment in clinical AI.

[Arxiv](https://arxiv.org/abs/2506.07273)