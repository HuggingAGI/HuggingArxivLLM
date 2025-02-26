# 蒙特卡洛温度：针对大语言模型不确定性量化方法的稳健采样策略

发布时间：2025年02月25日

`LLM理论` `人工智能` `机器学习`

> Monte Carlo Temperature: a robust sampling strategy for LLM's uncertainty quantification methods

# 摘要

> 大型语言模型（LLMs）中的不确定性量化（UQ）对于确保其在关键应用中的安全可靠部署至关重要，尤其是在错误输出可能导致严重后果的场景中。当前的UQ方法通常依赖于通过非零温度采样多次查询模型，以生成多样化的输出用于不确定性估计。然而，选择特定温度参数的影响研究不足，我们的分析表明，温度在不确定性估计的质量中起着根本性作用。传统方法通过昂贵的超参数优化（HPO）来识别最优温度值，且必须为每个新的模型-数据集组合重复这一过程。我们提出了蒙特卡罗温度（MCT），这是一种无需温度校准的鲁棒采样策略。我们的分析揭示了以下几点：1）MCT在广泛的温度范围内提供更稳健的不确定性估计，2）MCT通过替代不依赖HPO的固定温度策略，显著提升了UQ方法的性能，3）MCT在统计上与理想校准的温度（即经过良好调优但计算昂贵的HPO过程的输出）持平。这些发现表明，无需承担温度参数校准的计算负担，即可实现有效的UQ。

> Uncertainty quantification (UQ) in Large Language Models (LLMs) is essential for their safe and reliable deployment, particularly in critical applications where incorrect outputs can have serious consequences. Current UQ methods typically rely on querying the model multiple times using non-zero temperature sampling to generate diverse outputs for uncertainty estimation. However, the impact of selecting a given temperature parameter is understudied, and our analysis reveals that temperature plays a fundamental role in the quality of uncertainty estimates. The conventional approach of identifying optimal temperature values requires expensive hyperparameter optimization (HPO) that must be repeated for each new model-dataset combination. We propose Monte Carlo Temperature (MCT), a robust sampling strategy that eliminates the need for temperature calibration. Our analysis reveals that: 1) MCT provides more robust uncertainty estimates across a wide range of temperatures, 2) MCT improves the performance of UQ methods by replacing fixed-temperature strategies that do not rely on HPO, and 3) MCT achieves statistical parity with oracle temperatures, which represent the ideal outcome of a well-tuned but computationally expensive HPO process. These findings demonstrate that effective UQ can be achieved without the computational burden of temperature parameter calibration.

[Arxiv](https://arxiv.org/abs/2502.18389)