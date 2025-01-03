# 以眼还眼：通过计算机图形学问题评估 GPT-4o 的视觉感知与几何推理能力

发布时间：2024年10月22日

`LLM应用

理由：这篇论文主要探讨了大型多模态模型（LMM）或多模态LLM在计算机图形学（CG）教学中的应用，特别是如何利用这些模型来解决CG问题并改进教学。虽然论文也涉及到了模型的性能评估，但其核心关注点是如何将这些模型应用于实际教学场景中，因此应归类为“LLM应用”。` `计算机图形学`

> An Eye for an AI: Evaluating GPT-4o's Visual Perception Skills and Geometric Reasoning Skills Using Computer Graphics Questions

# 摘要

> # 摘要
计算机图形学（CG）是计算机科学（CS）中的热门领域，但由于涉及数学、编程、几何推理和创造力等多重技能，许多学生感到学习困难。近年来，研究人员探索了如何利用生成式人工智能（GenAI）改进教学。在CS领域，研究主要集中在入门计算上。最近一项评估大型语言模型（LLM）GPT-4（仅文本）在CG问题上的表现的研究显示，其表现不佳，且依赖对图像内容的详细描述，通常需要用户提供大量洞察才能得到合理结果。目前，尚无研究探讨大型多模态模型（LMM）或多模态LLM解决CG问题的能力及其在教学中的应用。
本研究构建了两个需要不同视觉感知和几何推理技能的CG问题数据集，并评估了当前最先进的LMM GPT-4o的表现。尽管GPT-4o在独立处理视觉信息问题时展现出潜力，但其生成结果的准确性和质量仍有显著局限。我们提出了几种新颖方法，帮助CG教育者在教学中融入GenAI，尽管存在这些限制。我们希望这些指南能进一步激发CG课堂中的学习兴趣和参与度。

> CG (Computer Graphics) is a popular field of CS (Computer Science), but many students find this topic difficult due to it requiring a large number of skills, such as mathematics, programming, geometric reasoning, and creativity. Over the past few years, researchers have investigated ways to harness the power of GenAI (Generative Artificial Intelligence) to improve teaching. In CS, much of the research has focused on introductory computing. A recent study evaluating the performance of an LLM (Large Language Model), GPT-4 (text-only), on CG questions, indicated poor performance and reliance on detailed descriptions of image content, which often required considerable insight from the user to return reasonable results. So far, no studies have investigated the abilities of LMMs (Large Multimodal Models), or multimodal LLMs, to solve CG questions and how these abilities can be used to improve teaching.
  In this study, we construct two datasets of CG questions requiring varying degrees of visual perception skills and geometric reasoning skills, and evaluate the current state-of-the-art LMM, GPT-4o, on the two datasets. We find that although GPT-4o exhibits great potential in solving questions with visual information independently, major limitations still exist to the accuracy and quality of the generated results. We propose several novel approaches for CG educators to incorporate GenAI into CG teaching despite these limitations. We hope that our guidelines further encourage learning and engagement in CG classrooms.

[Arxiv](https://arxiv.org/abs/2410.16991)