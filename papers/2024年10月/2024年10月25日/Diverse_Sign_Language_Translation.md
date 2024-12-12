# 多样化的手语翻译

发布时间：2024年10月25日

`LLM应用` `手语翻译` `语言模型`

> Diverse Sign Language Translation

# 摘要

> 如同口语一般，单个手语表达可能对应着多种有效的文本释义。所以，为手语翻译（SLT）模型学习严格的一一对应关系或许并不足够，尤其是在数据有限的情况下。在本项工作中，我们推出了多样化手语翻译（DivSLT）任务，旨在为手语视频生成多样且准确的译文。首先，我们运用大型语言模型（LLM）为广泛使用的 CSL-Daily 和 PHOENIX14T SLT 数据集生成多个参考。在此，仅邀请母语人士对不准确的参考进行修改，从而大幅提升标注效率。其次，我们提供了一个基准模型来推动此项任务的研究。具体而言，我们探究了多参考训练策略，让我们的 DivSLT 模型能够达成多样化的翻译。接着，为增强翻译的准确性，我们采用了最大奖励驱动的强化学习目标，以将翻译结果的奖励最大化。另外，我们利用多个指标来评估 DivSLT 任务的准确性、多样性和语义精准度。在丰富的数据集中的实验结果显示，我们的 DivSLT 方法不但实现了更优的翻译性能，还生成了多样的翻译结果。

> Like spoken languages, a single sign language expression could correspond to multiple valid textual interpretations. Hence, learning a rigid one-to-one mapping for sign language translation (SLT) models might be inadequate, particularly in the case of limited data. In this work, we introduce a Diverse Sign Language Translation (DivSLT) task, aiming to generate diverse yet accurate translations for sign language videos. Firstly, we employ large language models (LLM) to generate multiple references for the widely-used CSL-Daily and PHOENIX14T SLT datasets. Here, native speakers are only invited to touch up inaccurate references, thus significantly improving the annotation efficiency. Secondly, we provide a benchmark model to spur research in this task. Specifically, we investigate multi-reference training strategies to enable our DivSLT model to achieve diverse translations. Then, to enhance translation accuracy, we employ the max-reward-driven reinforcement learning objective that maximizes the reward of the translated result. Additionally, we utilize multiple metrics to assess the accuracy, diversity, and semantic precision of the DivSLT task. Experimental results on the enriched datasets demonstrate that our DivSLT method achieves not only better translation performance but also diverse translation results.

[Arxiv](https://arxiv.org/abs/2410.19586)