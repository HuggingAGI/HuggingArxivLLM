# FiVL：一个用于提升视觉 - 语言对齐效果的框架

发布时间：2024年12月19日

`LLM应用` `多模态推理`

> FiVL: A Framework for Improved Vision-Language Alignment

# 摘要

> 大型视觉语言模型（LVLMs）在融合视觉与文本输入进行多模态推理方面成果斐然。然而，一直存在的难题是，当两种模态对于得出准确答案都不可或缺时，要保证这些模型对视觉信息的利用能像对语言内容的利用一样高效。我们推测，当前 LVLMs 中之所以会出现幻觉，是因为缺乏有效的视觉基础。这一问题在视觉语言基准中也有所体现，即难以让图像成为准确生成答案必不可少的要素，在视觉问答任务中尤其如此。在本研究中，我们推出了 FiVL，这是一种构建数据集的新方法，旨在训练 LVLMs 以强化视觉基础，并评估其效果。这些数据集既能用于训练，又能用于评估 LVLM 将图像内容当作实质性证据而非单纯依赖语言先验的能力，从而洞察模型对视觉信息的依赖程度。为展示我们数据集的实用性，我们引入了一项创新的训练任务，其表现优于基线，同时还提供了一种验证方法和可解释性应用。代码可在 https://github.com/IntelLabs/fivl 获取。

> Large Vision Language Models (LVLMs) have achieved significant progress in integrating visual and textual inputs for multimodal reasoning. However, a recurring challenge is ensuring these models utilize visual information as effectively as linguistic content when both modalities are necessary to formulate an accurate answer. We hypothesize that hallucinations arise due to the lack of effective visual grounding in current LVLMs. This issue extends to vision-language benchmarks, where it is difficult to make the image indispensable for accurate answer generation, particularly in vision question-answering tasks. In this work, we introduce FiVL, a novel method for constructing datasets designed to train LVLMs for enhanced visual grounding and to evaluate their effectiveness in achieving it. These datasets can be utilized for both training and assessing an LVLM's ability to use image content as substantive evidence rather than relying solely on linguistic priors, providing insights into the model's reliance on visual information. To demonstrate the utility of our dataset, we introduce an innovative training task that outperforms baselines alongside a validation method and application for explainability. The code is available at https://github.com/IntelLabs/fivl.

[Arxiv](https://arxiv.org/abs/2412.14672)