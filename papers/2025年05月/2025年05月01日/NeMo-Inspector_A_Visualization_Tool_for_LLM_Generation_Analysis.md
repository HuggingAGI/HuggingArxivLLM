# NeMo-Inspector：探索 LLM 生成机制的可视化工具

发布时间：2025年05月01日

`LLM应用` `数据生成` `数据清洗`

> NeMo-Inspector: A Visualization Tool for LLM Generation Analysis

# 摘要

> 将大型语言模型（LLMs）应用于新任务并提升其能力，通常需要大量高质量的训练数据。在现实数据稀缺时，合成数据成为宝贵替代方案。然而，确保合成数据质量颇具挑战，需要手动检查大量样本，耗时且依赖专业工具。我们推出NeMo-Inspector，一个开源工具，通过集成推理功能简化合成数据集分析。实际案例展示了其有效性：使用NeMo-Inspector清洗GSM-Plus数据集，低质量样本比例从46.99%降至19.51%。该工具还帮助修正OpenMath模型的生成错误，使Meta-Llama-3-8B模型在MATH数据集上准确率提升1.92%，在GSM8K数据集上提升4.17%。

> Adapting Large Language Models (LLMs) to novel tasks and enhancing their overall capabilities often requires large, high-quality training datasets. Synthetic data, generated at scale, serves a valuable alternative when real-world data is scarce or difficult to obtain. However, ensuring the quality of synthetic datasets is challenging, as developers must manually inspect and refine numerous samples to identify errors and areas for improvement. This process is time-consuming and requires specialized tools. We introduce NeMo-Inspector, an open-source tool designed to simplify the analysis of synthetic datasets with integrated inference capabilities. We demonstrate its effectiveness through two real-world cases. Analysis and cleaning of the synthetically generated GSM-Plus dataset with NeMo-Inspector led to a significant decrease in low-quality samples from 46.99% to 19.51%. The tool also helped identify and correct generation errors in OpenMath models, improving accuracy by 1.92% on the MATH dataset and by 4.17% on the GSM8K dataset for a Meta-Llama-3-8B model fine-tuned on synthetic data generated from Nemotron-4-340B.

[Arxiv](https://arxiv.org/abs/2505.00903)