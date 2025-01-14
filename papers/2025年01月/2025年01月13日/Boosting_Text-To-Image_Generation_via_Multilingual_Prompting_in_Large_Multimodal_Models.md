# 多语言提示助力多模态大模型，提升文本到图像生成效果

发布时间：2025年01月13日

`LLM应用

理由：这篇论文主要探讨了如何通过构建并行多语言提示来增强大型多模态模型（LMMs）在文本到图像生成任务中的表现。研究集中在提升模型对输入文本的理解能力，特别是在多语言环境下的应用。虽然涉及多模态模型，但其核心是优化和扩展LLM在多语言环境中的应用，因此归类为LLM应用。` `多模态生成`

> Boosting Text-To-Image Generation via Multilingual Prompting in Large Multimodal Models

# 摘要

> # 摘要
以往增强大型多模态模型（LMMs）用于文本到图像（T2I）生成的研究，主要集中在丰富上下文学习（ICL）的输入空间，如提供示例并优化图像描述，使其更详细和逻辑化。然而，随着对复杂灵活图像描述需求的增加，提升ICL范式中对输入文本的理解仍是一个关键但未充分探索的领域。本研究通过构建并行多语言提示，进一步探索LMMs的多语言能力。具体而言，我们将输入文本翻译成多种语言，并为模型提供原始文本及其翻译。在两个LMMs上进行的3个基准测试表明，我们的方法PMT2I在一般、组合和细粒度评估中表现优异，尤其在人类偏好对齐方面。此外，PMT2I在生成多样化图像方面具有优势，结合重排序方法后，显著优于基线提示。代码和并行多语言数据详见https://github.com/takagi97/PMT2I。

> Previous work on augmenting large multimodal models (LMMs) for text-to-image (T2I) generation has focused on enriching the input space of in-context learning (ICL). This includes providing a few demonstrations and optimizing image descriptions to be more detailed and logical. However, as demand for more complex and flexible image descriptions grows, enhancing comprehension of input text within the ICL paradigm remains a critical yet underexplored area. In this work, we extend this line of research by constructing parallel multilingual prompts aimed at harnessing the multilingual capabilities of LMMs. More specifically, we translate the input text into several languages and provide the models with both the original text and the translations. Experiments on two LMMs across 3 benchmarks show that our method, PMT2I, achieves superior performance in general, compositional, and fine-grained assessments, especially in human preference alignment. Additionally, with its advantage of generating more diverse images, PMT2I significantly outperforms baseline prompts when incorporated with reranking methods. Our code and parallel multilingual data can be found at https://github.com/takagi97/PMT2I.

[Arxiv](https://arxiv.org/abs/2501.07086)