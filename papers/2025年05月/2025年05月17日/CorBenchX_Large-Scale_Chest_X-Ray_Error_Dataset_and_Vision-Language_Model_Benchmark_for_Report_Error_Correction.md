# CorBenchX: 大规模胸部X光错误数据集与视觉语言模型基准测试（用于报告错误修正）

发布时间：2025年05月17日

`LLM应用` `放射学`

> CorBenchX: Large-Scale Chest X-Ray Error Dataset and Vision-Language Model Benchmark for Report Error Correction

# 摘要

> AI驱动的模型在检测放射学报告中的错误方面表现出巨大潜力，但该领域尚未建立统一的评估基准来严格测试错误检测与修正效果。为填补这一空白，我们推出CorBenchX，一个专为胸部X光报告设计的自动错误检测与修正工具包，旨在提升临床实践中AI辅助的质量控制水平。我们通过向DeepSeek-R1注入常见临床错误，构建了一个包含26,326份胸部X光错误报告的大型数据集，每份错误报告均附带原始文本、错误类型及详细说明。基于此数据集，我们在零样本提示模式下对开源与闭源视觉语言模型（如InternVL、Qwen-VL、GPT-4o、o4-mini和Claude-3.7）进行了全面测试。结果显示，o4-mini表现最优，检测准确率达到50.6%，修正质量指标包括BLEU 0.853、ROUGE 0.924、BERTScore 0.981、SembScore 0.865和CheXbertF1 0.954，但仍未能达到临床标准，凸显了精准报告修正的难度。为推动技术进步，我们提出了一种多步骤强化学习（MSRL）框架，通过优化结合格式合规性、错误类型准确性和BLEU相似性的多目标奖励函数，显著提升了模型性能。将其应用于我们在基准测试中表现最佳的开源模型QwenVL2.5-7B，结果显示单个错误检测精度提升了38.3%，修正效果提升了5.2%，较零样本基线有明显改善。

> AI-driven models have shown great promise in detecting errors in radiology reports, yet the field lacks a unified benchmark for rigorous evaluation of error detection and further correction. To address this gap, we introduce CorBenchX, a comprehensive suite for automated error detection and correction in chest X-ray reports, designed to advance AI-assisted quality control in clinical practice. We first synthesize a large-scale dataset of 26,326 chest X-ray error reports by injecting clinically common errors via prompting DeepSeek-R1, with each corrupted report paired with its original text, error type, and human-readable description. Leveraging this dataset, we benchmark both open- and closed-source vision-language models,(e.g., InternVL, Qwen-VL, GPT-4o, o4-mini, and Claude-3.7) for error detection and correction under zero-shot prompting. Among these models, o4-mini achieves the best performance, with 50.6 % detection accuracy and correction scores of BLEU 0.853, ROUGE 0.924, BERTScore 0.981, SembScore 0.865, and CheXbertF1 0.954, remaining below clinical-level accuracy, highlighting the challenge of precise report correction. To advance the state of the art, we propose a multi-step reinforcement learning (MSRL) framework that optimizes a multi-objective reward combining format compliance, error-type accuracy, and BLEU similarity. We apply MSRL to QwenVL2.5-7B, the top open-source model in our benchmark, achieving an improvement of 38.3% in single-error detection precision and 5.2% in single-error correction over the zero-shot baseline.

[Arxiv](https://arxiv.org/abs/2505.12057)