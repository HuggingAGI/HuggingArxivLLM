# # 摘要  
通过多样性获得智慧：借助混合型人类与LLM群体减轻偏见影响

发布时间：2025年05月18日

`LLM理论

摘要中讨论了大型语言模型（LLMs）中的偏见问题，并探索了缓解偏见的策略。研究者分析了模型对偏见标题的响应，并提出了一种基于群体的策略，通过聚合多个模型的响应来减少偏见。他们探讨了不同聚合方法的效果，并提出了局部加权聚合方法。此外，他们还考虑了结合LLM和人类的混合方法来进一步减少偏见。这些内容涉及模型的内在行为、偏见来源及改进方法，属于LLM理论的范畴。` `公平性`

> Wisdom from Diversity: Bias Mitigation Through Hybrid Human-LLM Crowds

# 摘要

> 尽管大型语言模型（LLMs）性能卓越，但它们可能无意间延续了训练数据中的偏见。通过分析 LLM 对引发偏见的标题的响应，我们发现这些模型往往反映了人类的偏见。为了解决这一问题，我们探索了通过聚合响应来缓解偏见的基于群体的策略。我们首先证明，单纯地对多个 LLM 的响应取平均值，旨在利用“群体的智慧”，但由于 LLM 群体内部多样性有限，反而会加剧现有偏见。相比之下，我们展示了局部加权聚合方法更能有效利用 LLM 群体的智慧，既减少了偏见，又提高了准确性。最后，我们认识到 LLM（准确性）和人类（多样性）的互补优势，因此证明了同时包含两者的混合群体能够显著提升性能，并在种族和性别相关背景下进一步减少偏见。

> Despite their performance, large language models (LLMs) can inadvertently perpetuate biases found in the data they are trained on. By analyzing LLM responses to bias-eliciting headlines, we find that these models often mirror human biases. To address this, we explore crowd-based strategies for mitigating bias through response aggregation. We first demonstrate that simply averaging responses from multiple LLMs, intended to leverage the "wisdom of the crowd", can exacerbate existing biases due to the limited diversity within LLM crowds. In contrast, we show that locally weighted aggregation methods more effectively leverage the wisdom of the LLM crowd, achieving both bias mitigation and improved accuracy. Finally, recognizing the complementary strengths of LLMs (accuracy) and humans (diversity), we demonstrate that hybrid crowds containing both significantly enhance performance and further reduce biases across ethnic and gender-related contexts.

[Arxiv](https://arxiv.org/abs/2505.12349)