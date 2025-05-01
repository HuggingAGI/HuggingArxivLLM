# # Phi-4推理技术报告

发布时间：2025年04月30日

`LLM理论

论文摘要：我们推出 Phi-4-reasoning，一款140亿参数的推理模型，在复杂推理任务中表现卓越。该模型基于 Phi-4，通过监督微调训练而成，采用精心挑选的“可教学”提示，确保适当的复杂度和多样性，并结合 o3-mini 生成的推理演示。Phi-4-reasoning 能够生成详尽的推理链，充分运用推理时的计算资源。此外，我们开发了增强版 Phi-4-reasoning-plus，通过基于结果的强化学习训练，生成更长的推理轨迹，性能更上一层楼。在广泛的推理任务中，这两个模型不仅超越了 DeepSeek-R1-Distill-Llama-70B 等大型开源模型，甚至接近 DeepSeek-R1 的性能水平。我们的评估覆盖了数学与科学推理、编码、算法问题解决、规划及空间理解等多个基准测试。值得注意的是，这些改进在通用基准测试中也带来了显著提升。在本报告中，我们将深入探讨训练数据、训练方法及评估过程。我们发现，精心整理的数据对于监督微调（SFT）至关重要，而强化学习（RL）则能进一步放大这一优势。最后，我们的评估结果为提升推理模型的性能和稳健性评估提供了新的思路。

LLM理论` `人工智能`

> Phi-4-reasoning Technical Report

# 摘要

> 我们推出 Phi-4-reasoning，一款140亿参数的推理模型，在复杂推理任务中表现卓越。该模型基于 Phi-4，通过监督微调训练而成，采用精心挑选的“可教学”提示，确保适当的复杂度和多样性，并结合 o3-mini 生成的推理演示。Phi-4-reasoning 能够生成详尽的推理链，充分运用推理时的计算资源。此外，我们开发了增强版 Phi-4-reasoning-plus，通过基于结果的强化学习训练，生成更长的推理轨迹，性能更上一层楼。在广泛的推理任务中，这两个模型不仅超越了 DeepSeek-R1-Distill-Llama-70B 等大型开源模型，甚至接近 DeepSeek-R1 的性能水平。我们的评估覆盖了数学与科学推理、编码、算法问题解决、规划及空间理解等多个基准测试。值得注意的是，这些改进在通用基准测试中也带来了显著提升。在本报告中，我们将深入探讨训练数据、训练方法及评估过程。我们发现，精心整理的数据对于监督微调（SFT）至关重要，而强化学习（RL）则能进一步放大这一优势。最后，我们的评估结果为提升推理模型的性能和稳健性评估提供了新的思路。

> We introduce Phi-4-reasoning, a 14-billion parameter reasoning model that achieves strong performance on complex reasoning tasks. Trained via supervised fine-tuning of Phi-4 on carefully curated set of "teachable" prompts-selected for the right level of complexity and diversity-and reasoning demonstrations generated using o3-mini, Phi-4-reasoning generates detailed reasoning chains that effectively leverage inference-time compute. We further develop Phi-4-reasoning-plus, a variant enhanced through a short phase of outcome-based reinforcement learning that offers higher performance by generating longer reasoning traces. Across a wide range of reasoning tasks, both models outperform significantly larger open-weight models such as DeepSeek-R1-Distill-Llama-70B model and approach the performance levels of full DeepSeek-R1 model. Our comprehensive evaluations span benchmarks in math and scientific reasoning, coding, algorithmic problem solving, planning, and spatial understanding. Interestingly, we observe a non-trivial transfer of improvements to general-purpose benchmarks as well. In this report, we provide insights into our training data, our training methodologies, and our evaluations. We show that the benefit of careful data curation for supervised fine-tuning (SFT) extends to reasoning language models, and can be further amplified by reinforcement learning (RL). Finally, our evaluation points to opportunities for improving how we assess the performance and robustness of reasoning models.

[Arxiv](https://arxiv.org/abs/2504.21318)