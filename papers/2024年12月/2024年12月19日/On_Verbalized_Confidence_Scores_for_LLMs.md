# 关于 LLMs 的语言化置信分数

发布时间：2024年12月19日

`LLM应用` `语言模型` `不确定性量化`

> On Verbalized Confidence Scores for LLMs

# 摘要

> 大型语言模型（LLMs）的兴起并深度融入我们的日常生活，这使得努力提升其可信度变得极为关键。对 LLMs 进行不确定性量化，既能增强人类对其回应的信任，也能让 LLM 代理依据彼此的不确定性做出更明智的决策。为估算响应中的不确定性，常用内部令牌对数、特定任务的代理模型或多个响应的采样。本研究专注于让 LLM 自身以置信分数的形式表达不确定性，并将其作为输出令牌的一部分，这对于与提示和模型无关的不确定性量化且开销低而言，是一种颇具前景的方式。通过大量的基准测试，我们评估了针对不同数据集、模型和提示方法的口头表达置信分数的可靠性。结果显示，这些分数的可靠性很大程度上取决于模型的询问方式，但通过某些提示方法能够提取出校准良好的置信分数。我们认为，口头表达的置信分数未来有望成为一种简便、有效且通用的不确定性量化方法。我们的代码可在 https://github.com/danielyxyang/llm-verbalized-uq 获取。

> The rise of large language models (LLMs) and their tight integration into our daily life make it essential to dedicate efforts towards their trustworthiness. Uncertainty quantification for LLMs can establish more human trust into their responses, but also allows LLM agents to make more informed decisions based on each other's uncertainty. To estimate the uncertainty in a response, internal token logits, task-specific proxy models, or sampling of multiple responses are commonly used. This work focuses on asking the LLM itself to verbalize its uncertainty with a confidence score as part of its output tokens, which is a promising way for prompt- and model-agnostic uncertainty quantification with low overhead. Using an extensive benchmark, we assess the reliability of verbalized confidence scores with respect to different datasets, models, and prompt methods. Our results reveal that the reliability of these scores strongly depends on how the model is asked, but also that it is possible to extract well-calibrated confidence scores with certain prompt methods. We argue that verbalized confidence scores can become a simple but effective and versatile uncertainty quantification method in the future. Our code is available at https://github.com/danielyxyang/llm-verbalized-uq .

[Arxiv](https://arxiv.org/abs/2412.14737)