# 无价之宝：多模态提取 TikTok 影响者表达的人类价值观

发布时间：2025年01月20日

`LLM应用

理由：这篇论文主要探讨了如何使用掩码语言模型和大型语言模型（LLM）来检测TikTok视频中隐含的价值观。研究涉及了LLM的应用，特别是在价值观提取和文本分析方面的应用。虽然论文也涉及了数据集和模型比较，但其核心是LLM在实际问题中的应用，因此归类为“LLM应用”更为合适。` `社交媒体`

> The Value of Nothing: Multimodal Extraction of Human Values Expressed by TikTok Influencers

# 摘要

> # 摘要
社会和个人的价值观通过互动和接触传递给年轻一代。传统上，儿童和青少年从父母、教育者或同龄人那里学习价值观。如今，社交平台成为青少年（和成年人）消费信息的主要渠道，既是主要的娱乐媒介，也可能是他们学习不同价值观的媒介。本文从针对儿童和青少年的网络影响者上传的TikTok视频中提取隐含的价值观。我们整理了一个包含数百个TikTok视频的数据集，并根据Schwartz的个人价值观理论对它们进行了注释。随后，我们尝试了一系列掩码语言模型和大型语言模型，探索如何检测价值观。具体来说，我们采用了两种方法——直接从视频中提取价值观和两步法，即先将视频转换为详细的脚本，再提取价值观。
  实验结果表明，两步法的表现显著优于直接法，并且使用可训练的掩码语言模型作为第二步显著优于多个大型语言模型的少样本应用。我们进一步讨论了微调的影响，并比较了不同模型在识别TikTok中存在的或矛盾的价值观方面的表现。最后，我们分享了第一个价值观注释的TikTok视频数据集。我们的研究为基于视频的社交平台上的影响力和价值观传递的进一步研究奠定了基础。

> Societal and personal values are transmitted to younger generations through interaction and exposure. Traditionally, children and adolescents learned values from parents, educators, or peers. Nowadays, social platforms serve as a significant channel through which youth (and adults) consume information, as the main medium of entertainment, and possibly the medium through which they learn different values. In this paper we extract implicit values from TikTok movies uploaded by online influencers targeting children and adolescents. We curated a dataset of hundreds of TikTok movies and annotated them according to the Schwartz Theory of Personal Values. We then experimented with an array of Masked and Large language model, exploring how values can be detected. Specifically, we considered two pipelines -- direct extraction of values from video and a 2-step approach in which videos are first converted to elaborated scripts and then values are extracted.
  Achieving state-of-the-art results, we find that the 2-step approach performs significantly better than the direct approach and that using a trainable Masked Language Model as a second step significantly outperforms a few-shot application of a number of Large Language Models. We further discuss the impact of fine-tuning and compare the performance of the different models on identification of values present or contradicted in the TikTok. Finally, we share the first values-annotated dataset of TikTok videos. Our results pave the way to further research on influence and value transmission in video-based social platforms.

[Arxiv](https://arxiv.org/abs/2501.11770)