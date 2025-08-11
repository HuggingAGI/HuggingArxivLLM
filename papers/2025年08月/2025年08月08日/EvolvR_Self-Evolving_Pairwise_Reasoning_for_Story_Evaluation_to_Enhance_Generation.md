# EvolvR：通过自我演进的配对推理提升故事生成能力

发布时间：2025年08月08日

`LLM应用` `故事生成` `故事评估`

> EvolvR: Self-Evolving Pairwise Reasoning for Story Evaluation to Enhance Generation

# 摘要

> 尽管大型语言模型（LLMs）作为评委的能力已得到验证，但其在开放性任务中的表现仍显不足，尤其在故事评估方面。准确的故事评估不仅有助于辅助人类评判，还能为故事生成提供关键指导信号。现有方法面临双重困境：闭源模型的提示工程适应性差，而开源模型的微调方法缺乏故事评估所需的严格推理能力。为解决这一问题，我们提出了自演进配对推理（EvolvR）框架。基于配对比较，该框架通过多角色策略自我合成与分数对齐的思维链（CoT）数据。为确保数据质量，这些原始的CoT会经历一个自我过滤过程，利用多智能体确保其逻辑严谨性和鲁棒性。最终，基于精炼数据训练的评估器被部署为奖励模型，以指导故事生成任务。实验结果表明，我们的框架在StoryER、HANNA和OpenMEVA三个评估基准上均实现了最先进（SOTA）性能。此外，当作为奖励模型时，它显著提升了生成故事的质量，充分验证了我们自演进方法的优越性。

> Although the effectiveness of Large Language Models (LLMs) as judges (LLM-as-a-judge) has been validated, their performance remains limited in open-ended tasks, particularly in story evaluation. Accurate story evaluation is crucial not only for assisting human quality judgment but also for providing key signals to guide story generation. However, existing methods face a dilemma: prompt engineering for closed-source models suffers from poor adaptability, while fine-tuning approaches for open-source models lack the rigorous reasoning capabilities essential for story evaluation. To address this, we propose the Self-Evolving Pairwise Reasoning (EvolvR) framework. Grounded in pairwise comparison, the framework first self-synthesizes score-aligned Chain-of-Thought (CoT) data via a multi-persona strategy. To ensure data quality, these raw CoTs undergo a self-filtering process, utilizing multi-agents to guarantee their logical rigor and robustness. Finally, the evaluator trained on the refined data is deployed as a reward model to guide the story generation task. Experimental results demonstrate that our framework achieves state-of-the-art (SOTA) performance on three evaluation benchmarks including StoryER, HANNA and OpenMEVA. Furthermore, when served as a reward model, it significantly enhances the quality of generated stories, thereby fully validating the superiority of our self-evolving approach.

[Arxiv](https://arxiv.org/abs/2508.06046)