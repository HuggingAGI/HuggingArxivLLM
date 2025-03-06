# 构建并应用大规模粤语数据集，助力大型语言模型实现多任务处理

发布时间：2025年03月05日

`LLM应用` `语言处理`

> Developing and Utilizing a Large-Scale Cantonese Dataset for Multi-Tasking in Large Language Models

# 摘要

> 高质量的数据资源对大型语言模型（LLMs）的学习至关重要，尤其是针对像粤语这样的低资源语言。尽管粤语拥有超过8500万的母语使用者，但在自然语言处理（NLP）领域，粤语仍被视为低资源语言。这主要是因为普通话的主导地位、粤语使用者群体的分散性、字符编码和输入方式的多样性，以及海外粤语使用者更倾向于使用英语等因素。此外，粤语丰富的口语词汇、英语借词和混合使用的特点，进一步增加了语料收集和处理的难度。为了解决这些挑战，我们从开源语料库、香港特定论坛、维基百科和Common Crawl数据等多种来源收集粤语文本。通过语言过滤、质量过滤、内容过滤和去重等严格的数据处理步骤，我们成功构建了一个包含超过20亿个标记的高质量粤语语料库，用于训练大型语言模型。通过在精选粤语任务上进行监督微调（SFT），我们进一步优化了模型，使其在特定应用中表现更佳。训练完成后，该模型在四个粤语基准测试中达到了最先进的（SOTA）性能。经过我们数据集的训练后，该模型在其他主流语言任务上也表现出色。

> High-quality data resources play a crucial role in learning large language models (LLMs), particularly for low-resource languages like Cantonese. Despite having more than 85 million native speakers, Cantonese is still considered a low-resource language in the field of natural language processing (NLP) due to factors such as the dominance of Mandarin, lack of cohesion within the Cantonese-speaking community, diversity in character encoding and input methods, and the tendency of overseas Cantonese speakers to prefer using English. In addition, rich colloquial vocabulary of Cantonese, English loanwords, and code-switching characteristics add to the complexity of corpus collection and processing. To address these challenges, we collect Cantonese texts from a variety of sources, including open source corpora, Hong Kong-specific forums, Wikipedia, and Common Crawl data. We conduct rigorous data processing through language filtering, quality filtering, content filtering, and de-duplication steps, successfully constructing a high-quality Cantonese corpus of over 2 billion tokens for training large language models. We further refined the model through supervised fine-tuning (SFT) on curated Cantonese tasks, enhancing its ability to handle specific applications. Upon completion of the training, the model achieves state-of-the-art (SOTA) performance on four Cantonese benchmarks. After training on our dataset, the model also exhibits improved performance on other mainstream language tasks.

[Arxiv](https://arxiv.org/abs/2503.03702)