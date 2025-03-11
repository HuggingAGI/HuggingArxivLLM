# 大型语言模型的幻象：解构AI的迷思与真相

发布时间：2025年03月09日

`LLM理论`

> Delusions of Large Language Models

# 摘要

> 大型语言模型 (LLMs) 常常生成事实错误但看似合理的输出，这种现象被称为幻觉。我们发现了一种更为隐蔽的现象，即 LLM 妄想，即错误输出伴随着异常高的信心水平，使得它们更难被检测和缓解。与普通幻觉不同，妄想具有较低的不确定性，对模型可靠性构成了重大挑战。通过对不同模型家族和规模在多个问答任务上的实证分析，我们展示了妄想现象普遍且与幻觉不同。具有妄想的 LLM 表现出更低的诚实度，且更难通过微调或自我反思来克服。我们将妄想的形成与训练动力学和数据集噪声联系起来，并探索了检索增强生成和多智能体辩论等缓解策略以缓解妄想。通过系统地研究 LLM 妄想的本质、普遍性和缓解方法，我们的研究揭示了这一现象的根本原因，并为提高模型可靠性指明了未来方向。

> Large Language Models often generate factually incorrect but plausible outputs, known as hallucinations. We identify a more insidious phenomenon, LLM delusion, defined as high belief hallucinations, incorrect outputs with abnormally high confidence, making them harder to detect and mitigate. Unlike ordinary hallucinations, delusions persist with low uncertainty, posing significant challenges to model reliability. Through empirical analysis across different model families and sizes on several Question Answering tasks, we show that delusions are prevalent and distinct from hallucinations. LLMs exhibit lower honesty with delusions, which are harder to override via finetuning or self reflection. We link delusion formation with training dynamics and dataset noise and explore mitigation strategies such as retrieval augmented generation and multi agent debating to mitigate delusions. By systematically investigating the nature, prevalence, and mitigation of LLM delusions, our study provides insights into the underlying causes of this phenomenon and outlines future directions for improving model reliability.

[Arxiv](https://arxiv.org/abs/2503.06709)