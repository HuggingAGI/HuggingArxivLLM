# 不同的问题，不同的模型：利用大型语言模型对临床问答的不确定性和校准进行细致评估

发布时间：2025年06月12日

`LLM应用`

> Different Questions, Different Models: Fine-Grained Evaluation of Uncertainty and Calibration in Clinical QA with LLMs

# 摘要

> 准确且经过良好校准的不确定性估计，对于在临床决策支持等高风险领域部署大型语言模型（LLMs）至关重要。本研究对临床多选题回答的不确定性估计方法进行了精细评估，涵盖两个数据集、十种开源LLM（包括通用型、生物医学型和推理型模型）、十一门医学专科以及六种问题类型。我们对比了标准单次生成和基于采样的方法，并通过案例研究探索了基于推理轨迹中行为信号的简单单次通过估计器。这些轻量级方法在仅需一次生成的情况下，达到了语义熵的性能水平。我们的研究结果揭示了不同专科和问题类型之间的显著差异，强调了根据问题特性和模型特定优势选择模型的重要性。

> Accurate and well-calibrated uncertainty estimates are essential for deploying large language models (LLMs) in high-stakes domains such as clinical decision support. We present a fine-grained evaluation of uncertainty estimation methods for clinical multiple-choice question answering, covering ten open-source LLMs (general-purpose, biomedical, and reasoning models) across two datasets, eleven medical specialties, and six question types. We compare standard single-generation and sampling-based methods, and present a case study exploring simple, single-pass estimators based on behavioral signals in reasoning traces. These lightweight methods approach the performance of Semantic Entropy while requiring only one generation. Our results reveal substantial variation across specialties and question types, underscoring the importance of selecting models based on both the nature of the question and model-specific strengths.

[Arxiv](https://arxiv.org/abs/2506.10769)