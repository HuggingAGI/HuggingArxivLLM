# 故事生成框架：一个多智能体架构用于长篇故事创作

发布时间：2025年06月19日

`LLM应用` `内容创作`

> StoryWriter: A Multi-Agent Framework for Long Story Generation

# 摘要

> 长篇故事生成仍是现有大型语言模型（LLMs）面临的挑战，主要归因于两大核心因素：(1) 语篇连贯性，要求在长篇生成中保持情节一致、逻辑连贯且完整；(2) 叙事复杂性，要求故事情节交织且引人入胜。为应对这些挑战，我们提出StoryWriter，一个由三个主要模块组成的多智能体故事生成框架：(1) 大纲智能体，生成包含丰富情节、角色及其关系的事件大纲；(2) 规划智能体，进一步细化事件并规划每章应重点描写的事件，以保持故事情节的交织性和吸引力；(3) 写作智能体，根据当前事件动态压缩故事历史，生成并反映新情节，确保生成故事的连贯性。我们进行了人工和自动化评估，结果显示StoryWriter在故事质量和长度上均显著优于现有故事生成基线。此外，我们利用StoryWriter生成了一个包含约6,000篇高质量长篇故事的数据集，平均长度达8,000字。我们通过监督微调在LongStory数据集上训练了Llama3.1-8B和GLM4-9B模型，并开发了StoryWriter_GLM，该模型在长篇故事生成方面展现了卓越性能。

> Long story generation remains a challenge for existing large language models (LLMs), primarily due to two main factors: (1) discourse coherence, which requires plot consistency, logical coherence, and completeness in the long-form generation, and (2) narrative complexity, which requires an interwoven and engaging narrative. To address these challenges, we propose StoryWriter, a multi-agent story generation framework, which consists of three main modules: (1) outline agent, which generates event-based outlines containing rich event plots, character, and event-event relationships. (2) planning agent, which further details events and plans which events should be written in each chapter to maintain an interwoven and engaging story. (3) writing agent, which dynamically compresses the story history based on the current event to generate and reflect new plots, ensuring the coherence of the generated story. We conduct both human and automated evaluation, and StoryWriter significantly outperforms existing story generation baselines in both story quality and length. Furthermore, we use StoryWriter to generate a dataset, which contains about $6,000$ high-quality long stories, with an average length of $8,000$ words. We train the model Llama3.1-8B and GLM4-9B using supervised fine-tuning on LongStory and develop StoryWriter_GLM and StoryWriter_GLM, which demonstrates advanced performance in long story generation.

[Arxiv](https://arxiv.org/abs/2506.16445)