# **不要对抗幻觉，善用幻觉：基于原子事实的自然语言推理方法评估图像真实性**

发布时间：2025年03月20日

`LLM应用

理由：这篇论文探讨了如何利用大型视觉-语言模型（LVLMs）和自然语言推理（NLI）来评估图像的真实性，属于将大型语言模型应用于具体任务的范畴。` `计算机视觉` `图像真实性评估`

> Don't Fight Hallucinations, Use Them: Estimating Image Realism using NLI over Atomic Facts

# 摘要

> 图像真实性的量化仍是人工智能领域的一大难题。例如，一张爱因斯坦手持智能手机的照片违背常识，因为现代智能手机是在爱因斯坦去世后才被发明的。我们提出了一种创新方法，利用大型视觉-语言模型（LVLMs）与自然语言推理（NLI）来评估图像的真实性。我们的方法基于这样一个观察：当面对违背常识的图像时，LVLMs可能会生成幻觉。通过使用LVLM从图像中提取原子事实，我们能够获得准确的事实与错误的幻觉的混合。随后，我们计算这些事实之间的成对蕴含分数，并将这些值聚合以得到一个单一的现实得分。这一过程旨在识别真实事实与幻觉元素之间的矛盾，从而揭示违背常识的图像。我们的方法在零样本模式下，在WHOOPS!数据集上实现了新的最先进性能。

> Quantifying the realism of images remains a challenging problem in the field of artificial intelligence. For example, an image of Albert Einstein holding a smartphone violates common-sense because modern smartphone were invented after Einstein's death. We introduce a novel method for assessing image realism using Large Vision-Language Models (LVLMs) and Natural Language Inference (NLI). Our approach is based on the premise that LVLMs may generate hallucinations when confronted with images that defy common sense. Using LVLM to extract atomic facts from these images, we obtain a mix of accurate facts and erroneous hallucinations. We proceed by calculating pairwise entailment scores among these facts, subsequently aggregating these values to yield a singular reality score. This process serves to identify contradictions between genuine facts and hallucinatory elements, signaling the presence of images that violate common sense. Our approach has achieved a new state-of-the-art performance in zero-shot mode on the WHOOPS! dataset.

[Arxiv](https://arxiv.org/abs/2503.15948)