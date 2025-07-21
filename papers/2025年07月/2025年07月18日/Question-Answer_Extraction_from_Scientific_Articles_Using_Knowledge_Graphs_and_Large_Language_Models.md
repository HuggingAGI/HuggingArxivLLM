# 基于知识图谱与大型语言模型的科学文章问答提取

发布时间：2025年07月18日

`LLM应用` `科学出版` `问答系统`

> Question-Answer Extraction from Scientific Articles Using Knowledge Graphs and Large Language Models

# 摘要

> 学者在阅读文章或将其纳入研究时，往往希望快速抓住其核心观点。本文提出了一种通过问答对（QA）形式，从科学文章中提取关键概念和贡献的方法。我们设计了两种生成QA对的方案。第一种方案基于文章内容，通过大型语言模型（LLM）生成问题，并根据问题的可答性进行排序，最后生成答案。然而，评估文章的新颖性需要参考现有文献。因此，我们提出了第二种方案，利用知识图谱（KG）生成QA对。我们通过在科学文章上微调实体关系（ER）抽取模型，构建知识图谱，并采用突出三元组提取方法，根据三元组在文章中的重要性与文献中的普遍程度，选择最相关的ER。评估结果表明，基于KG的方法能够有效捕捉文章的主要观点。研究还表明，对ER抽取模型进行科学语料库的微调，对于提取高质量的三元组至关重要。

> When deciding to read an article or incorporate it into their research, scholars often seek to quickly identify and understand its main ideas. In this paper, we aim to extract these key concepts and contributions from scientific articles in the form of Question and Answer (QA) pairs. We propose two distinct approaches for generating QAs. The first approach involves selecting salient paragraphs, using a Large Language Model (LLM) to generate questions, ranking these questions by the likelihood of obtaining meaningful answers, and subsequently generating answers. This method relies exclusively on the content of the articles. However, assessing an article's novelty typically requires comparison with the existing literature. Therefore, our second approach leverages a Knowledge Graph (KG) for QA generation. We construct a KG by fine-tuning an Entity Relationship (ER) extraction model on scientific articles and using it to build the graph. We then employ a salient triplet extraction method to select the most pertinent ERs per article, utilizing metrics such as the centrality of entities based on a triplet TF-IDF-like measure. This measure assesses the saliency of a triplet based on its importance within the article compared to its prevalence in the literature. For evaluation, we generate QAs using both approaches and have them assessed by Subject Matter Experts (SMEs) through a set of predefined metrics to evaluate the quality of both questions and answers. Our evaluations demonstrate that the KG-based approach effectively captures the main ideas discussed in the articles. Furthermore, our findings indicate that fine-tuning the ER extraction model on our scientific corpus is crucial for extracting high-quality triplets from such documents.

[Arxiv](https://arxiv.org/abs/2507.13827)