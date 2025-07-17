# 大型语言模型能否理解并运用专利法规，成功通过实用专利律师考试？

发布时间：2025年07月11日

`LLM应用`

> Can Large Language Models Understand As Well As Apply Patent Regulations to Pass a Hands-On Patent Attorney Test?

# 摘要

> # 法律领域中的大型语言模型应用与挑战

法律领域已在实际应用中采用了多种大型语言模型（LLMs），但它们的定量性能及其原因尚未得到充分探索。我们评估了多个开源和专有LLMs——包括GPT系列、Anthropic、Deepseek和Llama-3等变体——在欧洲专利律师资格考试（EQE）的部分内容上，旨在测试未来欧洲专利律师的能力。

评估结果显示，OpenAI o1以0.82的准确率和0.81的F1分数领先，而（亚马逊网络服务）AWS Llama 3.1 8B则以0.50的准确率 lagged，Python部署的Llama 3.1 8B得分为0.55。后两者的表现接近于在两个答案的强制选择设计中随机猜测。没有被评估的模型能够通过考试，因为准确率从未超过专业水平所需0.90的平均阈值——即使是那些被认为超越了博士学位和通过律师资格考试水平的模型。

GPT-4o在整合文本和图形方面表现出色，而Claude 3 Opus常常失去格式的一致性。人类专利专家评估了文本理由，并发现每个模型的各种关键不足。他们更看重答案的清晰度和法律推理，而非答案的原始正确性，这揭示了自动指标与专家判断之间的不一致。

模型输出对适度的温度变化和提示措辞敏感，这强调了专家监督的持续必要性。未来的工作应致力于逻辑一致性、强大的多模态能力和自适应提示，以达到人类水平的专利熟练度。

总之，尽管近期大型模型表现出色，但公众可能高估了它们的性能。要开发出虚拟专利律师，该领域还有很长的路要走。本文旨在指出需要解决的几个具体限制。

> The legal field already uses various large language models (LLMs) in actual applications, but their quantitative performance and reasons for it are underexplored. We evaluated several open-source and proprietary LLMs -- including GPT-series, Anthropic, Deepseek and Llama-3, variants -- on parts of the European Qualifying Examination (EQE) for future European Patent Attorneys. OpenAI o1 led with 0.82 accuracy and 0.81 F1 score, whereas (Amazon Web Services) AWS Llama 3.1 8B lagged at 0.50 accuracy, and a Python-deployed Llama 3.1 8B scored 0.55. The latter two are within the range of mere guessing for the two-answer forced-choice design. None of the evaluated models could have passed the examination fully, as accuracy never exceeded the average threshold of 0.90 required for professional-level standards -- also not models that are regularly promoted for their assumed beyond-PhD- and bar-admitted-lawyer-level performance. GPT-4o excelled at integrating text and graphics, while Claude 3 Opus often lost formatting coherence. Human patent experts evaluated the textual justifications and uncovered various critical shortcomings of each model. They valued clarity and legal rationale over the raw correctness of the answers, which revealed misalignment between automatic metrics and expert judgment. Model outputs were sensitive to modest temperature changes and prompt wording, which underscores the remaining necessity of expert oversight. Future work should target logical consistency, robust multimodality, and adaptive prompting to approach human-level patent proficiency. In summary, despite the outstanding performance of recent large models, the general public might overestimate their performance. The field has a long way to go to develop a virtual patent attorney. This paper wants to point out several specific limitations that need solutions.

[Arxiv](https://arxiv.org/abs/2507.10576)