# 利用下一个词预测实现大语言模型生成文本的无损压缩

发布时间：2025年05月07日

`LLM应用` `数据压缩` `生成式AI`

> Lossless Compression of Large Language Model-Generated Text via Next-Token Prediction

# 摘要

> 随着大型语言模型 (LLMs) 在各领域的广泛应用，LLM 生成的数据量激增。这凸显了在现代文本管理中对这类数据进行高效无损压缩的重要性。然而，与传统的人类或机器生成内容不同，压缩 LLM 生成数据面临独特挑战。传统机器生成数据通常结构化且简单，适合传统无损压缩器。而 LLM 生成数据复杂多样，需要新方法。本研究首次系统性探索针对 LLM 生成数据的无损压缩技术。由于 LLM 通过预测下一个词进行训练，我们发现 LLM 生成数据对其自身高度可预测。这种特性使 LLM 能够高效压缩其输出。通过实验，我们发现基于 LLM 的预测方法压缩率可达 20 倍以上，远超通用压缩器 Gzip 的 3 倍。这一优势在不同规模的 LLM 和数据集中均得以体现，证明了基于 LLM 的方法在生成式 AI 中的鲁棒性和实用性。

> As large language models (LLMs) continue to be deployed and utilized across domains, the volume of LLM-generated data is growing rapidly. This trend highlights the increasing importance of effective and lossless compression for such data in modern text management systems. However, compressing LLM-generated data presents unique challenges compared to traditional human- or machine-generated content. Traditional machine-generated data is typically derived from computational processes or device outputs, often highly structured and limited to low-level elements like labels or numerical values. This structure enables conventional lossless compressors to perform efficiently. In contrast, LLM-generated data is more complex and diverse, requiring new approaches for effective compression. In this work, we conduct the first systematic investigation of lossless compression techniques tailored specifically to LLM-generated data. Notably, because LLMs are trained via next-token prediction, we find that LLM-generated data is highly predictable for the models themselves. This predictability enables LLMs to serve as efficient compressors of their own outputs. Through extensive experiments with 14 representative LLMs and 8 LLM-generated datasets from diverse domains, we show that LLM-based prediction methods achieve remarkable compression rates, exceeding 20x, far surpassing the 3x rate achieved by Gzip, a widely used general-purpose compressor. Furthermore, this advantage holds across different LLM sizes and dataset types, demonstrating the robustness and practicality of LLM-based methods in lossless text compression under generative AI workloads.

[Arxiv](https://arxiv.org/abs/2505.06297)