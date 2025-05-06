# 迈向更安全的预训练：在大规模网络数据集中分析并过滤有害内容，以构建负责任的大型语言模型

发布时间：2025年05月04日

`LLM应用` `数据安全` `内容安全`

> Towards Safer Pretraining: Analyzing and Filtering Harmful Content in Webscale datasets for Responsible LLMs

# 摘要

> 大型语言模型（LLMs）在实际应用中发挥着关键作用，它们通过Common Crawl、C4和FineWeb等大规模网络数据集进行预训练。然而，这些数据集虽然为高质量自然语言生成提供了必要语言数据，但也包含仇恨言论、错误信息和偏见叙事等有害内容。在这些未经过滤的数据上训练LLMs，可能导致有毒行为延续、错误信息传播及社会偏见放大，从而削弱公众对LLM应用的信任并引发伦理争议。本研究对这些数据集中的不当内容进行了全面分析，提出了基于网页意图的“主题相关”与“有毒”分类法。我们还开发了提示评估数据集、高精度主题相关与有毒提示（TTP）、基于Transformer的内容过滤模型（HarmFormer），并创建了多维度开放性毒性基准（HAVOC）。研究揭示了模型对对抗性有毒输入的响应机制。发布时，我们将开源C4数据集的完整模型信号。本研究为确保LLM预训练安全性提供了新见解，并为负责任的人工智能（RAI）合规性提供了重要资源。

> Large language models (LLMs) have become integral to various real-world applications, leveraging massive, web-sourced datasets like Common Crawl, C4, and FineWeb for pretraining. While these datasets provide linguistic data essential for high-quality natural language generation, they often contain harmful content, such as hate speech, misinformation, and biased narratives. Training LLMs on such unfiltered data risks perpetuating toxic behaviors, spreading misinformation, and amplifying societal biases which can undermine trust in LLM-driven applications and raise ethical concerns about their use. This paper presents a large-scale analysis of inappropriate content across these datasets, offering a comprehensive taxonomy that categorizes harmful webpages into Topical and Toxic based on their intent. We also introduce a prompt evaluation dataset, a high-accuracy Topical and Toxic Prompt (TTP), and a transformer-based model (HarmFormer) for content filtering. Additionally, we create a new multi-harm open-ended toxicity benchmark (HAVOC) and provide crucial insights into how models respond to adversarial toxic inputs. Upon publishing, we will also opensource our model signal on the entire C4 dataset. Our work offers insights into ensuring safer LLM pretraining and serves as a resource for Responsible AI (RAI) compliance.

[Arxiv](https://arxiv.org/abs/2505.02009)