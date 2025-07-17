# MSA @ ImageCLEF 2025 多模态推理：基于集成视觉语言模型的多语言多模态推理

发布时间：2025年07月15日

`LLM应用` `多模态`

> MSA at ImageCLEF 2025 Multimodal Reasoning: Multilingual Multimodal Reasoning With Ensemble Vision Language Models

# 摘要

> 我们提出了一种基于集成方法的健壮多语言多模态推理系统，专为ImageCLEF 2025 EXAMS V挑战设计。该系统整合了Gemini 2.5 Flash用于视觉描述，Gemini 1.5 Pro用于标题优化和一致性检查，以及Gemini 2.5 Pro作为推理器处理最终答案选择，所有组件通过精心设计的少量样本和零样本提示进行协调。我们进行了广泛的消融研究，在英语数据集及其多语言增强版本上训练了多个大型语言模型（包括Gemini 2.5 Flash、Phi 4、Gemma 3、Mistral）。此外，我们在零样本设置下评估了Gemini 2.5 Flash以进行对比，发现其显著优于经过训练的模型。提示设计也被证明是关键：强制要求简洁、语言标准化的格式，并禁止解释性文本，使得模型在英语验证集上的准确率从55.9%提升到61.7%。在官方排行榜上，我们的系统（团队MSA）在多语言赛道中以81.4%的准确率获得整体第一名，并在13个单独语言赛道中领先了11个，其中克罗地亚语达到95.07%，意大利语达到92.12%。这些发现表明，轻量级OCR与视觉语言模型的集成，结合精准的提示策略和跨语言增强，可以在高风险、多语言教育环境中超越更复杂的端到端模型。

> We present a robust ensemble-based system for multilingual multimodal reasoning, designed for the ImageCLEF 2025 EXAMS V challenge. Our approach integrates Gemini 2.5 Flash for visual description, Gemini 1.5 Pro for caption refinement and consistency checks, and Gemini 2.5 Pro as a reasoner which handles final answer selection, all coordinated through carefully engineered few-shot and zero-shot prompts. We conducted an extensive ablation study, training several large language models (Gemini 2.5 Flash, Phi 4, Gemma 3, Mistral) on an English dataset and its multilingual augmented version. Additionally, we evaluated Gemini 2.5 Flash in a zero-shot setting for comparison and found it to substantially outperform the trained models. Prompt design also proved critical: enforcing concise, language-normalized formats and prohibiting explanatory text boosted model accuracy on the English validation set from 55.9% to 61.7%. On the official leaderboard, our system (Team MSA) achieved first place overall in the multilingual track with 81.4% accuracy, and led 11 out of 13 individual language tracks, with top results such as 95.07% for Croatian and 92.12% for Italian. These findings highlight that lightweight OCR-VLM ensembles, when paired with precise prompt strategies and cross-lingual augmentation, can outperform heavier end-to-end models in high-stakes, multilingual educational settings.

[Arxiv](https://arxiv.org/abs/2507.11114)