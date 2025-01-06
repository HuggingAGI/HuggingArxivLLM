# MusicGen-Stem: 基于自回归模型的多音轨音乐生成与编辑

发布时间：2025年01月03日

`其他

理由：这篇论文主要讨论的是音乐生成模型，特别是多音轨生成模型，并涉及音乐源分离和音乐编辑。虽然使用了语言模型的技术，但其核心内容与自然语言处理（NLP）或大型语言模型（LLM）的应用、理论、Agent或RAG（Retrieval-Augmented Generation）没有直接关联。因此，将其分类为“其他”更为合适。` `生成模型`

> MusicGen-Stem: Multi-stem music generation and edition through autoregressive modeling

# 摘要

> 大多数音乐生成模型生成的是混合音轨（单声道或立体声），而我们提出了一种包含贝斯、鼓和其他音轨的多音轨生成模型，并学习它们之间的音乐依赖关系。我们为每个音轨训练了专门的压缩算法，将音乐转化为并行的标记流。随后，借助音乐源分离任务的最新进展，我们在大型数据集上训练了一个多流文本到音乐的语言模型。通过特定的条件方法，我们的模型能够编辑现有或生成歌曲中的贝斯、鼓或其他音轨，并支持迭代作曲（如在现有鼓的基础上生成贝斯）。这为音乐生成算法提供了更大的灵活性，据我们所知，这是首个开源的多音轨自回归音乐生成模型，能够实现高质量生成和连贯的源编辑。代码和模型权重将公开，样本可在https://simonrouard.github.io/musicgenstem/上查看。

> While most music generation models generate a mixture of stems (in mono or stereo), we propose to train a multi-stem generative model with 3 stems (bass, drums and other) that learn the musical dependencies between them. To do so, we train one specialized compression algorithm per stem to tokenize the music into parallel streams of tokens. Then, we leverage recent improvements in the task of music source separation to train a multi-stream text-to-music language model on a large dataset. Finally, thanks to a particular conditioning method, our model is able to edit bass, drums or other stems on existing or generated songs as well as doing iterative composition (e.g. generating bass on top of existing drums). This gives more flexibility in music generation algorithms and it is to the best of our knowledge the first open-source multi-stem autoregressive music generation model that can perform good quality generation and coherent source editing. Code and model weights will be released and samples are available on https://simonrouard.github.io/musicgenstem/.

[Arxiv](https://arxiv.org/abs/2501.01757)