# 大规模多模态模型在开放世界图像分类中的应用研究

发布时间：2025年03月27日

`LLM应用` `图像分类` `计算机视觉`

> On Large Multimodal Models as Open-World Image Classifiers

# 摘要

> 传统图像分类需要预先定义的语义类别列表，而大型多模态模型（LMMs）则可以通过直接使用自然语言（例如回答“图像中的主要物体是什么？”）对图像进行分类，从而绕过了这一限制。尽管LMMs具备这种出色的能力，但目前关于其分类性能的研究却意外地局限于封闭世界环境，通常假设类别是预先定义好的。本研究通过全面评估LMM在真正开放世界环境下的分类性能来填补这一空白。我们首先正式定义了任务并引入了评估协议，定义了各种指标来评估预测类别与真实类别之间的对齐程度。然后，我们在10个基准测试中评估了13种模型，涵盖了原型、非原型、细粒度和超细粒度类别，展示了LMM在此任务中所面临的挑战。基于提出的指标进行的进一步分析揭示了LMM所犯的错误类型，突显了与粒度和细粒度能力相关的挑战，并展示了如何通过定制提示和推理来缓解这些问题。

> Traditional image classification requires a predefined list of semantic categories. In contrast, Large Multimodal Models (LMMs) can sidestep this requirement by classifying images directly using natural language (e.g., answering the prompt "What is the main object in the image?"). Despite this remarkable capability, most existing studies on LMM classification performance are surprisingly limited in scope, often assuming a closed-world setting with a predefined set of categories. In this work, we address this gap by thoroughly evaluating LMM classification performance in a truly open-world setting. We first formalize the task and introduce an evaluation protocol, defining various metrics to assess the alignment between predicted and ground truth classes. We then evaluate 13 models across 10 benchmarks, encompassing prototypical, non-prototypical, fine-grained, and very fine-grained classes, demonstrating the challenges LMMs face in this task. Further analyses based on the proposed metrics reveal the types of errors LMMs make, highlighting challenges related to granularity and fine-grained capabilities, showing how tailored prompting and reasoning can alleviate them.

[Arxiv](https://arxiv.org/abs/2503.21851)