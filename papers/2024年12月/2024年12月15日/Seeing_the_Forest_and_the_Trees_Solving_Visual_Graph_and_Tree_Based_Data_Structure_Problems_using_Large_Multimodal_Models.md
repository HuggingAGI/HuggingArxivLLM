# 见树又见林：利用大型多模态模型解决视觉图和树的数据结构问题

发布时间：2024年12月15日

`LLM应用

**理由**：这篇论文主要探讨了大型多模态模型（LMMs）在解决图和树数据结构问题上的能力，并构建了一个新的基准数据集来测试多个模型（如GPT-4o、Gemini等）的性能。研究内容集中在模型的应用层面，特别是如何利用这些模型解决具体的计算问题，并对教学和评估实践产生影响。因此，这篇论文应归类为LLM应用。` `人工智能`

> Seeing the Forest and the Trees: Solving Visual Graph and Tree Based Data Structure Problems using Large Multimodal Models

# 摘要

> # 摘要
生成式AI系统的快速发展引发了教育界对学术诚信的担忧。除了在编程和文本选择题上表现出色，最新研究还发现，大型多模态模型（LMMs）仅凭图像就能解决Parsons问题。然而，这些问题本质上仍依赖文本，模型需将代码块图像转换为文本。本文进一步探讨了LMMs仅凭图像解决图和树数据结构问题的能力。为此，我们构建并评估了一个包含9,072个样本的多样化图和树数据结构任务的新基准数据集，测试了GPT-4o、GPT-4v、Gemini 1.5 Pro、Gemini 1.5 Flash、Gemini 1.0 Pro Vision和Claude 3模型家族的性能。GPT-4o在树任务中以87.6%的准确率领先，而Gemini 1.5 Flash在图任务中以56.2%的准确率表现最佳。研究揭示了结构和视觉变化对模型性能的影响。本文不仅为LMMs提供了一个基准，便于复制和进一步研究，还展示了LMMs在解决复杂计算问题中的潜力，对教学和评估实践具有重要启示。

> Recent advancements in generative AI systems have raised concerns about academic integrity among educators. Beyond excelling at solving programming problems and text-based multiple-choice questions, recent research has also found that large multimodal models (LMMs) can solve Parsons problems based only on an image. However, such problems are still inherently text-based and rely on the capabilities of the models to convert the images of code blocks to their corresponding text. In this paper, we further investigate the capabilities of LMMs to solve graph and tree data structure problems based only on images. To achieve this, we computationally construct and evaluate a novel benchmark dataset comprising 9,072 samples of diverse graph and tree data structure tasks to assess the performance of the GPT-4o, GPT-4v, Gemini 1.5 Pro, Gemini 1.5 Flash, Gemini 1.0 Pro Vision, and Claude 3 model families. GPT-4o and Gemini 1.5 Flash performed best on trees and graphs respectively. GPT-4o achieved 87.6% accuracy on tree samples, while Gemini 1.5 Flash, achieved 56.2% accuracy on graph samples. Our findings highlight the influence of structural and visual variations on model performance. This research not only introduces an LMM benchmark to facilitate replication and further exploration but also underscores the potential of LMMs in solving complex computing problems, with important implications for pedagogy and assessment practices.

[Arxiv](https://arxiv.org/abs/2412.11088)