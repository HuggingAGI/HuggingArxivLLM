# 教大型语言模型生成数字聚焦标题及关键元素理由

发布时间：2025年02月05日

`LLM应用

理由：该论文主要关注如何利用LLMs（大型语言模型）来提升数字聚焦的标题生成任务中的文本质量和数字准确性。通过引入思维链框架和教师-学生模型的方法，论文展示了如何微调和优化LLMs以生成更高质量的文本。这属于LLM在实际应用中的改进和优化，因此归类为“LLM应用”。`

> Teaching Large Language Models Number-Focused Headline Generation With Key Element Rationales

# 摘要

> # 摘要
数字聚焦的标题生成任务要求高文本质量和精确数字准确性，这对LLMs提出了独特挑战。现有研究往往只关注文本质量或数字推理，难以全面应对这一挑战。本文提出了一种新颖的思维链框架，通过引入新闻文章中的主题、实体和数字推理（TEN）作为理由，提升LLMs生成主题一致且数字精确的高质量文本的能力。具体而言，我们利用教师LLM生成TEN理由作为监督数据，用于教导和微调学生LLM，使其具备自动生成理由并提升数字推理和标题生成的能力。实验结果表明，该方法在文本质量和数字准确性上均表现优异。

> Number-focused headline generation is a summarization task requiring both high textual quality and precise numerical accuracy, which poses a unique challenge for Large Language Models (LLMs). Existing studies in the literature focus only on either textual quality or numerical reasoning and thus are inadequate to address this challenge. In this paper, we propose a novel chain-of-thought framework for using rationales comprising key elements of the Topic, Entities, and Numerical reasoning (TEN) in news articles to enhance the capability for LLMs to generate topic-aligned high-quality texts with precise numerical accuracy. Specifically, a teacher LLM is employed to generate TEN rationales as supervision data, which are then used to teach and fine-tune a student LLM. Our approach teaches the student LLM automatic generation of rationales with enhanced capability for numerical reasoning and topic-aligned numerical headline generation. Experiments show that our approach achieves superior performance in both textual quality and numerical accuracy.

[Arxiv](https://arxiv.org/abs/2502.03129)