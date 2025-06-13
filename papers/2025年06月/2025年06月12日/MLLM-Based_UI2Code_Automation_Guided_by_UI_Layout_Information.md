# # 基于MLLM的UI到代码自动化：利用UI布局信息进行引导
通过MLLM实现的UI到代码自动化，利用UI布局信息进行智能引导。

发布时间：2025年06月12日

`LLM应用` `网站开发` `用户界面设计`

> MLLM-Based UI2Code Automation Guided by UI Layout Information

# 摘要

> 将用户界面转换为代码（UI2Code）是网站开发中的关键步骤，这一过程耗时且劳动密集。UI2Code的自动化对于提高开发效率至关重要。尽管存在基于深度学习的方法，但它们依赖大量标注数据且难以推广到真实世界的设计。多模态大型语言模型（MLLMs）虽然有潜力，但难以准确理解UI布局并生成代码。为此，我们提出了LayoutCoder框架，从真实网页图像生成UI代码，包含三个核心模块：元素关系构建、UI布局解析和布局引导的代码融合。我们构建了包含350个真实网站的Snap2Code数据集，并与现有数据集Design2Code一起进行评估。实验结果表明，LayoutCoder在性能上优于现有方法，BLEU和CLIP分数分别提高了10.14%和3.95%。

> Converting user interfaces into code (UI2Code) is a crucial step in website development, which is time-consuming and labor-intensive. The automation of UI2Code is essential to streamline this task, beneficial for improving the development efficiency. There exist deep learning-based methods for the task; however, they heavily rely on a large amount of labeled training data and struggle with generalizing to real-world, unseen web page designs. The advent of Multimodal Large Language Models (MLLMs) presents potential for alleviating the issue, but they are difficult to comprehend the complex layouts in UIs and generate the accurate code with layout preserved. To address these issues, we propose LayoutCoder, a novel MLLM-based framework generating UI code from real-world webpage images, which includes three key modules: (1) Element Relation Construction, which aims at capturing UI layout by identifying and grouping components with similar structures; (2) UI Layout Parsing, which aims at generating UI layout trees for guiding the subsequent code generation process; and (3) Layout-Guided Code Fusion, which aims at producing the accurate code with layout preserved. For evaluation, we build a new benchmark dataset which involves 350 real-world websites named Snap2Code, divided into seen and unseen parts for mitigating the data leakage issue, besides the popular dataset Design2Code. Extensive evaluation shows the superior performance of LayoutCoder over the state-of-the-art approaches. Compared with the best-performing baseline, LayoutCoder improves 10.14% in the BLEU score and 3.95% in the CLIP score on average across all datasets.

[Arxiv](https://arxiv.org/abs/2506.10376)