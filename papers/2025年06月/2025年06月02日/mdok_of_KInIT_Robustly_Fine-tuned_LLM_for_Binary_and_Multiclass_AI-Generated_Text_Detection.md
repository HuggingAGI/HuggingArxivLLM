# mdok of KInIT：用于二分类和多分类AI生成文本检测的稳健微调大型语言模型。

发布时间：2025年06月02日

`LLM应用` `信息检测` `人工智能`

> mdok of KInIT: Robustly Fine-tuned LLM for Binary and Multiclass AI-Generated Text Detection

# 摘要

> 大型语言模型（LLMs）能够生成多语言高质量文本，这些文本常常难以被人识别为机器生成，因此存在被滥用的风险（例如抄袭、垃圾信息、散布虚假信息）。自动化检测技术可以帮助人们识别这些机器生成的文本，然而，其对分布外数据的鲁棒性仍然是一个挑战。本笔记本介绍了我们基于微调小型LLMs进行文本分类的mdok方法，用于实现稳健检测。该方法被应用于2025 Voight-Kampff生成式AI检测竞赛的两个子任务中，在二分类检测中表现出色，并在多分类（第1名）的各种人机协作案例中也取得了显著成绩。

> The large language models (LLMs) are able to generate high-quality texts in multiple languages. Such texts are often not recognizable by humans as generated, and therefore present a potential of LLMs for misuse (e.g., plagiarism, spams, disinformation spreading). An automated detection is able to assist humans to indicate the machine-generated texts; however, its robustness to out-of-distribution data is still challenging. This notebook describes our mdok approach in robust detection, based on fine-tuning smaller LLMs for text classification. It is applied to both subtasks of Voight-Kampff Generative AI Detection 2025, providing remarkable performance in binary detection as well as in multiclass (1st rank) classification of various cases of human-AI collaboration.

[Arxiv](https://arxiv.org/abs/2506.01702)