# OpenCSG 中文语料库：专为 LLM 训练打造的高质量中文数据集系列

发布时间：2025年01月14日

`LLM理论

理由：这篇论文主要讨论了中文大型语言模型（LLMs）在预训练语料质量方面的挑战，并提出了一个高质量的中文语料库OpenCSG。论文的核心在于如何通过改进语料库的质量来提升LLMs的表现，这涉及到LLMs的理论基础，特别是预训练数据的质量和其对模型性能的影响。因此，这篇论文更适合归类为LLM理论。`

> OpenCSG Chinese Corpus: A Series of High-quality Chinese Datasets for LLM Training

# 摘要

> 大型语言模型（LLMs）展现了强大的能力，但其成功高度依赖预训练语料的质量。中文LLMs面临的一大挑战是高质量中文数据集的稀缺，这常常限制了它们的表现。为此，我们推出了OpenCSG中文语料库，这是一系列专为LLM预训练、后训练和微调设计的高质量数据集。该语料库包含Fineweb-edu-chinese、Fineweb-edu-chinese-v2、Cosmopedia-chinese和Smoltalk-chinese，各具特色：Fineweb-edu数据集聚焦于从多样中文网络资源中筛选的高质量内容；Cosmopedia-chinese提供合成的教科书风格数据，适合知识密集型训练；而Smoltalk-chinese则强调风格多样化的聊天格式数据。OpenCSG中文语料库以高质量文本、跨领域多样化覆盖以及可扩展、可复现的数据整理流程为特点。我们还进行了广泛的实验分析，包括对较小参数模型的评估，结果显示在C-Eval等任务中性能显著提升，充分证明了该语料库在训练中文LLMs方面的有效性。

> Large language models (LLMs) have demonstrated remarkable capabilities, but their success heavily relies on the quality of pretraining corpora. For Chinese LLMs, the scarcity of high-quality Chinese datasets presents a significant challenge, often limiting their performance. To address this issue, we propose the OpenCSG Chinese Corpus, a series of high-quality datasets specifically designed for LLM pretraining, post-training, and fine-tuning. This corpus includes Fineweb-edu-chinese, Fineweb-edu-chinese-v2, Cosmopedia-chinese, and Smoltalk-chinese, each with distinct characteristics: Fineweb-edu datasets focus on filtered, high-quality content derived from diverse Chinese web sources; Cosmopedia-chinese provides synthetic, textbook-style data for knowledge-intensive training; and Smoltalk-chinese emphasizes stylistic and diverse chat-format data. The OpenCSG Chinese Corpus is characterized by its high-quality text, diverse coverage across domains, and scalable, reproducible data curation processes. Additionally, we conducted extensive experimental analyses, including evaluations on smaller parameter models, which demonstrated significant performance improvements in tasks such as C-Eval, showcasing the effectiveness of the corpus for training Chinese LLMs.

[Arxiv](https://arxiv.org/abs/2501.08197)