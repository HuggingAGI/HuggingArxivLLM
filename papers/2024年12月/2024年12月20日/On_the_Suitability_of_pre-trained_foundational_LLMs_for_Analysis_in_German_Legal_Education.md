# 论预训练的基础大型语言模型于德国法律教育分析的适用性

发布时间：2024年12月20日

`LLM应用`

> On the Suitability of pre-trained foundational LLMs for Analysis in German Legal Education

# 摘要

> 我们指出，当下的开源基础大型语言模型（LLMs）具备指令能力和德国法律背景知识，足以在教育情境中开展部分法律分析。但在一些非常具体的任务里，比如“Gutachtenstil”评估风格组件的分类，或者像完整法律意见这类复杂情境中，模型能力就会失效。即便有拓展的上下文和有效的提示策略，它们也比不上词袋基线。为应对此情况，我们引入了一种基于检索增强生成的提示示例选择方法，这在高数据可用性场景中显著提升了预测效果。我们还进一步评估了预训练的LLMs在论点挖掘和自动作文评分这两项标准任务上的表现，发现其更为恰当。自始至终，在标记数据少或无的场景中，预训练的LLMs优于基线，思维链提示在零样本情况下进一步助力。

> We show that current open-source foundational LLMs possess instruction capability and German legal background knowledge that is sufficient for some legal analysis in an educational context. However, model capability breaks down in very specific tasks, such as the classification of "Gutachtenstil" appraisal style components, or with complex contexts, such as complete legal opinions. Even with extended context and effective prompting strategies, they cannot match the Bag-of-Words baseline. To combat this, we introduce a Retrieval Augmented Generation based prompt example selection method that substantially improves predictions in high data availability scenarios. We further evaluate the performance of pre-trained LLMs on two standard tasks for argument mining and automated essay scoring and find it to be more adequate. Throughout, pre-trained LLMs improve upon the baseline in scenarios with little or no labeled data with Chain-of-Thought prompting further helping in the zero-shot case.

[Arxiv](https://arxiv.org/abs/2412.15902)