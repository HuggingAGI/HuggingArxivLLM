# 知识与推理，哪个更重要？一探 LLMs 跨领域思考的奥秘

发布时间：2025年06月02日

`LLM应用`

> Knowledge or Reasoning? A Close Look at How LLMs Think Across Domains

# 摘要

> 近期，推理增强型大型语言模型（如 OpenAI-o1/3 和 DeepSeek-R1）在复杂任务上的性能有了显著提升。然而，这些模型内部推理过程的质量和透明度仍待进一步探索。本研究突破了对最终答案准确性的关注，转而深入探究医疗和数学领域中的逐步推理过程，通过将推理轨迹明确分解为知识和推理两部分进行分析。具体而言，我们提出了一套细致入微的评估框架，用于评判：(1) 所使用知识的正确性（通过知识指数 (KI) 衡量）以及 (2) 推理的质量（通过信息增益 (InfoGain) 衡量）。借助此框架，我们研究了经过监督微调 (SFT) 和/或强化学习 (RL) 训练的 R1 蒸馏模型和基线 Qwen 模型在医疗和数学领域中的表现。研究发现三个有趣的现象：(1) R1 蒸馏模型的一般推理能力并未通过 SFT 或 RL 有效迁移至医疗领域；(2) SFT 在两个领域中均提高了最终答案的准确性，但往往以推理质量为代价：与未经训练的模型相比，InfoGain 平均下降 38.9%。然而，在医疗领域，SFT 仍至关重要，因为专业知识不可或缺；(3) RL 通过剪除推理路径中不准确或不相关的知识，提升了医疗推理的准确性，同时改善了知识的正确性。

> Recent advances in reasoning-enhanced Large Language Models such as OpenAI-o1/3 and DeepSeek-R1 have significantly improved performance on complex tasks. However, the quality and transparency of their internal reasoning processes remain underexplored. This work moves beyond the final-answer accuracy and investigates step-by-step reasoning in the medical and mathematical domains by explicitly decomposing the thinking trajectories into two parts: knowledge and reasoning. Specifically, we introduce a fine-grained evaluation framework that judges: (1) the correctness of knowledge used (measured by Knowledge Index (KI)) and (2) the quality of reasoning (measured by Information Gain (InfoGain)). Using this framework, we study R1-distilled and base Qwen models trained with supervised fine-tuning (SFT) and/or reinforcement learning (RL) in the medical and math domains. Three intriguing findings emerge: (1) The general reasoning abilities in R1-distilled models do not transfer effectively to the medical domain through either SFT or RL. (2) SFT raises final-answer accuracy in both domains, but often at the cost of reasoning quality: InfoGain drops by 38.9% on average compared with untrained models; In the medical domain, however, SFT remains crucial because domain knowledge is indispensable. (3) RL enhances medical reasoning by pruning inaccurate or irrelevant knowledge from reasoning paths, thereby improving both reasoning accuracy and knowledge correctness.

[Arxiv](https://arxiv.org/abs/2506.02126)