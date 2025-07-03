# # 外部信息对LLMs的立场检测真的有用吗？
外部信息对LLMs的立场检测真的有用吗？

发布时间：2025年07月02日

`LLM应用`

> Is External Information Useful for Stance Detection with LLMs?

# 摘要

> # 研究摘要
在立场检测任务中，文本会被分类为对目标持支持、反对或中立态度。先前研究发现，使用外部信息（如维基百科摘录）可以提升检测表现。然而，尽管大型语言模型（LLMs）在推理任务中应用广泛，但这些信息是否对其有益仍是一个开放问题。

本研究系统评估了维基百科和网络搜索中的外部信息如何影响八种LLMs在三个数据集（涵盖12个目标）上的立场检测。令人意外的是，我们发现这种信息在多数情况下反而降低了性能，导致宏F1分数下降高达27.9%。实验表明，LLMs更倾向于让预测结果与提供的信息立场和情感保持一致，而非依据文本真实立场。即使采用链式思考提示，性能下降的问题仍存，而微调虽能部分缓解，却无法完全消除这一现象。

我们的发现与此前关于BERT-based系统的研究形成鲜明对比，突显了基于LLM的立场分类器在信息偏见方面的潜在风险。代码可在GitHub上获取。


> In the stance detection task, a text is classified as either favorable, opposing, or neutral towards a target. Prior work suggests that the use of external information, e.g., excerpts from Wikipedia, improves stance detection performance. However, whether or not such information can benefit large language models (LLMs) remains an unanswered question, despite their wide adoption in many reasoning tasks. In this study, we conduct a systematic evaluation on how Wikipedia and web search external information can affect stance detection across eight LLMs and in three datasets with 12 targets. Surprisingly, we find that such information degrades performance in most cases, with macro F1 scores dropping by up to 27.9\%. We explain this through experiments showing LLMs' tendency to align their predictions with the stance and sentiment of the provided information rather than the ground truth stance of the given text. We also find that performance degradation persists with chain-of-thought prompting, while fine-tuning mitigates but does not fully eliminate it. Our findings, in contrast to previous literature on BERT-based systems which suggests that external information enhances performance, highlight the risks of information biases in LLM-based stance classifiers. Code is available at https://github.com/ngqm/acl2025-stance-detection.

[Arxiv](https://arxiv.org/abs/2507.01543)