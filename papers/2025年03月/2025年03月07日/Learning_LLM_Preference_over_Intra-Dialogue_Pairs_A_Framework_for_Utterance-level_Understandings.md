# 学习 LLM 对对话内部配对的偏好：一种基于语句级别的理解框架

发布时间：2025年03月07日

`LLM应用` `对话系统`

> Learning LLM Preference over Intra-Dialogue Pairs: A Framework for Utterance-level Understandings

# 摘要

> 大型语言模型（LLMs）在处理复杂对话任务时展现出了显著的能力，而无需为特定场景做针对性调整。然而，实时对话分析需要低延迟的处理系统，这使得部署具有数十亿参数的模型变得不切实际。因此，从业者通常更倾向于使用参数量在百万级的小模型，这些模型基于高质量的人工标注数据集进行训练。然而，整理此类数据集既耗时又昂贵。因此，如何将LLM生成标签的可扩展性与人工标注的精准度相结合，成为了一个亟待解决的问题。通过这种结合，经过微调的小模型能够实现与大模型相当的高速度和高精度。本文提出了一种简单而有效的框架来解决这一问题。我们的方法特别针对每个 utterance 的分类问题，涵盖意图检测、对话状态追踪等任务。为了减少LLM标注错误对学生模型准确性的影响，我们提出了一种噪声减少的偏好学习损失。实验结果表明，我们的方法在 utterance 级别的对话任务中显著提高了准确率，包括情感检测（超过$2\%$）、对话行为分类（超过$1.5\%$）等。

> Large language models (LLMs) have demonstrated remarkable capabilities in handling complex dialogue tasks without requiring use case-specific fine-tuning. However, analyzing live dialogues in real-time necessitates low-latency processing systems, making it impractical to deploy models with billions of parameters due to latency constraints. As a result, practitioners often prefer smaller models with millions of parameters, trained on high-quality, human-annotated datasets. Yet, curating such datasets is both time-consuming and costly. Consequently, there is a growing need to combine the scalability of LLM-generated labels with the precision of human annotations, enabling fine-tuned smaller models to achieve both higher speed and accuracy comparable to larger models. In this paper, we introduce a simple yet effective framework to address this challenge. Our approach is specifically designed for per-utterance classification problems, which encompass tasks such as intent detection, dialogue state tracking, and more. To mitigate the impact of labeling errors from LLMs -- the primary source of inaccuracies in student models -- we propose a noise-reduced preference learning loss. Experimental results demonstrate that our method significantly improves accuracy across utterance-level dialogue tasks, including sentiment detection (over $2\%$), dialogue act classification (over $1.5\%$), etc.

[Arxiv](https://arxiv.org/abs/2503.05620)