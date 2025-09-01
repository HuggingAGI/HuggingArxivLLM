# 因材施教与难度均衡：借助提示课程增强多模态思维链推理

发布时间：2025年08月26日

`LLM应用` `教育科技`

> Tailored Teaching with Balanced Difficulty: Elevating Reasoning in Multimodal Chain-of-Thought via Prompt Curriculum

# 摘要

> 多模态思维链（MCoT）提示的效果常因示例选择方式（随机或人工挑选）而受限：这些示例既未考虑模型特有的知识分布，也忽略了任务的内在复杂性，导致模型性能不理想且不稳定。为此，我们受“难度平衡的定制教学”教育理念启发，提出了一种全新框架——将提示选择重构为“提示课程设计”问题，即构建与模型当前能力相适配的有序训练示例集。该方法整合了两个互补信号：（1）模型感知难度，通过主动学习场景下的预测分歧量化，捕捉模型自身的“认知难点”；（2）内在样本复杂性，独立于模型衡量每个问题-图像对的固有难度。通过联合分析这两个信号，我们开发出难度平衡的采样策略，确保所选提示示例在上述两个维度均具备多样性。在五个高难度基准数据集和多款主流多模态大语言模型（MLLMs）上的大量实验表明，该方法能带来显著且稳定的性能提升，大幅减少随机采样造成的性能波动，为增强多模态推理提供了一套兼具理论依据与鲁棒性的解决方案。

> The effectiveness of Multimodal Chain-of-Thought (MCoT) prompting is often limited by the use of randomly or manually selected examples. These examples fail to account for both model-specific knowledge distributions and the intrinsic complexity of the tasks, resulting in suboptimal and unstable model performance. To address this, we propose a novel framework inspired by the pedagogical principle of "tailored teaching with balanced difficulty". We reframe prompt selection as a prompt curriculum design problem: constructing a well ordered set of training examples that align with the model's current capabilities. Our approach integrates two complementary signals: (1) model-perceived difficulty, quantified through prediction disagreement in an active learning setup, capturing what the model itself finds challenging; and (2) intrinsic sample complexity, which measures the inherent difficulty of each question-image pair independently of any model. By jointly analyzing these signals, we develop a difficulty-balanced sampling strategy that ensures the selected prompt examples are diverse across both dimensions. Extensive experiments conducted on five challenging benchmarks and multiple popular Multimodal Large Language Models (MLLMs) demonstrate that our method yields substantial and consistent improvements and greatly reduces performance discrepancies caused by random sampling, providing a principled and robust approach for enhancing multimodal reasoning.

[Arxiv](https://arxiv.org/abs/2508.18673)