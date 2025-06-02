# # MIRAGE：评估多模态大语言模型中多模态推理链的幻觉现象

发布时间：2025年05月30日

`LLM理论` `计算机视觉`

> MIRAGE: Assessing Hallucination in Multimodal Reasoning Chains of MLLM

# 摘要

> 多模态幻觉问题在多模态大型语言模型 (MLLMs) 中制约了其输出的正确性。这一问题具有多重来源，由多种原因共同引发。现有的评测基准未能充分区分由感知错误引发的幻觉与由推理错误引发的幻觉。这一不足构成了一个重大问题，阻碍了对 MLLMs 中多模态推理失败的深入诊断。

为解决这一问题，我们提出 {\dataset} 基准测试。该基准通过构建一类特殊问题来孤立推理幻觉：输入图像被 MLLMs 正确感知，但推理错误依然存在。{\dataset} 引入了多粒度评估指标：准确性、事实性和 LLMs 幻觉评分，用于量化幻觉程度。

我们的分析揭示了以下关键发现：
1. 模型规模、数据规模和训练阶段显著影响逻辑、捏造和事实幻觉的程度；
2. 当前 MLLMs 在由误判空间关系引起的错误空间幻觉方面未见有效改进，表明其视觉推理能力存在明显局限；
3. 不同问题类型与特定幻觉模式相关联，突显了针对性挑战及潜在缓解策略。

为应对这些挑战，我们提出 {\method}，一种结合课程强化微调的方法。该方法通过逐步降低学习难度，鼓励模型生成逻辑一致的推理链，并借助协作提示推理来简化推理复杂度。{\method} 在 {\dataset} 上建立了基线，并显著减少了原始基础模型中的逻辑幻觉。


> Multimodal hallucination in multimodal large language models (MLLMs) restricts the correctness of MLLMs. However, multimodal hallucinations are multi-sourced and arise from diverse causes. Existing benchmarks fail to adequately distinguish between perception-induced hallucinations and reasoning-induced hallucinations. This failure constitutes a significant issue and hinders the diagnosis of multimodal reasoning failures within MLLMs. To address this, we propose the {\dataset} benchmark, which isolates reasoning hallucinations by constructing questions where input images are correctly perceived by MLLMs yet reasoning errors persist. {\dataset} introduces multi-granular evaluation metrics: accuracy, factuality, and LLMs hallucination score for hallucination quantification. Our analysis reveals that (1) the model scale, data scale, and training stages significantly affect the degree of logical, fabrication, and factual hallucinations; (2) current MLLMs show no effective improvement on spatial hallucinations caused by misinterpreted spatial relationships, indicating their limited visual reasoning capabilities; and (3) question types correlate with distinct hallucination patterns, highlighting targeted challenges and potential mitigation strategies. To address these challenges, we propose {\method}, a method that combines curriculum reinforcement fine-tuning to encourage models to generate logic-consistent reasoning chains by stepwise reducing learning difficulty, and collaborative hint inference to reduce reasoning complexity. {\method} establishes a baseline on {\dataset}, and reduces the logical hallucinations in original base models.

[Arxiv](https://arxiv.org/abs/2505.24238)