# 关于大型语言模型中锚定偏差的实验研究

发布时间：2024年12月09日

`LLM应用` `人工智能` `认知偏差`

> Anchoring Bias in Large Language Models: An Experimental Study

# 摘要

> 像 GPT-4 和 Gemini 这样的大型语言模型（LLMs），能够让机器生成和理解类人的文本，极大地推动了人工智能的进步。尽管它们能力出众，但 LLMs 也并非毫无局限，存在着各种偏见。虽然很多研究都探究了人口统计学方面的偏见，但 LLMs 中的认知偏见却未得到同等程度的深入审视。本研究聚焦于锚定偏差这一认知偏差，即初始信息会过度影响判断。借助实验数据集，我们考察了锚定偏差在 LLMs 中的体现，并验证了多种缓解策略的有效性。我们的发现凸显了 LLM 响应对于有偏差提示的敏感性。同时，实验表明，要减轻锚定偏差，需从全面的角度收集提示，以防 LLMs 被个别信息锚定，而像思维链、原则思考、忽略锚定提示和反思这类简单算法是远远不够的。

> Large Language Models (LLMs) like GPT-4 and Gemini have significantly advanced artificial intelligence by enabling machines to generate and comprehend human-like text. Despite their impressive capabilities, LLMs are not immune to limitations, including various biases. While much research has explored demographic biases, the cognitive biases in LLMs have not been equally scrutinized. This study delves into anchoring bias, a cognitive bias where initial information disproportionately influences judgment. Utilizing an experimental dataset, we examine how anchoring bias manifests in LLMs and verify the effectiveness of various mitigation strategies. Our findings highlight the sensitivity of LLM responses to biased hints. At the same time, our experiments show that, to mitigate anchoring bias, one needs to collect hints from comprehensive angles to prevent the LLMs from being anchored to individual pieces of information, while simple algorithms such as Chain-of-Thought, Thoughts of Principles, Ignoring Anchor Hints, and Reflection are not sufficient.

[Arxiv](https://arxiv.org/abs/2412.06593)