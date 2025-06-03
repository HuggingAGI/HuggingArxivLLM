# 超越上下文学习：通过任务固有属性的指导原则对齐大型语言模型的长文本生成能力

发布时间：2025年06月01日

`LLM应用

摘要中讨论了上下文学习（ICL）在大型语言模型中的应用，特别是针对长文本生成任务的改进方法。LongGuide的提出旨在提升模型在总结等任务中的性能，属于具体的应用研究。` `文本生成`

> Beyond In-Context Learning: Aligning Long-form Generation of Large Language Models via Task-Inherent Attribute Guidelines

# 摘要

> 上下文学习（ICL）是大型预训练语言模型（LLMs）中一种重要但尚未完全理解的能力。它通过少量示例（称为演示）在无需微调的情况下显著提升任务性能。尽管在问答任务中表现有效，但ICL在长文本生成任务（如总结）中往往表现不佳。在合理现实的假设下，我们通过实证和理论分析表明，仅凭ICL演示不足以教会LLMs生成任务的语言和格式分布。我们主张明确暴露任务分布，并假设通过提示定义它们可以提升模型性能。为此，我们提出了LongGuide，它能高效生成两组并行的指南，分别捕捉任务语言和格式属性：（i）指标指南（MGs），指导模型优化自我评估指标；（ii）输出约束指南（OCGs），在词级和句级约束生成。LongGuide自动选择最佳指南组合，在零样本和少样本设置下，显著提升了强开源和闭源LLMs的性能（提升超5%）。我们证明LongGuide具有通用性，能被弱模型学习以增强强模型，并能与自动提示优化器协同整合。

> In-context learning (ICL) is an important yet not fully understood ability of pre-trained large language models (LLMs). It can greatly enhance task performance using a few examples, termed demonstrations, without fine-tuning. Although effective in question answering, ICL often underperforms in long-form generation tasks such as summarization. Under appropriately realistic assumptions, we empirically and theoretically show that ICL demonstrations alone are insufficient to teach LLMs the task language and format distributions for generation. We argue for explicit exposure to the task distributions and hypothesize that defining them by prompting enhances model performance. To this end, we present LongGuide, which efficiently generates two parallel streams of guidelines capturing task language and format properties: (i) Metric Guidelines (MGs) that instruct models to optimize self-evaluated metrics; and (ii) Output Constraint Guidelines (OCGs) that constrain generation at both token and sentence levels. LongGuide automatically selects the best combination of guidelines, improving both strong open- and closed-source LLMs by over 5% in both zero- and few-shot settings. We show that LongGuide is generalizable, learnable by weak models to enhance strong ones, and integrates synergistically with automatic prompt optimizers.

[Arxiv](https://arxiv.org/abs/2506.01265)