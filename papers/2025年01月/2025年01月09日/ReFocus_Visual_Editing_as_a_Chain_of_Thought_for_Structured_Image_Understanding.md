# ReFocus: 视觉编辑——结构化图像理解的思维链

发布时间：2025年01月09日

`LLM应用

理由：这篇论文主要讨论了如何通过ReFocus框架提升多模态大型语言模型（LLMs）在结构化图像理解任务中的表现。具体来说，ReFocus通过生成Python代码调用工具来动态调整和优化视觉焦点，从而提升视觉推理效果。这属于LLM在实际应用中的改进和优化，因此应归类为LLM应用。` `计算机视觉` `图像处理`

> ReFocus: Visual Editing as a Chain of Thought for Structured Image Understanding

# 摘要

> 结构化图像理解，如表格和图表的解析，需要策略性地在图像中的不同结构和文本间切换焦点，形成推理链条以得出最终答案。然而，现有的多模态大型语言模型（LLMs）缺乏这种多跳选择性注意力能力。为此，我们提出了ReFocus框架，通过代码对输入图像进行视觉编辑，赋予多模态LLMs生成“视觉思维”的能力，从而动态调整和优化视觉焦点。具体而言，ReFocus让多模态LLMs生成Python代码调用工具，依次绘制框、高亮区域和遮罩部分，从而提升视觉推理效果。我们在涉及表格和图表的多种结构化图像理解任务上进行了实验。ReFocus在所有任务上的表现均显著优于未进行视觉编辑的GPT-4o，表格任务平均提升11.0%，图表任务平均提升6.8%。我们深入分析了不同视觉编辑的效果，并探讨了ReFocus在不引入额外信息的情况下提升性能的原因。此外，我们利用ReFocus构建了一个14k的训练集，证明这种带有中间信息的视觉思维链比标准VQA数据提供了更好的监督效果，相比使用QA对训练的模型，平均提升8.0%，相比CoT提升2.6%。

> Structured image understanding, such as interpreting tables and charts, requires strategically refocusing across various structures and texts within an image, forming a reasoning sequence to arrive at the final answer. However, current multimodal large language models (LLMs) lack this multihop selective attention capability. In this work, we introduce ReFocus, a simple yet effective framework that equips multimodal LLMs with the ability to generate "visual thoughts" by performing visual editing on the input image through code, shifting and refining their visual focuses. Specifically, ReFocus enables multimodal LLMs to generate Python codes to call tools and modify the input image, sequentially drawing boxes, highlighting sections, and masking out areas, thereby enhancing the visual reasoning process. We experiment upon a wide range of structured image understanding tasks involving tables and charts. ReFocus largely improves performance on all tasks over GPT-4o without visual editing, yielding an average gain of 11.0% on table tasks and 6.8% on chart tasks. We present an in-depth analysis of the effects of different visual edits, and reasons why ReFocus can improve the performance without introducing additional information. Further, we collect a 14k training set using ReFocus, and prove that such visual chain-of-thought with intermediate information offers a better supervision than standard VQA data, reaching a 8.0% average gain over the same model trained with QA pairs and 2.6% over CoT.

[Arxiv](https://arxiv.org/abs/2501.05452)