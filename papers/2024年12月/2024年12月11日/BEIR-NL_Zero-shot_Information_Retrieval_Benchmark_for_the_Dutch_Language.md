# BEIR-NL：针对荷兰语的零样本信息检索基准

发布时间：2024年12月11日

`LLM应用` `信息检索` `荷兰语`

> BEIR-NL: Zero-shot Information Retrieval Benchmark for the Dutch Language

# 摘要

> 零样本信息检索（IR）模型的评估常借助 BEIR 来进行，它是一个由多个数据集构成的大型且多元的基准，涵盖了不同领域的各类检索任务。尽管 BEIR 已成为零样本评估的标准基准，但其仅含英语内容，这降低了其对包括荷兰语在内的信息检索中弱势语言的实用性。为克服这一局限并推动荷兰语 IR 模型的发展，我们通过将公开可用的 BEIR 数据集自动翻译成荷兰语，推出了 BEIR-NL。利用 BEIR-NL，我们对众多的多语言密集排序和重排序模型，以及词汇 BM25 方法进行了评估。实验表明，BM25 仍是颇具竞争力的基准，只是被用于检索训练的更大规模密集模型超越。当与重排序模型结合时，BM25 能达到与最优密集排序模型相当的性能。此外，我们通过将部分数据集回译为英语，探究了翻译对数据的影响，发现密集方法和词汇方法的性能均有所下降，这表明通过翻译创建基准存在局限性。BEIR-NL 可在 Hugging Face 平台上公开获取。

> Zero-shot evaluation of information retrieval (IR) models is often performed using BEIR; a large and heterogeneous benchmark composed of multiple datasets, covering different retrieval tasks across various domains. Although BEIR has become a standard benchmark for the zero-shot setup, its exclusively English content reduces its utility for underrepresented languages in IR, including Dutch. To address this limitation and encourage the development of Dutch IR models, we introduce BEIR-NL by automatically translating the publicly accessible BEIR datasets into Dutch. Using BEIR-NL, we evaluated a wide range of multilingual dense ranking and reranking models, as well as the lexical BM25 method. Our experiments show that BM25 remains a competitive baseline, and is only outperformed by the larger dense models trained for retrieval. When combined with reranking models, BM25 achieves performance on par with the best dense ranking models. In addition, we explored the impact of translation on the data by back-translating a selection of datasets to English, and observed a performance drop for both dense and lexical methods, indicating the limitations of translation for creating benchmarks. BEIR-NL is publicly available on the Hugging Face hub.

[Arxiv](https://arxiv.org/abs/2412.08329)