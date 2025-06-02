# 你的模型真的公平且确定吗？感知不确定性的大型语言模型公平性评估

发布时间：2025年05月29日

`LLM理论

理由：这篇论文探讨了大型语言模型的公平性评估，提出了一种新的不确定性感知公平性指标，并引入了一个新的数据集来评估模型的公平性。这些研究属于对大型语言模型本身的理论分析和改进，因此应归类为LLM理论。` `人工智能伦理` `社会学`

> Is Your Model Fairly Certain? Uncertainty-Aware Fairness Evaluation for LLMs

# 摘要

> 大型语言模型（LLMs）的广泛应用凸显了对其公平性进行评估的迫切需求。传统的公平性指标主要关注预测准确性，但忽略了模型不确定性带来的潜在影响。例如，模型可能对某一特定群体表现出更高置信度，即使准确率相似。为解决这一问题，我们提出了一种新型的不确定性感知公平性指标UCerF，它能更细致地评估模型公平性，更能反映模型决策中的内在偏见。此外，针对现有数据集在数据量、多样性和清晰度方面的问题，我们引入了一个包含31,756个样本的新型性别-职业公平性评估数据集，专门用于共指消解任务，为评估现代LLMs提供了更加多样和合适的数据支持。我们利用这一指标和数据集建立了一个基准，并将其应用于评估十款开源LLMs的行为。例如，Mistral-7B由于在错误预测中表现出过高置信度而公平性欠佳，这一细节被传统指标Equalized Odds忽视，却为UCerF所捕获。总体而言，我们提出的考虑不确定性意识的LLM公平性基准测试，为开发更加透明和可问责的AI系统铺平了道路。

> The recent rapid adoption of large language models (LLMs) highlights the critical need for benchmarking their fairness. Conventional fairness metrics, which focus on discrete accuracy-based evaluations (i.e., prediction correctness), fail to capture the implicit impact of model uncertainty (e.g., higher model confidence about one group over another despite similar accuracy). To address this limitation, we propose an uncertainty-aware fairness metric, UCerF, to enable a fine-grained evaluation of model fairness that is more reflective of the internal bias in model decisions compared to conventional fairness measures. Furthermore, observing data size, diversity, and clarity issues in current datasets, we introduce a new gender-occupation fairness evaluation dataset with 31,756 samples for co-reference resolution, offering a more diverse and suitable dataset for evaluating modern LLMs. We establish a benchmark, using our metric and dataset, and apply it to evaluate the behavior of ten open-source LLMs. For example, Mistral-7B exhibits suboptimal fairness due to high confidence in incorrect predictions, a detail overlooked by Equalized Odds but captured by UCerF. Overall, our proposed LLM benchmark, which evaluates fairness with uncertainty awareness, paves the way for developing more transparent and accountable AI systems.

[Arxiv](https://arxiv.org/abs/2505.23996)