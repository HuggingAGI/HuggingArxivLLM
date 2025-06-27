# # mTSBench: 多变量时间序列异常检测与模型选择的规模化评估

发布时间：2025年06月26日

`LLM应用` `工业监控`

> mTSBench: Benchmarking Multivariate Time Series Anomaly Detection and Model Selection at Scale

# 摘要

> 多元时间序列异常检测（MTS-AD）在医疗、网络安全和工业监控等领域至关重要，但因变量间复杂依赖关系、时间动态性和稀疏异常标签而仍然具有挑战性。我们引入了mTSBench，这是迄今为止最大的MTS-AD和无监督模型选择基准，覆盖19个数据集和12个不同应用领域，共计344个标注时间序列。mTSBench评估了24种异常检测方法，包括用于多元时间序列的大型语言模型（LLM）检测器，并在标准化条件下系统性基准测试无监督模型选择技术。与先前研究一致，我们的结果证实了单一检测器无法在所有数据集上都表现优异，突显了模型选择的重要性。然而，即使是最先进的选择方法仍远非最优，揭示了关键差距。mTSBench提供了一个统一的评估套件，支持严谨、可复现的对比，并推动自适应异常检测和稳健模型选择的未来发展。

> Multivariate time series anomaly detection (MTS-AD) is critical in domains like healthcare, cybersecurity, and industrial monitoring, yet remains challenging due to complex inter-variable dependencies, temporal dynamics, and sparse anomaly labels. We introduce mTSBench, the largest benchmark to date for MTS-AD and unsupervised model selection, spanning 344 labeled time series across 19 datasets and 12 diverse application domains. mTSBench evaluates 24 anomaly detection methods, including large language model (LLM)-based detectors for multivariate time series, and systematically benchmarks unsupervised model selection techniques under standardized conditions. Consistent with prior findings, our results confirm that no single detector excels across datasets, underscoring the importance of model selection. However, even state-of-the-art selection methods remain far from optimal, revealing critical gaps. mTSBench provides a unified evaluation suite to enable rigorous, reproducible comparisons and catalyze future advances in adaptive anomaly detection and robust model selection.

[Arxiv](https://arxiv.org/abs/2506.21550)