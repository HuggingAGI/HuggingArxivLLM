# 大型语言模型偏见分析：中文宣传与反美情绪——DeepSeek-R1 与 ChatGPT o3-mini-high 对比研究

发布时间：2025年06月02日

`LLM应用` `公众理解` `模型比较`

> Analysis of LLM Bias (Chinese Propaganda & Anti-US Sentiment) in DeepSeek-R1 vs. ChatGPT o3-mini-high

# 摘要

> 大型语言模型（LLMs）日益影响公众理解和公民决策，然而，其意识形态中立性日益引发担忧。尽管现有研究探讨了LLM偏见的多种形式，但对具有不同地缘政治立场的模型——具体而言，中国系统模型与非中国模型——进行直接的跨语言比较仍存在空白。本研究通过系统评估DeepSeek-R1（中国对齐）与ChatGPT o3-mini-high（非中国）在中文宣传和反美情绪方面的表现，填补了这一空白。我们开发了一个包含1200个去情境化、以推理为导向的问题的新型语料库，这些问题源自中文新闻，以简体中文、繁体中文和英文呈现。通过结合基于评分标准的GPT-4o评分与人工标注的混合评估管道，我们评估了两个模型的7200个答案。研究结果揭示了显著的模型级别和语言依赖性偏见。与ChatGPT o3-mini-high相比，DeepSeek-R1在宣传和反美偏见的比例上显著更高，而后者在很大程度上没有反美情绪，宣传水平也较低。对于DeepSeek-R1，简体中文查询引发了最高的偏见率；这些偏见在繁体中文中有所减弱，并在英文中几乎消失。值得注意的是，DeepSeek-R1有时会用简体中文回答繁体中文查询，并在其中文答案中放大现有的中国对齐术语，展示了“无形扩音器”效果。此外，此类偏见不仅限于明显政治话题，还渗透到文化与生活方式内容，尤其是在DeepSeek-R1中表现尤为明显。

> Large language models (LLMs) increasingly shape public understanding and civic decisions, yet their ideological neutrality is a growing concern. While existing research has explored various forms of LLM bias, a direct, cross-lingual comparison of models with differing geopolitical alignments-specifically a PRC-system model versus a non-PRC counterpart-has been lacking. This study addresses this gap by systematically evaluating DeepSeek-R1 (PRC-aligned) against ChatGPT o3-mini-high (non-PRC) for Chinese-state propaganda and anti-U.S. sentiment. We developed a novel corpus of 1,200 de-contextualized, reasoning-oriented questions derived from Chinese-language news, presented in Simplified Chinese, Traditional Chinese, and English. Answers from both models (7,200 total) were assessed using a hybrid evaluation pipeline combining rubric-guided GPT-4o scoring with human annotation. Our findings reveal significant model-level and language-dependent biases. DeepSeek-R1 consistently exhibited substantially higher proportions of both propaganda and anti-U.S. bias compared to ChatGPT o3-mini-high, which remained largely free of anti-U.S. sentiment and showed lower propaganda levels. For DeepSeek-R1, Simplified Chinese queries elicited the highest bias rates; these diminished in Traditional Chinese and were nearly absent in English. Notably, DeepSeek-R1 occasionally responded in Simplified Chinese to Traditional Chinese queries and amplified existing PRC-aligned terms in its Chinese answers, demonstrating an "invisible loudspeaker" effect. Furthermore, such biases were not confined to overtly political topics but also permeated cultural and lifestyle content, particularly in DeepSeek-R1.

[Arxiv](https://arxiv.org/abs/2506.01814)