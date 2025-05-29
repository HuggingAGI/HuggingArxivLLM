# 通过扰动表示稳定性探测，实现对LLM置信度的精准校准

发布时间：2025年05月27日

`LLM理论` `人工智能`

> Calibrating LLM Confidence by Probing Perturbed Representation Stability

# 摘要

> 大型语言模型 (LLMs) 中的校准偏差削弱了其可靠性，准确估计其置信度变得尤为重要。我们提出了一种名为 CCPS（通过探查扰动表示稳定性来校准 LLM 置信度）的新方法，专注于分析 LLM 的内部表示稳定性。CCPS 通过在最终隐藏状态上施加有针对性的对抗扰动，提取模型对这些扰动响应的特征，并利用轻量级分类器预测答案的正确性。我们在涵盖 Llama、Qwen 和 Mistral 架构的 8B 到 32B 参数规模的 LLM 上，使用 MMLU 和 MMLU-Pro 基准测试（包括多选和开放格式）对 CCPS 进行了全面评估。结果显示，CCPS 在多个关键指标上显著优于现有方法。具体而言，与最强的先前方法相比，CCPS 将预期校准误差降低了约 55%，布里尔分数降低了 21%，同时将准确率提高了 5 个百分点，精确率-召回率曲线下面积提高了 4 个百分点，接收者操作特征曲线下面积提高了 6 个百分点。CCPS 为 LLM 的置信度估计提供了一种高效、广泛应用且更精准的解决方案，从而显著提升了其可信度。

> Miscalibration in Large Language Models (LLMs) undermines their reliability, highlighting the need for accurate confidence estimation. We introduce CCPS (Calibrating LLM Confidence by Probing Perturbed Representation Stability), a novel method analyzing internal representational stability in LLMs. CCPS applies targeted adversarial perturbations to final hidden states, extracts features reflecting the model's response to these perturbations, and uses a lightweight classifier to predict answer correctness. CCPS was evaluated on LLMs from 8B to 32B parameters (covering Llama, Qwen, and Mistral architectures) using MMLU and MMLU-Pro benchmarks in both multiple-choice and open-ended formats. Our results show that CCPS significantly outperforms current approaches. Across four LLMs and three MMLU variants, CCPS reduces Expected Calibration Error by approximately 55% and Brier score by 21%, while increasing accuracy by 5 percentage points, Area Under the Precision-Recall Curve by 4 percentage points, and Area Under the Receiver Operating Characteristic Curve by 6 percentage points, all relative to the strongest prior method. CCPS delivers an efficient, broadly applicable, and more accurate solution for estimating LLM confidence, thereby improving their trustworthiness.

[Arxiv](https://arxiv.org/abs/2505.21772)