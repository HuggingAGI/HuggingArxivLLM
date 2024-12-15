# 用于视觉语言组合理解的因果图形模型

发布时间：2024年12月12日

`LLM应用` `视觉语言模型` `组合任务`

> Causal Graphical Models for Vision-Language Compositional Understanding

# 摘要

> 近期工作经验证表明，视觉语言模型（VLMs）难以充分理解人类语言的组合特性，常把图像说明建模成“词袋”。所以，它们在组合任务中的表现欠佳，这类任务需要深入理解句子的不同实体（主语、动词等）以及它们之间的相互关系才能完成。在本文中，我们借助依赖解析器构建的因果图形模型（CGM）对文本和视觉标记间的依赖关系进行建模，并训练由 VLM 视觉编码器制约的解码器。与标准的自回归或并行预测不同，我们解码器的生成过程依照 CGM 结构进行部分排序。这种结构促使解码器仅学习句子中的主要因果依赖，摒弃虚假关联。通过在五个组合基准上开展的大量实验，我们表明，我们的方法大幅优于所有前沿的组合方法，而且也优于使用更大数据集训练的方法。

> Recent work has empirically shown that Vision-Language Models (VLMs) struggle to fully understand the compositional properties of the human language, usually modeling an image caption as a "bag of words". As a result, they perform poorly on compositional tasks, which require a deeper understanding of the different entities of a sentence (subject, verb, etc.) jointly with their mutual relationships in order to be solved. In this paper, we model the dependency relations among textual and visual tokens using a Causal Graphical Model (CGM), built using a dependency parser, and we train a decoder conditioned by the VLM visual encoder. Differently from standard autoregressive or parallel predictions, our decoder's generative process is partially-ordered following the CGM structure. This structure encourages the decoder to learn only the main causal dependencies in a sentence discarding spurious correlations. Using extensive experiments on five compositional benchmarks, we show that our method significantly outperforms all the state-of-the-art compositional approaches by a large margin, and it also improves over methods trained using much larger datasets.

[Arxiv](https://arxiv.org/abs/2412.09353)