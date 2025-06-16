# 别再全面学习，专注解决视觉幻觉问题

发布时间：2025年06月12日

`LLM应用` `计算机视觉` `视觉识别`

> Stop learning it all to mitigate visual hallucination, Focus on the hallucination target

# 摘要

> 多模态大型语言模型 (MLLMs) 在视觉-语言任务中常因幻觉问题生成与输入图像中不存在的对象相关的信息。这种幻觉严重影响了模型在需要精准对象识别的实用场景中的可靠性。为了解决这一难题，我们提出了 \mymethod\，一种通过专注于幻觉发生区域来减少幻觉的偏好学习方法。为此，我们构建了一个包含幻觉响应、正确响应和目标信息（即图像中存在的对象及其在响应中受幻觉影响的对应块位置）的数据集。通过将偏好学习方法限定在这些特定目标上，模型能够过滤掉不相关的信号，专注于纠正幻觉。这使模型能够仅关注相关的信息，从而生成更事实性的响应。实验结果表明，\mymethod\ 在多个视觉幻觉任务中有效减少了幻觉，显著提升了 MLLMs 的可靠性和性能，同时保持了整体性能的稳定。

> Multimodal Large Language Models (MLLMs) frequently suffer from hallucination issues, generating information about objects that are not present in input images during vision-language tasks. These hallucinations particularly undermine model reliability in practical applications requiring accurate object identification. To address this challenge, we propose \mymethod,\ a preference learning approach that mitigates hallucinations by focusing on targeted areas where they occur. To implement this, we build a dataset containing hallucinated responses, correct responses, and target information (i.e., objects present in the images and the corresponding chunk positions in responses affected by hallucinations). By applying a preference learning method restricted to these specific targets, the model can filter out irrelevant signals and focus on correcting hallucinations. This allows the model to produce more factual responses by concentrating solely on relevant information. Experimental results demonstrate that \mymethod\ effectively reduces hallucinations across multiple vision hallucination tasks, improving the reliability and performance of MLLMs without diminishing overall performance.

[Arxiv](https://arxiv.org/abs/2506.11417)