# 将“情境尖锐度”视为预警信号，我们从内在表征的视角探讨其在缓解大型语言模型生成幻觉问题上的作用。

发布时间：2024年03月03日

`LLM理论`

> In-Context Sharpness as Alerts: An Inner Representation Perspective for Hallucination Mitigation

# 摘要

> LLMs在生成内容时常会出现臆想和事实偏差，但我们对此背后的原因尚不明晰。本次研究独辟蹊径，从内部表示的角度剖析了LLM臆想产生的根源，并揭示出一个醒目的规律：相较于错误生成部分，正确生成的内容在上下文标记的隐藏状态中激活更为清晰、聚焦。借由这一新发现，我们创新性地提出了一个基于熵的指标，用于衡量上下文隐藏状态的“聚焦程度”，并将该指标融入解码流程，设计出一种约束性解码策略。实验证明，该方法在多个知识检索和臆想评测基准上表现出稳健的有效性，比如在TruthfulQA任务上提升了最高达8.6个百分点的成绩。我们坚信这项研究将深化我们对模型臆想现象的认知，并为解决臆想问题提供切实可行的方法。

> Large language models (LLMs) frequently hallucinate and produce factual errors, yet our understanding of why they make these errors remains limited. In this study, we delve into the underlying mechanisms of LLM hallucinations from the perspective of inner representations, and discover a salient pattern associated with hallucinations: correct generations tend to have sharper context activations in the hidden states of the in-context tokens, compared to the incorrect ones. Leveraging this insight, we propose an entropy-based metric to quantify the ``sharpness'' among the in-context hidden states and incorporate it into the decoding process to formulate a constrained decoding approach. Experiments on various knowledge-seeking and hallucination benchmarks demonstrate our approach's consistent effectiveness, for example, achieving up to an 8.6 point improvement on TruthfulQA. We believe this study can improve our understanding of hallucinations and serve as a practical solution for hallucination mitigation.

[Arxiv](https://arxiv.org/abs/2403.01548)