# 数据增强能够实现针对特定标签生成同源蛋白质序列。

发布时间：2025年07月21日

`LLM应用` `生物信息学` `生成模型`

> Data augmentation enables label-specific generation of homologous protein sequences

# 摘要

> 从序列数据中准确标注和控制蛋白质功能仍是重大挑战，尤其是在同源家族中，标注序列稀缺且结构变异小。我们提出了一种基于表示学习的两阶段方法，用于蛋白质家族的半监督功能注释和条件序列生成。首先，蛋白质语言模型在大规模多样化序列数据上预训练，并可能通过对比学习微调，能提供稳健捕捉细粒度功能特异性的嵌入，即使标注数据有限也是如此。其次，我们利用推断出的注释训练一种感知注释的受限玻尔兹曼机，该模型能生成具有指定功能标签的合成序列。在多个蛋白质家族中，我们的方法实现了高精度注释，并支持生成功能连贯的序列。研究结果表明，结合自监督学习与轻量级监督能有效克服蛋白质功能预测和设计中的数据稀缺性。

> Accurately annotating and controlling protein function from sequence data remains a major challenge, particularly within homologous families where annotated sequences are scarce and structural variation is minimal. We present a two-stage approach for semi-supervised functional annotation and conditional sequence generation in protein families using representation learning. First, we demonstrate that protein language models, pretrained on large and diverse sequence datasets and possibly finetuned via contrastive learning, provide embeddings that robustly capture fine-grained functional specificities, even with limited labeled data. Second, we use the inferred annotations to train a generative probabilistic model, an annotation-aware Restricted Boltzmann Machine, capable of producing synthetic sequences with prescribed functional labels. Across several protein families, we show that this approach achieves highly accurate annotation quality and supports the generation of functionally coherent sequences. Our findings underscore the power of combining self-supervised learning with light supervision to overcome data scarcity in protein function prediction and design.

[Arxiv](https://arxiv.org/abs/2507.15651)