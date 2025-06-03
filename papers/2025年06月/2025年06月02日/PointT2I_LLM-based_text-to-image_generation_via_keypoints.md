# **# 基于关键点的LLM文本到图像生成方法：PointT2I**

发布时间：2025年06月02日

`LLM应用

摘要中提到，这篇论文讨论了文本到图像生成模型的进展，并提出了一种名为PointT2I的框架，该框架利用大型语言模型（LLM）来生成与输入提示中描述的人体姿态高度对应的图像。论文详细介绍了该框架的三个组成部分：关键点生成、图像生成和反馈系统，并强调了其无需任何微调即可通过文本提示生成姿态对齐图像的优势。因此，这篇论文属于LLM应用类别，因为它展示了大型语言模型在图像生成任务中的具体应用。

LLM应用` `计算机视觉` `人工智能`

> PointT2I: LLM-based text-to-image generation via keypoints

# 摘要

> 文本到图像（T2I）生成模型已取得显著进展，能够生成与输入提示高度匹配的高质量图像。然而，尽管T2I生成模型能够生成精细的图像，但在处理包含复杂概念（尤其是人体姿态）的输入提示时，仍面临生成准确图像的挑战。本文中，我们提出了PointT2I框架，该框架通过使用大型语言模型（LLM），能够有效生成与提示中描述的人体姿态高度对应的图像。PointT2I包含三个组成部分：关键点生成、图像生成和反馈系统。关键点生成部分利用LLM直接根据输入提示生成对应人体姿态的关键点，无需任何外部参考。随后，图像生成部分结合文本提示和生成的关键点，生成能够准确反映目标姿态的图像。为了优化前序阶段的输出，我们引入了一个基于LLM的反馈系统，用于评估生成内容与给定提示之间的语义一致性。我们的框架是首个无需任何微调，仅通过文本提示即可生成姿态对齐图像的方法，实现了基于LLM引导的关键点图像生成。

> Text-to-image (T2I) generation model has made significant advancements, resulting in high-quality images aligned with an input prompt. However, despite T2I generation's ability to generate fine-grained images, it still faces challenges in accurately generating images when the input prompt contains complex concepts, especially human pose. In this paper, we propose PointT2I, a framework that effectively generates images that accurately correspond to the human pose described in the prompt by using a large language model (LLM). PointT2I consists of three components: Keypoint generation, Image generation, and Feedback system. The keypoint generation uses an LLM to directly generate keypoints corresponding to a human pose, solely based on the input prompt, without external references. Subsequently, the image generation produces images based on both the text prompt and the generated keypoints to accurately reflect the target pose. To refine the outputs of the preceding stages, we incorporate an LLM-based feedback system that assesses the semantic consistency between the generated contents and the given prompts. Our framework is the first approach to leveraging LLM for keypoints-guided image generation without any fine-tuning, producing accurate pose-aligned images based solely on textual prompts.

[Arxiv](https://arxiv.org/abs/2506.01370)