# 大型语言模型（LLMs）能否胜任复杂的伦理困境分析？

发布时间：2025年05月12日

`LLM应用` `伦理学` `人工智能`

> Are LLMs complicated ethical dilemma analyzers?

# 摘要

> 大型语言模型（LLMs）能否模拟人类的伦理推理能力，并作为人类判断的可信代理？针对这一开放性问题，我们构建了一个包含196个真实世界伦理困境及其专家意见的基准数据集，每个案例细分为引言、关键因素、历史理论视角、解决策略和关键要点五个部分。同时，我们收集了非专家人类的回应进行对比，但由于篇幅限制，仅限于关键因素部分。我们采用基于BLEU、Damerau-Levenshtein距离、TF-IDF余弦相似度和通用句子编码器相似度的综合指标框架，评估了GPT-4o-mini、Claude-3.5-Sonnet、Deepseek-V3和Gemini-1.5-Flash等前沿LLMs。通过逆向排名对齐和成对AHP分析计算指标权重，使模型输出与专家回应的对比更加细致入微。研究发现，LLMs在词汇和结构对齐方面普遍优于非专家人类，其中GPT-4o-mini表现尤为稳定。然而，所有模型在历史背景和提出细致的解决策略方面仍显不足，这需要强大的上下文抽象能力。尽管人类回应的结构较为松散，但它们偶尔也能达到相似的语义相似度，展现出直觉性的道德推理能力。这些发现不仅揭示了LLMs在伦理决策方面的优势，也指出了其当前的局限性。

> One open question in the study of Large Language Models (LLMs) is whether they can emulate human ethical reasoning and act as believable proxies for human judgment. To investigate this, we introduce a benchmark dataset comprising 196 real-world ethical dilemmas and expert opinions, each segmented into five structured components: Introduction, Key Factors, Historical Theoretical Perspectives, Resolution Strategies, and Key Takeaways. We also collect non-expert human responses for comparison, limited to the Key Factors section due to their brevity. We evaluate multiple frontier LLMs (GPT-4o-mini, Claude-3.5-Sonnet, Deepseek-V3, Gemini-1.5-Flash) using a composite metric framework based on BLEU, Damerau-Levenshtein distance, TF-IDF cosine similarity, and Universal Sentence Encoder similarity. Metric weights are computed through an inversion-based ranking alignment and pairwise AHP analysis, enabling fine-grained comparison of model outputs to expert responses. Our results show that LLMs generally outperform non-expert humans in lexical and structural alignment, with GPT-4o-mini performing most consistently across all sections. However, all models struggle with historical grounding and proposing nuanced resolution strategies, which require contextual abstraction. Human responses, while less structured, occasionally achieve comparable semantic similarity, suggesting intuitive moral reasoning. These findings highlight both the strengths and current limitations of LLMs in ethical decision-making.

[Arxiv](https://arxiv.org/abs/2505.08106)