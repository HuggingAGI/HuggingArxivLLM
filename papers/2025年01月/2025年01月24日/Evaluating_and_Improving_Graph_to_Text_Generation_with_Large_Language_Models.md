# 评估与优化：基于大型语言模型的图到文本生成

发布时间：2025年01月24日

`LLM应用

**理由**：这篇论文主要探讨了大型语言模型（LLMs）在图到文本生成任务中的应用，特别是通过提出新的数据集PlanGTG来提升LLMs在图序列规划和真实性基础方面的能力。研究重点在于如何通过数据集和提示策略来改进LLMs在特定任务中的表现，属于LLM在实际任务中的应用研究。` `图结构分析`

> Evaluating and Improving Graph to Text Generation with Large Language Models

# 摘要

> 大型语言模型（LLMs）在多种任务中展现了巨大潜力，但在图结构解释方面的研究仍显不足。为此，我们对开源LLMs在图到文本生成任务中的提示策略进行了全面评估。尽管我们探索了最优提示策略，并提出了一种基于多样性和难度的少样本选择方法，但无调优方法的改进有限，尤其是在处理复杂图（如包含大量三元组的图）时，LLMs的规划能力仍显不足。为进一步提升LLMs在图序列规划和真实性基础方面的能力，我们推出了新的图到文本数据集PlanGTG，包含重新排序和属性标注两个子任务。通过大量自动和人工评估，我们证明了使用PlanGTG数据集在少样本学习和微调视角下生成的文本质量显著提升。我们的研究为图到文本生成开辟了新方向。PlanGTG数据集可在https://github.com/probe2/kg_text获取。

> Large language models (LLMs) have demonstrated immense potential across various tasks. However, research for exploring and improving the capabilities of LLMs in interpreting graph structures remains limited. To address this gap, we conduct a comprehensive evaluation of prompting current open-source LLMs on graph-to-text generation tasks. Although we explored the optimal prompting strategies and proposed a novel and effective diversity-difficulty-based few-shot sample selection method, we found that the improvements from tuning-free approaches were incremental, as LLMs struggle with planning on complex graphs, particularly those with a larger number of triplets. To further improve LLMs in planning with graph sequences and grounding in truth, we introduce a new graph-to-text dataset, PlanGTG, annotated with two sub-tasks: reordering and attribution. Through extensive automatic and human evaluations, we demonstrate significant improvements in the quality of generated text from both few-shot learning and fine-tuning perspectives using the PlanGTG dataset. Our study paves the way for new research directions in graph-to-text generation. PlanGTG datasets can be found in https://github.com/probe2/kg_text.

[Arxiv](https://arxiv.org/abs/2501.14497)