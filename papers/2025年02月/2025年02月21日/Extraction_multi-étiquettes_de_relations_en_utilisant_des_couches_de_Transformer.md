# 使用Transformer层进行多标签关系抽取

发布时间：2025年02月21日

`LLM应用

理由：这篇论文提出了一种基于BERT和Transformer架构的模型，用于法语文本的多标签关系抽取，并展示了其在实际任务中的应用效果，属于大型语言模型的应用领域。` `情报分析` `信息处理`

> Extraction multi-étiquettes de relations en utilisant des couches de Transformer

# 摘要

> 本文提出了一种名为 BTransformer18 的深度学习架构，专为法语文本的多标签关系抽取而设计。我们的方法巧妙地结合了 BERT 家族模型（包括 BERT、RoBERTa 以及法语模型 CamemBERT 和 FlauBERT）的上下文表示能力，与 Transformer 编码器捕捉长距离依赖关系的优势。在 TextMine'25 挑战的数据集上进行的实验表明，本模型表现优异，尤其采用 CamemBERT-Large 时，取得了高达 0.654 的宏 F1 分数，显著超越了 FlauBERT-Large 的表现。这一结果充分证明了我们的方法在情报报告中自动提取复杂关系方面的有效性。

> In this article, we present the BTransformer18 model, a deep learning architecture designed for multi-label relation extraction in French texts. Our approach combines the contextual representation capabilities of pre-trained language models from the BERT family - such as BERT, RoBERTa, and their French counterparts CamemBERT and FlauBERT - with the power of Transformer encoders to capture long-term dependencies between tokens. Experiments conducted on the dataset from the TextMine'25 challenge show that our model achieves superior performance, particularly when using CamemBERT-Large, with a macro F1 score of 0.654, surpassing the results obtained with FlauBERT-Large. These results demonstrate the effectiveness of our approach for the automatic extraction of complex relations in intelligence reports.

[Arxiv](https://arxiv.org/abs/2502.15619)