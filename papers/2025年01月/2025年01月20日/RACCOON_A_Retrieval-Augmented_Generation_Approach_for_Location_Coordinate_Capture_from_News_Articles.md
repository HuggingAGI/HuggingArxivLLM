# RACCOON: 一种检索增强生成方法，用于从新闻文章中提取位置坐标

发布时间：2025年01月20日

`RAG

理由：这篇论文提出了一种名为 RACCOON 的地理编码方法，该方法利用检索增强生成（RAG）技术从新闻文章中提取地理位置。RAG 是一种结合了检索和生成的技术，通常用于增强语言模型的能力。因此，这篇论文属于 RAG 分类。` `地理信息系统` `灾害管理`

> RACCOON: A Retrieval-Augmented Generation Approach for Location Coordinate Capture from News Articles

# 摘要

> 地理编码能够自动从新闻报道中提取事件发生地的坐标，广泛应用于疫情情报和灾害管理。本文提出了一种名为 RACCOON 的开源地理编码方法，它通过检索增强生成（RAG）技术从新闻文章中提取地理位置。RACCOON 首先从位置数据库中检索候选位置及其相关信息，然后将这些信息与新闻文章一起输入到 LLM 中，生成精确的坐标。我们在三个数据集、两个 LLM 模型、三个基线方法以及多个组件消融测试中验证了 RACCOON 的有效性。据我们所知，RACCOON 是首个基于预训练 LLM 的 RAG 地理编码方法。

> Geocoding involves automatic extraction of location coordinates of incidents reported in news articles, and can be used for epidemic intelligence or disaster management. This paper introduces Retrieval-Augmented Coordinate Capture Of Online News articles (RACCOON), an open-source geocoding approach that extracts geolocations from news articles. RACCOON uses a retrieval-augmented generation (RAG) approach where candidate locations and associated information are retrieved in the form of context from a location database, and a prompt containing the retrieved context, location mentions and news articles is fed to an LLM to generate the location coordinates. Our evaluation on three datasets, two underlying LLMs, three baselines and several ablation tests based on the components of RACCOON demonstrate the utility of RACCOON. To the best of our knowledge, RACCOON is the first RAG-based approach for geocoding using pre-trained LLMs.

[Arxiv](https://arxiv.org/abs/2501.11440)