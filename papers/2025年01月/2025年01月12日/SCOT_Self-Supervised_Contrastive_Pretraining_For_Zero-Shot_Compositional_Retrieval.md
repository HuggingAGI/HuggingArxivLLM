# SCOT: 自监督对比预训练助力零-shot组合检索

发布时间：2025年01月12日

`LLM应用` `电子商务` `图像检索`

> SCOT: Self-Supervised Contrastive Pretraining For Zero-Shot Compositional Retrieval

# 摘要

> 组合图像检索（CIR）是一种多模态任务，模型通过结合查询图像和用户提供的文本修改来检索目标图像。CIR广泛应用于产品检索（如电子商务）和网络搜索等领域。现有方法主要依赖全监督学习，模型在标记的三元组数据集（如FashionIQ和CIRR）上训练，但这面临两大挑战：一是构建三元组数据集费时费力；二是模型对未见过的对象和领域泛化能力不足。为此，我们提出了SCOT（自监督组合训练），一种创新的零-shot组合预训练策略，利用大规模图像-文本对数据集和大型语言模型的生成能力，对比训练嵌入组合网络。具体而言，我们证明，在大规模对比预训练的视觉-语言模型中，文本嵌入可作为组合预训练中的代理目标监督，替代目标图像嵌入。在零-shot场景下，该策略在FashionIQ和CIRR等标准基准测试中超越了SOTA零-shot组合检索方法及许多全监督方法。

> Compositional image retrieval (CIR) is a multimodal learning task where a model combines a query image with a user-provided text modification to retrieve a target image. CIR finds applications in a variety of domains including product retrieval (e-commerce) and web search. Existing methods primarily focus on fully-supervised learning, wherein models are trained on datasets of labeled triplets such as FashionIQ and CIRR. This poses two significant challenges: (i) curating such triplet datasets is labor intensive; and (ii) models lack generalization to unseen objects and domains. In this work, we propose SCOT (Self-supervised COmpositional Training), a novel zero-shot compositional pretraining strategy that combines existing large image-text pair datasets with the generative capabilities of large language models to contrastively train an embedding composition network. Specifically, we show that the text embedding from a large-scale contrastively-pretrained vision-language model can be utilized as proxy target supervision during compositional pretraining, replacing the target image embedding. In zero-shot settings, this strategy surpasses SOTA zero-shot compositional retrieval methods as well as many fully-supervised methods on standard benchmarks such as FashionIQ and CIRR.

[Arxiv](https://arxiv.org/abs/2501.08347)