# 来源框架设计会导致大型语言模型的系统性评估偏差问题

发布时间：2025年05月14日

`LLM理论` `社会科学` `公共政策`

> Source framing triggers systematic evaluation bias in Large Language Models

# 摘要

> 大型语言模型（LLMs）不仅用于生成文本，还用于评估文本，这引发了对其判断是否一致、公平且不受框架效应影响的迫切问题。本研究系统考察了四个最先进LLMs（OpenAI o3-mini、Deepseek Reasoner、xAI Grok 2和Mistral）在评估4,800个涉及社会、政治和公共健康的叙述性陈述时的表现，共完成192,000次评估。我们通过操控陈述的披露来源，研究将其归因于另一个LLM或特定国籍的人类作者对评估结果的影响。结果发现，在匿名条件下，不同LLMs在各个主题上表现出高度的一致性。然而，当引入来源框架后，这种一致性消失。我们发现，将陈述归因于中国个人会显著降低所有模型的一致性得分，尤其是Deepseek Reasoner。研究结果表明，框架效应深刻影响文本评估，这对LLM中介信息系统的完整性和中立性具有重大意义。

> Large Language Models (LLMs) are increasingly used not only to generate text but also to evaluate it, raising urgent questions about whether their judgments are consistent, unbiased, and robust to framing effects. In this study, we systematically examine inter- and intra-model agreement across four state-of-the-art LLMs (OpenAI o3-mini, Deepseek Reasoner, xAI Grok 2, and Mistral) tasked with evaluating 4,800 narrative statements on 24 different topics of social, political, and public health relevance, for a total of 192,000 assessments. We manipulate the disclosed source of each statement to assess how attribution to either another LLM or a human author of specified nationality affects evaluation outcomes. We find that, in the blind condition, different LLMs display a remarkably high degree of inter- and intra-model agreement across topics. However, this alignment breaks down when source framing is introduced. Here we show that attributing statements to Chinese individuals systematically lowers agreement scores across all models, and in particular for Deepseek Reasoner. Our findings reveal that framing effects can deeply affect text evaluation, with significant implications for the integrity, neutrality, and fairness of LLM-mediated information systems.

[Arxiv](https://arxiv.org/abs/2505.13488)