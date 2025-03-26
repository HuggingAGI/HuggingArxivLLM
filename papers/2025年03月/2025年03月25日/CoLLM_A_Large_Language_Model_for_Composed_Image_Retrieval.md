# CoLLM：专为组合图像检索设计的大型语言模型

发布时间：2025年03月25日

`LLM应用` `跨模态处理`

> CoLLM: A Large Language Model for Composed Image Retrieval

# 摘要

> 基于组合的图像检索（CIR）是一项复杂的任务，旨在根据多模态查询检索图像。传统的训练数据由三元组组成，包括参考图像、对所需修改的文本描述以及目标图像，这些数据获取成本高昂且耗时。由于CIR数据集的稀缺性，零样本方法开始利用合成三元组或基于网络爬取的图像-文字描述对的视觉语言模型（VLMs）。然而，这些方法存在显著局限：合成三元组规模有限、缺乏多样性且修改文本不自然，而图像-文字描述对则因缺乏三元组数据而阻碍了多模态查询的联合嵌入学习。此外，现有方法难以处理复杂且微妙的修改文本，这些文本需要对视觉和语言模态进行复杂的融合与理解。

我们提出了CoLLM，一个一站式框架，有效克服这些限制。我们的方法从图像-文字描述对实时生成三元组，实现无需手动标注的监督训练。我们利用大型语言模型（LLMs）生成参考图像和修改文本的联合嵌入，促进更深层次的多模态融合。此外，我们引入了大规模数据集Multi-Text CIR（MTCIR），包含340万个样本，并优化现有CIR基准（CIRR和Fashion-IQ），以提升评估可靠性。

实验结果表明，CoLLM在多个CIR基准和设置中达到最新技术水平，MTCIR实现具有竞争力的结果，性能提升高达15%。我们的优化基准为CIR模型提供了更可靠的评估指标，推动了这一重要领域的发展。


> Composed Image Retrieval (CIR) is a complex task that aims to retrieve images based on a multimodal query. Typical training data consists of triplets containing a reference image, a textual description of desired modifications, and the target image, which are expensive and time-consuming to acquire. The scarcity of CIR datasets has led to zero-shot approaches utilizing synthetic triplets or leveraging vision-language models (VLMs) with ubiquitous web-crawled image-caption pairs. However, these methods have significant limitations: synthetic triplets suffer from limited scale, lack of diversity, and unnatural modification text, while image-caption pairs hinder joint embedding learning of the multimodal query due to the absence of triplet data. Moreover, existing approaches struggle with complex and nuanced modification texts that demand sophisticated fusion and understanding of vision and language modalities. We present CoLLM, a one-stop framework that effectively addresses these limitations. Our approach generates triplets on-the-fly from image-caption pairs, enabling supervised training without manual annotation. We leverage Large Language Models (LLMs) to generate joint embeddings of reference images and modification texts, facilitating deeper multimodal fusion. Additionally, we introduce Multi-Text CIR (MTCIR), a large-scale dataset comprising 3.4M samples, and refine existing CIR benchmarks (CIRR and Fashion-IQ) to enhance evaluation reliability. Experimental results demonstrate that CoLLM achieves state-of-the-art performance across multiple CIR benchmarks and settings. MTCIR yields competitive results, with up to 15% performance improvement. Our refined benchmarks provide more reliable evaluation metrics for CIR models, contributing to the advancement of this important field.

[Arxiv](https://arxiv.org/abs/2503.19910)