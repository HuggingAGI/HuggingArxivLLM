# 可解释抑郁症检测在临床访谈中的个性化检索增强生成

发布时间：2025年03月03日

`RAG` `心理健康`

> Explainable Depression Detection in Clinical Interviews with Personalized Retrieval-Augmented Generation

# 摘要

> 抑郁症是一种广泛存在的心理健康障碍，临床访谈是评估抑郁症的黄金标准。然而，由于依赖稀缺的专业人员，这凸显了自动化检测的必要性。当前系统主要采用缺乏可解释性的黑箱神经网络，而在心理健康领域，可解释性至关重要。一些改进可解释性的尝试使用了基于LLM的后验生成方法，但这些方法存在幻觉问题。为了解决这些局限性，我们提出了RED，一种用于可解释抑郁症检测的增强生成框架。RED从临床访谈记录中检索证据，为预测提供解释。传统的基于查询的检索系统采用一刀切的方法，这可能并不适合抑郁症检测，因为用户背景和情况各不相同。我们引入了一个个性化查询生成模块，该模块结合了标准查询和通过LLMs推断出的用户特定背景，使检索能够适应不同的个体情境。此外，为了提升LLMs在社交智能方面的能力，我们通过一个基于事件为中心的检索器从社交智能数据存储库中检索相关知识来增强LLMs。在真实世界基准测试中的实验结果表明，与神经网络和基于LLM的基线模型相比，RED表现出更好的效果。

> Depression is a widespread mental health disorder, and clinical interviews are the gold standard for assessment. However, their reliance on scarce professionals highlights the need for automated detection. Current systems mainly employ black-box neural networks, which lack interpretability, which is crucial in mental health contexts. Some attempts to improve interpretability use post-hoc LLM generation but suffer from hallucination. To address these limitations, we propose RED, a Retrieval-augmented generation framework for Explainable depression Detection. RED retrieves evidence from clinical interview transcripts, providing explanations for predictions. Traditional query-based retrieval systems use a one-size-fits-all approach, which may not be optimal for depression detection, as user backgrounds and situations vary. We introduce a personalized query generation module that combines standard queries with user-specific background inferred by LLMs, tailoring retrieval to individual contexts. Additionally, to enhance LLM performance in social intelligence, we augment LLMs by retrieving relevant knowledge from a social intelligence datastore using an event-centric retriever. Experimental results on the real-world benchmark demonstrate RED's effectiveness compared to neural networks and LLM-based baselines.

[Arxiv](https://arxiv.org/abs/2503.01315)