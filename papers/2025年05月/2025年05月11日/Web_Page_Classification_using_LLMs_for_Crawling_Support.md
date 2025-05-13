# # 网页分类：LLMs 在爬虫中的应用探索

发布时间：2025年05月11日

`LLM应用` `互联网技术` `网络爬虫`

> Web Page Classification using LLMs for Crawling Support

# 摘要

> 网络爬虫是一种用于收集网页的系统，高效爬取新页面需要合适的算法。尽管网站特征（如 XML 网站地图和过去页面更新频率）为访问新页面提供了重要线索，但它们在不同条件下的普遍应用具有挑战性。在本研究中，我们提出了一种方法，通过大型语言模型 (LLM) 将网页分类为“索引页面”和“内容页面”两类，并利用分类结果选择索引页面作为访问新页面的起点，从而高效地收集新页面。我们构建了一个具有自动标注的网页类型数据集，并从两个角度评估了我们的方法：页面类型分类性能和新页面覆盖率。实验结果表明，基于 LLM 的方法在两个评估指标上均优于基线方法。

> A web crawler is a system designed to collect web pages, and efficient crawling of new pages requires appropriate algorithms. While website features such as XML sitemaps and the frequency of past page updates provide important clues for accessing new pages, their universal application across diverse conditions is challenging. In this study, we propose a method to efficiently collect new pages by classifying web pages into two types, "Index Pages" and "Content Pages," using a large language model (LLM), and leveraging the classification results to select index pages as starting points for accessing new pages. We construct a dataset with automatically annotated web page types and evaluate our approach from two perspectives: the page type classification performance and coverage of new pages. Experimental results demonstrate that the LLM-based method outperformed baseline methods in both evaluation metrics.

[Arxiv](https://arxiv.org/abs/2505.06972)