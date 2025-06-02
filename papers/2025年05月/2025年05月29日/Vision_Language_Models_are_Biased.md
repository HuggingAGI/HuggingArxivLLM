# # 视觉语言模型的偏见问题

发布时间：2025年05月29日

`LLM应用

论文摘要：大型语言模型（LLMs）从互联网汲取了海量知识，这不仅让它们在各类任务中表现出色，也可能导致输出错误或偏见。本研究聚焦于热门主题知识对视觉语言模型（VLMs）的影响，特别是在标准视觉任务中的表现。我们发现，即使是当前最先进的VLMs，在计数和识别任务上也存在明显偏见，例如无法正确识别Adidas标志上新增的一条杠，导致在涵盖动物、标志、国际象棋、棋盘游戏、视错觉及图案网格等7大领域的测试中，平均准确率仅为17.05%。有趣的是，即便是在反事实图像中加入如“Adidas”这样的文字描述，VLM的准确率还会进一步下降。更令人惊讶的是，即使要求模型复查结果或仅依赖图像细节，平均准确率也只能提升2个百分点。本研究不仅揭示了VLMs的一个独特失效模式，还提供了一个自动化框架来检测其偏见。相关代码和数据已开放，详情请访问vlmsarebiased.github.io。` `视觉识别` `模型评估`

> Vision Language Models are Biased

# 摘要

> 大型语言模型（LLMs）从互联网汲取了海量知识，这不仅让它们在各类任务中表现出色，也可能导致输出错误或偏见。本研究聚焦于热门主题知识对视觉语言模型（VLMs）的影响，特别是在标准视觉任务中的表现。我们发现，即使是当前最先进的VLMs，在计数和识别任务上也存在明显偏见，例如无法正确识别Adidas标志上新增的一条杠，导致在涵盖动物、标志、国际象棋、棋盘游戏、视错觉及图案网格等7大领域的测试中，平均准确率仅为17.05%。有趣的是，即便是在反事实图像中加入如“Adidas”这样的文字描述，VLM的准确率还会进一步下降。更令人惊讶的是，即使要求模型复查结果或仅依赖图像细节，平均准确率也只能提升2个百分点。本研究不仅揭示了VLMs的一个独特失效模式，还提供了一个自动化框架来检测其偏见。相关代码和数据已开放，详情请访问vlmsarebiased.github.io。

> Large language models (LLMs) memorize a vast amount of prior knowledge from the Internet that help them on downstream tasks but also may notoriously sway their outputs towards wrong or biased answers. In this work, we test how the knowledge about popular subjects hurt the accuracy of vision language models (VLMs) on standard, objective visual tasks of counting and identification. We find that state-of-the-art VLMs are strongly biased (e.g, unable to recognize a fourth stripe has been added to a 3-stripe Adidas logo) scoring an average of 17.05% accuracy in counting (e.g., counting stripes in an Adidas-like logo) across 7 diverse domains from animals, logos, chess, board games, optical illusions, to patterned grids. Insert text (e.g., "Adidas") describing the subject name into the counterfactual image further decreases VLM accuracy. The biases in VLMs are so strong that instructing them to double-check their results or rely exclusively on image details to answer improves counting accuracy by only +2 points, on average. Our work presents an interesting failure mode in VLMs and an automated framework for testing VLM biases. Code and data are available at: vlmsarebiased.github.io.

[Arxiv](https://arxiv.org/abs/2505.23941)