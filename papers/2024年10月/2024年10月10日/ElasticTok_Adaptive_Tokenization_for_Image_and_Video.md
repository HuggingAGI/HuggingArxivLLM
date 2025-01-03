# ElasticTok: 图像与视频的自适应分词技术

发布时间：2024年10月10日

`其他

理由：这篇论文主要讨论的是视频标记化技术，特别是提出了一种名为ElasticTok的自适应标记生成方法。虽然文中提到了“智能体”和“多模态模型”，但核心内容并不直接涉及Agent、RAG、LLM应用或LLM理论。因此，将其归类为“其他”更为合适。` `视频处理` `多模态模型`

> ElasticTok: Adaptive Tokenization for Image and Video

# 摘要

> 高效视频标记化是构建通用视觉模型的关键瓶颈，尤其是在处理长视频序列时。现有方法通常将视频编码为固定数量的标记，标记过少会导致信息丢失，过多则会导致序列过长。为此，我们提出了ElasticTok，一种基于先前帧自适应生成可变数量标记的方法。通过引入随机丢弃标记的掩码技术，ElasticTok在计算上更具扩展性。在推理时，ElasticTok能够动态分配标记：复杂数据使用更多标记，简单数据则只需少量。我们在图像和视频上的实验验证了该方法的高效性，为未来开发更强大的多模态模型、世界模型和智能体奠定了基础。

> Efficient video tokenization remains a key bottleneck in learning general purpose vision models that are capable of processing long video sequences. Prevailing approaches are restricted to encoding videos to a fixed number of tokens, where too few tokens will result in overly lossy encodings, and too many tokens will result in prohibitively long sequence lengths. In this work, we introduce ElasticTok, a method that conditions on prior frames to adaptively encode a frame into a variable number of tokens. To enable this in a computationally scalable way, we propose a masking technique that drops a random number of tokens at the end of each frames's token encoding. During inference, ElasticTok can dynamically allocate tokens when needed -- more complex data can leverage more tokens, while simpler data only needs a few tokens. Our empirical evaluations on images and video demonstrate the effectiveness of our approach in efficient token usage, paving the way for future development of more powerful multimodal models, world models, and agents.

[Arxiv](https://arxiv.org/abs/2410.08368)