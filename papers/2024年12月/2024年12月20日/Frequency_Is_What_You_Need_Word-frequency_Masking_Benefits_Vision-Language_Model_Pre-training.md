# 频率至关重要：词频掩蔽对视觉语言模型的预训练有益

发布时间：2024年12月20日

`LLM应用` `计算机视觉`

> Frequency Is What You Need: Word-frequency Masking Benefits Vision-Language Model Pre-training

# 摘要

> 视觉语言模型（VLMs）若能缩小训练集规模，训练效率会更高。近期研究显示，在 VLM 训练时采用多种方式（如截断、随机掩码、块掩码和语法掩码）对文本进行掩码颇具益处。本文指出，最佳掩码策略会随训练周期而改变，且在训练周期充足时，单词频率信息是达至最佳性能的关键。在众多数据集上开展的实验彰显了我们名为带有单词频率掩码的对比语言 - 图像预训练（CLIPF）这一方法的优势。尤其在输入标记数量减少时，其优势更为显著。我们剖析了 CLIPF 与其他掩码方法对单词频率平衡的影响，并探讨了 CLIPF 在维持不同词性类别单词频率平衡方面的关键作用。

> Vision Language Models (VLMs) can be trained more efficiently if training sets can be reduced in size. Recent work has shown the benefits of masking text during VLM training using a variety of approaches: truncation, random masking, block masking and syntax masking. In this paper, we show that the best masking strategy changes over training epochs and that, given sufficient training epochs, word frequency information is what you need to achieve the best performance. Experiments on a large range of data sets demonstrate the advantages of our approach, called Contrastive Language-Image Pre-training with word Frequency Masking (CLIPF). The benefits are particularly evident as the number of input tokens decreases. We analyze the impact of CLIPF vs. other masking approaches on word frequency balance and discuss the apparently critical contribution of CLIPF in maintaining word frequency balance across POS categories.

[Arxiv](https://arxiv.org/abs/2412.16148)