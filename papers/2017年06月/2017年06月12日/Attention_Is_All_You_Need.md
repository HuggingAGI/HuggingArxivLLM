# 注意力即所需

发布时间：2017年06月12日

`LLM应用` `机器翻译`

> Attention Is All You Need

# 摘要

> 摘要：当前主流的序列转换模型基于编码器 - 解码器架构中的复杂循环或卷积神经网络。表现出色的模型还通过注意力机制连接编码器与解码器。我们提出了全新的简单网络架构——Transformer，其仅依靠注意力机制，完全舍弃了循环和卷积。在两项机器翻译任务中的实验显示，这些模型不仅质量更优，还更具并行性，且训练耗时大幅减少。我们的模型在 WMT 2014 英语到德语翻译任务中取得 28.4 BLEU 的成绩，比现有的最优结果（包括集成模型）高出 2 个 BLEU 以上。在 WMT 2014 英语到法语翻译任务中，我们的模型在 8 个 GPU 上训练 3.5 天后，创下了新的单模型最先进 BLEU 得分 41.8，其训练成本仅为文献中最优模型的一小部分。我们通过将 Transformer 成功应用于拥有大量和有限训练数据的英语成分句法分析，证明它能出色地推广到其他任务。

> 
Abstract:The dominant sequence transduction models are based on complex recurrent or convolutional neural networks in an encoder-decoder configuration. The best performing models also connect the encoder and decoder through an attention mechanism. We propose a new simple network architecture, the Transformer, based solely on attention mechanisms, dispensing with recurrence and convolutions entirely. Experiments on two machine translation tasks show these models to be superior in quality while being more parallelizable and requiring significantly less time to train. Our model achieves 28.4 BLEU on the WMT 2014 English-to-German translation task, improving over the existing best results, including ensembles by over 2 BLEU. On the WMT 2014 English-to-French translation task, our model establishes a new single-model state-of-the-art BLEU score of 41.8 after training for 3.5 days on eight GPUs, a small fraction of the training costs of the best models from the literature. We show that the Transformer generalizes well to other tasks by applying it successfully to English constituency parsing both with large and limited training data.
    

[Arxiv](https://arxiv.org/pdf/1706.03762)