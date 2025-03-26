# 看图说话还是详细描述？巧妙提示视觉语言模型实现精准语义分割

发布时间：2025年03月25日

`LLM应用` `计算机视觉` `多模态`

> Show or Tell? Effectively prompting Vision-Language Models for semantic segmentation

# 摘要

> 大型视觉语言模型（VLMs）正日益被视为基础模型，能够通过提示解决多种任务，而无需针对特定任务进行训练。我们探讨了如何有效提示VLMs进行语义分割这一看似显而易见的问题。为此，我们系统评估了几种近期模型在基于文本或视觉提示下的分割性能，使用了分布外的MESS数据集。我们引入了一种可扩展的提示方案，即基于少量样本的提示式语义分割，灵感来源于开放词汇分割和少量样本学习。结果显示，VLMs的表现远逊于专为特定分割任务训练的专用模型，在交并比指标上平均落后约30%。此外，我们发现文本提示和视觉提示具有互补性：每种模式在许多例子上失败，而另一种模式却能成功。我们的分析表明，能够预见到最有效的提示模式可以带来11%的性能提升。受我们的发现启发，我们提出了PromptMatcher，这是一个无需训练的简单基线方法，结合了文本和视觉提示，在基于少量样本的提示式语义分割中取得了领先于最佳文本提示VLM 2.5%和最佳视觉提示VLM 3.5%的优异结果。

> Large Vision-Language Models (VLMs) are increasingly being regarded as foundation models that can be instructed to solve diverse tasks by prompting, without task-specific training. We examine the seemingly obvious question: how to effectively prompt VLMs for semantic segmentation. To that end, we systematically evaluate the segmentation performance of several recent models guided by either text or visual prompts on the out-of-distribution MESS dataset collection. We introduce a scalable prompting scheme, few-shot prompted semantic segmentation, inspired by open-vocabulary segmentation and few-shot learning. It turns out that VLMs lag far behind specialist models trained for a specific segmentation task, by about 30% on average on the Intersection-over-Union metric. Moreover, we find that text prompts and visual prompts are complementary: each one of the two modes fails on many examples that the other one can solve. Our analysis suggests that being able to anticipate the most effective prompt modality can lead to a 11% improvement in performance. Motivated by our findings, we propose PromptMatcher, a remarkably simple training-free baseline that combines both text and visual prompts, achieving state-of-the-art results outperforming the best text-prompted VLM by 2.5%, and the top visual-prompted VLM by 3.5% on few-shot prompted semantic segmentation.

[Arxiv](https://arxiv.org/abs/2503.19647)