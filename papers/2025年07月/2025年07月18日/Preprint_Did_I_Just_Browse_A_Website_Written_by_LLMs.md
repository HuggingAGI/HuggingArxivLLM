# 预印本：我刚刚浏览的网站竟是LLM创作的吗？

发布时间：2025年07月18日

`LLM应用` `内容安全` `网络安全`

> Preprint: Did I Just Browse A Website Written by LLMs?

# 摘要

> 越来越多的网络内容由大型语言模型（LLMs）自动生成，几乎无需人工干预。我们称这种内容为“LLM主导型”内容。由于LLMs存在抄袭和捏造信息的倾向，LLM主导型内容可能不可靠且有悖伦理。然而，网站通常不会披露此类内容，而人类读者也难以辨别。因此，我们必须开发可靠的LLM主导型内容检测器。
    现有检测器在干净、散文类文本上表现良好，但面对复杂标记和多样文体的网络内容时，效果大打折扣。我们提出了一种高度可靠且可扩展的管道，用于对整个网站进行分类。我们并非简单地对每一页提取的文本进行分类，而是基于LLM文本检测器对多个散文类页面的输出结果，对每个网站进行分类。
    通过收集两个不同的真实数据集，总计120个网站，我们训练并评估了我们的检测器，并在测试中获得了100%的准确率。在实际应用中，我们在搜索引擎结果和Common Crawl存档中分别检测了1万个网站，发现其中相当一部分属于LLM主导型。我们发现，LLM主导型网站的 prevalence 正在增长，并且在搜索结果中排名靠前，这引发了关于它们对最终用户和整个网络生态系统影响的疑问。

> Increasingly, web content is automatically generated by large language models (LLMs) with little human input. We call this "LLM-dominant" content. Since LLMs plagiarize and hallucinate, LLM-dominant content can be unreliable and unethical. Yet, websites rarely disclose such content, and human readers struggle to distinguish it. Thus, we must develop reliable detectors for LLM-dominant content. However, state-of-the-art LLM detectors are insufficient, because they perform well mainly on clean, prose-like text, while web content has complex markup and diverse genres.
  We propose a highly reliable, scalable pipeline that classifies entire websites. Instead of naively classifying text extracted from each page, we classify each site based on an LLM text detector's outputs of multiple prose-like pages. We train and evaluate our detector by collecting 2 distinct ground truth datasets totaling 120 sites, and obtain 100% accuracies testing across them. In the wild, we detect a sizable portion of sites as LLM-dominant among 10k sites in search engine results and 10k in Common Crawl archives. We find LLM-dominant sites are growing in prevalence and rank highly in search results, raising questions about their impact on end users and the overall Web ecosystem.

[Arxiv](https://arxiv.org/abs/2507.13933)