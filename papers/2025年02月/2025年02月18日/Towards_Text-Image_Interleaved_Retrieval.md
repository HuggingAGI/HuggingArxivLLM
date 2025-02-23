# # 迈向文本与图像的交叉检索

发布时间：2025年02月18日

`LLM应用` `信息检索` `多模态处理`

> Towards Text-Image Interleaved Retrieval

# 摘要

> 现有的多模态信息检索研究大多局限于单图像输入，这限制了其在涉及多图像和文本-图像交错内容的实际应用中的潜力。为此，我们提出了文本-图像交错检索（TIIR）任务，其中查询和文档都是交错的文本-图像序列，模型需通过理解交错上下文的语义来进行有效检索。我们基于自然交错的wikiHow教程构建了TIIR基准，并设计了专门的管道生成交错查询。为了深入探索这一任务，我们对现成的检索器进行了适应性调整，并利用交错的多模态大型语言模型（MLLM）构建了密集基线。针对MLLM基TIIR模型中视觉令牌过多的问题，我们提出了一种创新的Matryoshka多模态嵌入器（MME），通过在不同粒度级别压缩视觉令牌数量来解决这一挑战。实验结果表明，简单地适应现有模型并不能保证获得一致的有效结果。我们的MME通过大幅减少视觉令牌数量，显著优于基线模型。我们进行了全面的分析，并计划发布数据集和代码以支持未来研究。

> Current multimodal information retrieval studies mainly focus on single-image inputs, which limits real-world applications involving multiple images and text-image interleaved content. In this work, we introduce the text-image interleaved retrieval (TIIR) task, where the query and document are interleaved text-image sequences, and the model is required to understand the semantics from the interleaved context for effective retrieval. We construct a TIIR benchmark based on naturally interleaved wikiHow tutorials, where a specific pipeline is designed to generate interleaved queries. To explore the task, we adapt several off-the-shelf retrievers and build a dense baseline by interleaved multimodal large language model (MLLM). We then propose a novel Matryoshka Multimodal Embedder (MME), which compresses the number of visual tokens at different granularity, to address the challenge of excessive visual tokens in MLLM-based TIIR models. Experiments demonstrate that simple adaption of existing models does not consistently yield effective results. Our MME achieves significant improvements over the baseline by substantially fewer visual tokens. We provide extensive analysis and will release the dataset and code to facilitate future research.

[Arxiv](https://arxiv.org/abs/2502.12799)