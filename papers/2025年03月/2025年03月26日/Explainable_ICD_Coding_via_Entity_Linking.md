# 基于实体链接的可解释 ICD 编码

发布时间：2025年03月26日

`LLM应用` `实体链接`

> Explainable ICD Coding via Entity Linking

# 摘要

> 临床编码是医疗领域中一项至关重要的任务，但传统方法在自动化临床编码时可能无法为实际工作中提供足够的显式证据支持。这种证据至关重要，因为医学编码人员必须确保输入的健康记录中至少存在一个显式的段落，能够证明某个代码的归属。因此，我们建议将此任务重新定义为一个实体链接问题，其中每个文档都会标注其对应的代码集及其相应的文本证据，从而促进更好的人机协作。通过利用大型语言模型（LLMs）的参数高效微调，结合受限解码，我们提出了三种解决此问题的方法，这些方法在消除临床提及的歧义方面被证明是有效的，并且在少样本场景下表现良好。

> Clinical coding is a critical task in healthcare, although traditional methods for automating clinical coding may not provide sufficient explicit evidence for coders in production environments. This evidence is crucial, as medical coders have to make sure there exists at least one explicit passage in the input health record that justifies the attribution of a code. We therefore propose to reframe the task as an entity linking problem, in which each document is annotated with its set of codes and respective textual evidence, enabling better human-machine collaboration. By leveraging parameter-efficient fine-tuning of Large Language Models (LLMs), together with constrained decoding, we introduce three approaches to solve this problem that prove effective at disambiguating clinical mentions and that perform well in few-shot scenarios.

[Arxiv](https://arxiv.org/abs/2503.20508)