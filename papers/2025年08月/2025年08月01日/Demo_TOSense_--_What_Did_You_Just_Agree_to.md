# 展示：TOSense —— 您刚刚同意了什么？

发布时间：2025年08月01日

`LLM应用

摘要中的论文描述了一个使用自然语言处理技术来帮助用户理解和解析服务条款（ToS）的系统。该系统利用了预训练的语言模型（如MiniLM和BART-encoder）来实现自动化的问答功能。虽然论文中没有明确提到使用大型语言模型（LLM），但其核心是利用自然语言处理技术来解决实际问题，因此可以归类为LLM的应用。` `在线服务`

> Demo: TOSense -- What Did You Just Agree to?

# 摘要

> # 摘要  
在线服务通常要求用户同意冗长晦涩的服务条款（ToS），这不仅造成了信息不对称，还带来了法律风险。本文提出了一款名为TOSense的Chrome插件，让用户能够用自然语言提问关于ToS的问题，并实时获得简洁明了的答案。该系统由两部分组成：一是自动提取ToS内容的爬虫“tos-crawl”，二是包含MiniLM语义检索和BART-encoder答案验证的轻量级语言模型管道。为了避免耗时耗力的手动标注，我们开发了一种创新的问题回答评估管道（QEP），通过聚类主题匹配生成合成问题并验证答案的正确性。在苹果、谷歌、X（原Twitter）、微软和网飞等五大平台上的实验结果表明，TOSense在不同主题聚类数量下均表现优异（最高准确率达44.5%）。在演示中，我们将现场展示TOSense的实际操作，参与者将能够亲身体验无缝内容提取、交互式问答以及新网站的即时索引功能。

> Online services often require users to agree to lengthy and obscure Terms of Service (ToS), leading to information asymmetry and legal risks. This paper proposes TOSense-a Chrome extension that allows users to ask questions about ToS in natural language and get concise answers in real time. The system combines (i) a crawler "tos-crawl" that automatically extracts ToS content, and (ii) a lightweight large language model pipeline: MiniLM for semantic retrieval and BART-encoder for answer relevance verification. To avoid expensive manual annotation, we present a novel Question Answering Evaluation Pipeline (QEP) that generates synthetic questions and verifies the correctness of answers using clustered topic matching. Experiments on five major platforms, Apple, Google, X (formerly Twitter), Microsoft, and Netflix, show the effectiveness of TOSense (with up to 44.5% accuracy) across varying number of topic clusters. During the demonstration, we will showcase TOSense in action. Attendees will be able to experience seamless extraction, interactive question answering, and instant indexing of new sites.

[Arxiv](https://arxiv.org/abs/2508.00659)