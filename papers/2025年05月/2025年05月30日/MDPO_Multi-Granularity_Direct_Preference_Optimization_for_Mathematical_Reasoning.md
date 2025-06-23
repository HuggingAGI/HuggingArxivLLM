# MDPO：针对数学推理的多粒度直接偏好优化

发布时间：2025年05月30日

`LLM应用` `数学推理`

> MDPO: Multi-Granularity Direct Preference Optimization for Mathematical Reasoning

# 摘要

> 数学推理对大型语言模型（LLMs）来说是一个巨大挑战，因为它要求确保每一步推理的正确性。尽管研究人员通过监督微调增强了LLMs的数学推理能力，但由于无法有效抑制错误输出，幻觉现象仍然容易发生。最近，直接偏好优化（DPO）作为一种通过偏好数据对齐人类意图的方法，被广泛采用以防止LLMs生成错误输出。然而，在长链数学推理任务中，DPO显示出有限的改进效果，主要是因为DPO难以有效捕捉长链数据中被接受和被拒绝答案之间的差异。此外，DPO训练目标与LLMs生成指标之间的不一致也影响了抑制错误输出的效果。

我们提出了一种多粒度直接偏好优化（MDPO）方法，在Solution2Solution、Inference2Inference和Step2Step三个粒度上优化LLMs的数学推理能力。Solution2Solution关注整个长链推理的正确性；Inference2Inference关注步骤之间的逻辑推理；Step2Step则纠正步骤中的计算错误，从而提升LLMs的计算能力。此外，我们将三个粒度的训练目标统一，使其与生成指标保持一致。

我们在开源模型Qwen2和Llama3上进行了实验，在GSM8K数据集上分别取得了1.7%和0.9%的提升，在MATH数据集上分别取得了2.3%和1.2%的提升，优于DPO和其他DPO变体方法。此外，我们还提供了一种简单且无需人工标注成本的MDPO训练数据构建 pipeline。

> Mathematical reasoning presents a significant challenge for Large Language Models (LLMs) as it requires ensuring the correctness of each reasoning step. Researchers have been strengthening the mathematical reasoning abilities of LLMs through supervised fine-tuning, but due to the inability to suppress incorrect outputs, illusions can easily arise. Recently, Direct Preference Optimization (DPO) has been widely adopted for aligning human intent by using preference data to prevent LLMs from generating incorrect outputs. However, it has shown limited benefits in long-chain mathematical reasoning, mainly because DPO struggles to effectively capture the differences between accepted and rejected answers from preferences in long-chain data. The inconsistency between DPO training and LLMs' generation metrics also affects the effectiveness of suppressing incorrect outputs. We propose the Multi-Granularity Direct Preference Optimization (MDPO) method, optimizing the mathematical reasoning of LLMs at three granularities: Solution2Solution, Inference2Inference, and Step2Step. Solution2Solution focuses on the correctness of entire long-chain reasoning; Inference2Inference concentrates on logical reasoning between steps; Step2Step corrects computational errors in steps, enhancing the computational capabilities of LLMs. Additionally, we unify the training objectives of the three granularities to align with the generation metrics. We conducted experiments on the open-source models Qwen2 and Llama3, achieving improvements of 1.7% and 0.9% on the GSM8K dataset, and 2.3% and 1.2% on the MATH dataset, outperforming DPO and other DPO variant methods. Furthermore, we also provide a pipeline for constructing MDPO training data that is simple and does not require manual annotation costs.

[Arxiv](https://arxiv.org/abs/2506.15706)