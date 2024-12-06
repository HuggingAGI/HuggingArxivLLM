# MIND：借助多模态结构增强语言模型实现有效的错误分配检测

发布时间：2024年12月05日

`其他` `数字图书馆`

> MIND: Effective Incorrect Assignment Detection through a Multi-Modal Structure-Enhanced Language Model

# 摘要

> 学术出版物的迅猛增长，让在线数字图书馆中作者姓名的模糊问题愈发严重。尽管姓名消歧算法在不断进步，可累积的错误依旧损害着学术系统的可靠性。据估算，构建百万规模的 WhoIsWho 基准时，超过 10%的论文作者分配得以纠正。现有的检测错误分配的尝试，要么是基于语义，要么是基于图，都未能充分利用论文丰富的文本属性以及由论文属性共现所定义的隐含结构特征。为此，本文引入了一种结构增强型语言模型，它将基于图的方法中的关键结构特征与丰富论文属性中的细粒度语义特征相结合，用于检测错误分配。所提出的模型通过高效的多模态多轮指令调整框架进行训练，该框架融合了任务引导的指令调整、文本属性模态和结构模态。实验结果显示，我们的模型超越了以往的方法，在 2024 年 KDD 杯的排行榜上斩获顶级成绩。我们的代码已公开。

> The rapid growth of academic publications has exacerbated the issue of author name ambiguity in online digital libraries. Despite advances in name disambiguation algorithms, cumulative errors continue to undermine the reliability of academic systems. It is estimated that over 10% paper-author assignments are rectified when constructing the million-scale WhoIsWho benchmark. Existing endeavors to detect incorrect assignments are either semantic-based or graph-based approaches, which fall short of making full use of the rich text attributes of papers and implicit structural features defined via the co-occurrence of paper attributes. To this end, this paper introduces a structure-enhanced language model that combines key structural features from graph-based methods with fine-grained semantic features from rich paper attributes to detect incorrect assignments. The proposed model is trained with a highly effective multi-modal multi-turn instruction tuning framework, which incorporates task-guided instruction tuning, text-attribute modality, and structural modality. Experimental results demonstrate that our model outperforms previous approaches, achieving top performance on the leaderboard of KDD Cup 2024. Our code has been publicly available.

[Arxiv](https://arxiv.org/abs/2412.03930)