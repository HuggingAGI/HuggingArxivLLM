# SlideCoder：基于设计的布局感知RAG增强层次化幻灯片生成方法

发布时间：2025年06月09日

`LLM应用

摘要中提到的论文主要探讨了将大型语言模型应用于幻灯片生成的任务，提出了新的基准和框架，并展示了模型的实际效果。因此，它属于LLM应用类别。` `办公自动化` `计算机视觉`

> SlideCoder: Layout-aware RAG-enhanced Hierarchical Slide Generation from Design

# 摘要

> 制作幻灯片耗时且需要专业知识，现有基于自然语言的LLM生成方法难以捕捉幻灯片设计中的视觉和结构细节。为解决这一问题，我们提出了参考图像到幻灯片生成任务，并推出了Slide2Code——首个基于新型幻灯片复杂度指标的分难度等级样本基准。我们开发了SlideCoder，这是一个了解布局且具有检索增强功能的框架，用于从参考图像生成可编辑幻灯片。SlideCoder结合了基于颜色渐变的分割算法和分层检索增强生成方法，以分解复杂任务并提升代码生成效果。此外，我们发布了SlideMaster——一个经过改进逆向工程数据微调的开源7B模型。实验结果显示，SlideCoder在布局保真度、执行准确性和视觉一致性等方面均优于现有最先进基线，高出40.5分。我们的代码可在GitHub上获取：https://github.com/vinsontang1/SlideCoder。

> Manual slide creation is labor-intensive and requires expert prior knowledge. Existing natural language-based LLM generation methods struggle to capture the visual and structural nuances of slide designs. To address this, we formalize the Reference Image to Slide Generation task and propose Slide2Code, the first benchmark with difficulty-tiered samples based on a novel Slide Complexity Metric. We introduce SlideCoder, a layout-aware, retrieval-augmented framework for generating editable slides from reference images. SlideCoder integrates a Color Gradient-based Segmentation algorithm and a Hierarchical Retrieval-Augmented Generation method to decompose complex tasks and enhance code generation. We also release SlideMaster, a 7B open-source model fine-tuned with improved reverse-engineered data. Experiments show that SlideCoder outperforms state-of-the-art baselines by up to 40.5 points, demonstrating strong performance across layout fidelity, execution accuracy, and visual consistency. Our code is available at https://github.com/vinsontang1/SlideCoder.

[Arxiv](https://arxiv.org/abs/2506.07964)