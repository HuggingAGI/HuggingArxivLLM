# 从多样性中汲取智慧：利用混合型人与LLM群体缓解偏见

发布时间：2025年05月18日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）中的偏见问题，并提出了一种通过响应聚合来缓解偏见的方法。研究集中在模型的行为和偏见缓解策略上，属于理论层面的探讨，因此归类为LLM理论。` `社会学`

> Wisdom from Diversity: Bias Mitigation Through Hybrid Human-LLM Crowds

# 摘要

> 大型语言模型（LLMs）尽管表现出色，但可能无意中延续数据中的偏见。通过分析LLMs对引发偏见的新闻标题的响应，我们发现这些模型往往会反映人类的偏见。为了解决这一问题，我们探索了通过响应聚合来缓解偏见的群体策略。我们首先证明，简单地对多个LLMs的响应进行平均，旨在利用“群体智慧”，但由于LLMs群体的多样性有限，这种方法可能会加剧现有偏见。相比之下，我们发现基于局部加权的聚合方法更能有效利用LLMs群体的智慧，同时实现偏见缓解和准确性提升。最后，认识到LLMs（准确性）和人类（多样性）的互补优势，我们证明包含两者的混合群体显著提升了性能，并进一步减少了与种族和性别相关背景中的偏见。

> Despite their performance, large language models (LLMs) can inadvertently perpetuate biases found in the data they are trained on. By analyzing LLM responses to bias-eliciting headlines, we find that these models often mirror human biases. To address this, we explore crowd-based strategies for mitigating bias through response aggregation. We first demonstrate that simply averaging responses from multiple LLMs, intended to leverage the "wisdom of the crowd", can exacerbate existing biases due to the limited diversity within LLM crowds. In contrast, we show that locally weighted aggregation methods more effectively leverage the wisdom of the LLM crowd, achieving both bias mitigation and improved accuracy. Finally, recognizing the complementary strengths of LLMs (accuracy) and humans (diversity), we demonstrate that hybrid crowds containing both significantly enhance performance and further reduce biases across ethnic and gender-related contexts.

[Arxiv](https://arxiv.org/abs/2505.12349)