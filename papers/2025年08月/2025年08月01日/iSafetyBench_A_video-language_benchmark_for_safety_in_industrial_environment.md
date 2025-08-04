# iSafetyBench: 视频语言基准用于工业安全评估

发布时间：2025年08月01日

`其他`

> iSafetyBench: A video-language benchmark for safety in industrial environment

# 摘要

> 近期视觉语言模型（VLMs）在零样本设置下展现出了跨多样化视频理解任务的卓越泛化能力。然而，这些模型在高风险工业领域中的表现——特别是在识别常规操作和安全关键异常方面——仍待深入探索。为此，我们推出了iSafetyBench，这是一个全新的视频语言基准测试，专注于评估模型在工业环境中的表现，涵盖正常与危险场景。iSafetyBench包含1,100个来自真实工业环境的视频片段，标注了开放词汇表、多标签的动作标签，覆盖98个常规操作类别和67个危险动作类别。每个视频片段都配有多项选择题，支持单标签和多标签评估，从而能够细致评估VLMs在标准和安全关键场景下的表现。我们在零样本条件下评估了八种最先进的视频语言模型。尽管这些模型在现有视频基准测试中表现优异，但在iSafetyBench上却面临挑战，尤其是在识别危险活动和多标签场景方面。我们的研究结果揭示了显著的性能差距，凸显了开发更强大、安全感知的多模态模型在工业应用中的迫切需求。iSafetyBench为推动这一领域的进展提供了一个开创性的测试平台。数据集可访问：https://github.com/raiyaan-abdullah/iSafety-Bench。

> Recent advances in vision-language models (VLMs) have enabled impressive generalization across diverse video understanding tasks under zero-shot settings. However, their capabilities in high-stakes industrial domains-where recognizing both routine operations and safety-critical anomalies is essential-remain largely underexplored. To address this gap, we introduce iSafetyBench, a new video-language benchmark specifically designed to evaluate model performance in industrial environments across both normal and hazardous scenarios. iSafetyBench comprises 1,100 video clips sourced from real-world industrial settings, annotated with open-vocabulary, multi-label action tags spanning 98 routine and 67 hazardous action categories. Each clip is paired with multiple-choice questions for both single-label and multi-label evaluation, enabling fine-grained assessment of VLMs in both standard and safety-critical contexts. We evaluate eight state-of-the-art video-language models under zero-shot conditions. Despite their strong performance on existing video benchmarks, these models struggle with iSafetyBench-particularly in recognizing hazardous activities and in multi-label scenarios. Our results reveal significant performance gaps, underscoring the need for more robust, safety-aware multimodal models for industrial applications. iSafetyBench provides a first-of-its-kind testbed to drive progress in this direction. The dataset is available at: https://github.com/raiyaan-abdullah/iSafety-Bench.

[Arxiv](https://arxiv.org/abs/2508.00399)