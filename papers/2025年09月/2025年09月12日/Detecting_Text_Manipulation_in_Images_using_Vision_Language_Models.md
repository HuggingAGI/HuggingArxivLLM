# 利用视觉语言模型检测图像文本篡改

发布时间：2025年09月12日

`LLM应用` `法律科技`

> Detecting Text Manipulation in Images using Vision Language Models

# 摘要

> 近期研究证实，大型视觉语言模型（VLMs或LVLMs）在图像篡改检测中表现出色。但这些研究大多忽略了文本篡改检测这一领域。为此，我们在多个文本篡改数据集上对闭源及开源VLMs展开分析，以填补这一研究空白。结果显示，开源模型虽日益逼近闭源模型，但与GPT-4o等闭源模型相比仍有差距。此外，我们还测试了专门针对图像篡改检测的VLMs在文本篡改检测任务中的性能，发现这类模型存在泛化能力不足的问题。我们进一步在真实场景文本和虚构身份证的篡改检测任务中对VLMs进行基准测试，后者模拟了现实中极具挑战性的滥用场景。

> Recent works have shown the effectiveness of Large Vision Language Models (VLMs or LVLMs) in image manipulation detection. However, text manipulation detection is largely missing in these studies. We bridge this knowledge gap by analyzing closed- and open-source VLMs on different text manipulation datasets. Our results suggest that open-source models are getting closer, but still behind closed-source ones like GPT- 4o. Additionally, we benchmark image manipulation detection-specific VLMs for text manipulation detection and show that they suffer from the generalization problem. We benchmark VLMs for manipulations done on in-the-wild scene texts and on fantasy ID cards, where the latter mimic a challenging real-world misuse.

[Arxiv](https://arxiv.org/abs/2509.10278)