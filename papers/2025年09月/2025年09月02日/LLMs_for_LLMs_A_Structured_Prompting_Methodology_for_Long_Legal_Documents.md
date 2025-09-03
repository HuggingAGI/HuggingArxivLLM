# LLMs for LLMs：面向长法律文档的结构化提示方法

发布时间：2025年09月02日

`LLM应用` `法律科技`

> LLMs for LLMs: A Structured Prompting Methodology for Long Legal Documents

# 摘要

> 大型语言模型（LLMs）的兴起深刻变革了多个领域，但其在法律领域的应用却因可靠性与透明度这两大关键问题更具挑战。本研究提出一种结构化提示方法，作为昂贵微调的可行替代方案，可处理CUAD数据集中的长法律文档以完成信息检索任务。具体而言，首先通过分块与增强系统对文档分块，解决长文档难题；随后结合设计的提示词将输入送入QWEN-2，为每个问题生成答案集；最后引入基于分布的定位与逆基数加权启发式方法，攻克候选选择问题。该方法借助通用模型提升长期可扩展性，通过提示工程增强可靠性，并以两种启发式策略减轻黑箱效应。尽管模型性能较先前方法提升9%、达最先进水平，却也凸显当前问答自动评估指标的局限，为未来研究指明方向。而本工作的核心价值，正在于揭示结构化提示工程作为一种实用且尚未充分挖掘的工具，在保障法律及其他领域AI问责与责任方面的巨大潜力。

> The rise of Large Language Models (LLMs) has had a profoundly transformative effect on a number of fields and domains. However, their uptake in Law has proven more challenging due to the important issues of reliability and transparency. In this study, we present a structured prompting methodology as a viable alternative to the often expensive fine-tuning, with the capability of tacking long legal documents from the CUAD dataset on the task of information retrieval. Each document is first split into chunks via a system of chunking and augmentation, addressing the long document problem. Then, alongside an engineered prompt, the input is fed into QWEN-2 to produce a set of answers for each question. Finally, we tackle the resulting candidate selection problem with the introduction of the Distribution-based Localisation and Inverse Cardinality Weighting heuristics. This approach leverages a general purpose model to promote long term scalability, prompt engineering to increase reliability and the two heuristic strategies to reduce the impact of the black box effect. Whilst our model performs up to 9\% better than the previously presented method, reaching state-of-the-art performance, it also highlights the limiting factor of current automatic evaluation metrics for question answering, serving as a call to action for future research. However, the chief aim of this work is to underscore the potential of structured prompt engineering as a useful, yet under-explored, tool in ensuring accountability and responsibility of AI in the legal domain, and beyond.

[Arxiv](https://arxiv.org/abs/2509.02241)