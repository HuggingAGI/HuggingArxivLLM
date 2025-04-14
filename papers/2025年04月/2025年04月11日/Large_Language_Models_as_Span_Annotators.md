# 大型语言模型：成为跨度标注器的得力助手

发布时间：2025年04月11日

`LLM应用`

> Large Language Models as Span Annotators

# 摘要

> 对于高质量文本，单一分值指标难以提供有效的反馈。而通过标注问题范围的跨度标注，则能有效指导改进并提供深入见解。过去，跨度标注主要依赖人工标注员或微调编码器模型。本研究利用大型语言模型（LLMs）实现了跨度标注的自动化。我们比较了专家或熟练众包标注员与开放和专有LLMs在三个任务上的表现：数据到文本生成评估、机器翻译评估及人类撰写文本中的宣传内容检测。实验结果表明，LLMs作为跨度标注器不仅易于实现，且相较于人工标注员更具成本效益。LLMs与熟练人类标注员达成了一定一致性，在某些情况下甚至接近标注员之间的平均一致性。定性分析显示，推理模型的表现优于指令微调模型，并能提供更有效的标注解释。我们发布了包含超过40,000个模型和人工标注的数据集，以支持进一步研究。

> For high-quality texts, single-score metrics seldom provide actionable feedback. In contrast, span annotation - pointing out issues in the text by annotating their spans - can guide improvements and provide insights. Until recently, span annotation was limited to human annotators or fine-tuned encoder models. In this study, we automate span annotation with large language models (LLMs). We compare expert or skilled crowdworker annotators with open and proprietary LLMs on three tasks: data-to-text generation evaluation, machine translation evaluation, and propaganda detection in human-written texts. In our experiments, we show that LLMs as span annotators are straightforward to implement and notably more cost-efficient than human annotators. The LLMs achieve moderate agreement with skilled human annotators, in some scenarios comparable to the average agreement among the annotators themselves. Qualitative analysis shows that reasoning models outperform their instruction-tuned counterparts and provide more valid explanations for annotations. We release the dataset of more than 40k model and human annotations for further research.

[Arxiv](https://arxiv.org/abs/2504.08697)