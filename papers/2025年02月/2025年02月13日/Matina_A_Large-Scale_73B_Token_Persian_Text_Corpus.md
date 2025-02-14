# # 玛蒂娜：大规模的730亿标记波斯语文本语料库

发布时间：2025年02月13日

`LLM应用

理由：这篇论文专注于构建和评估一个高质量的波斯语数据集，用于训练和改进大型语言模型（LLMs）。它讨论了数据收集、预处理、数据质量以及在关键NLP任务上的应用，这些都是与LLM的应用和发展直接相关的。因此，它属于LLM应用类别。` `波斯语`

> Matina: A Large-Scale 73B Token Persian Text Corpus

# 摘要

> 文本语料库对训练摘要、翻译和大型语言模型（LLMs）等任务至关重要。尽管在单语和多语种数据集收集方面已做出诸多努力，但波斯语因数据收集和预处理资源有限而常代表性不足。现有的波斯语数据集通常规模较小、内容单一，主要由网络日志和新闻文章组成。高质量多样化数据的匮乏阻碍了波斯语NLP模型和开源LLMs的发展。鉴于模型性能高度依赖训练数据质量，我们通过推出Matina语料库来填补这一空白，这是一个经过精心预处理和去重的全新波斯语数据集，包含729亿个token，确保了高质量的数据。我们还通过在关键NLP任务上训练和评估基于transformer的模型来进一步评估其有效性。该数据集和预处理代码均为公开可用，研究人员可以在此基础上构建和改进这一资源，以推动未来波斯语NLP的发展。

> Text corpora are essential for training models used in tasks like summarization, translation, and large language models (LLMs). While various efforts have been made to collect monolingual and multilingual datasets in many languages, Persian has often been underrepresented due to limited resources for data collection and preprocessing. Existing Persian datasets are typically small and lack content diversity, consisting mainly of weblogs and news articles. This shortage of high-quality, varied data has slowed the development of NLP models and open-source LLMs for Persian. Since model performance depends heavily on the quality of training data, we address this gap by introducing the Matina corpus, a new Persian dataset of 72.9B tokens, carefully preprocessed and deduplicated to ensure high data quality. We further assess its effectiveness by training and evaluating transformer-based models on key NLP tasks. Both the dataset and preprocessing codes are publicly available, enabling researchers to build on and improve this resource for future Persian NLP advancements.

[Arxiv](https://arxiv.org/abs/2502.09188)