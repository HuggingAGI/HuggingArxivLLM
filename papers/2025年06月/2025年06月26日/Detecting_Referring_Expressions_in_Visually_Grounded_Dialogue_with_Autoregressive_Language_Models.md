# 视觉接地对话中指示表达式的检测：基于自回归语言模型的方法

发布时间：2025年06月26日

`LLM应用

摘要讨论了如何将大型语言模型（LLM）应用于视觉对话中的指代表达提取，属于应用层面的研究，因此归类为LLM应用。` `人机交互`

> Detecting Referring Expressions in Visually Grounded Dialogue with Autoregressive Language Models

# 摘要

> 本文探讨了仅基于文本的自回归语言建模方法在从视觉对话中提取指代表达方面的应用。具体而言，我们旨在研究仅凭语言上下文能够多大程度上帮助识别对话视觉上下文中具有可感知指代对象的提及。为此，我们通过对预训练大型语言模型（LLM）的适应性调整，使其能够通过对文本中下一个词汇的预测来标注对话过程中提及的范围边界，从而实现对提及跨度的相对粗粒度标注。研究发现，即使采用规模适中的LLM、相对较小的数据集以及参数高效的微调方法，仅基于文本的方法仍能取得有效成果，凸显了语言上下文在该任务中的重要性。然而，我们认为该任务本质上属于多模态问题，并探讨了单模态方法固有的局限性。

> In this paper, we explore the use of a text-only, autoregressive language modeling approach for the extraction of referring expressions from visually grounded dialogue. More specifically, the aim is to investigate the extent to which the linguistic context alone can inform the detection of mentions that have a (visually perceivable) referent in the visual context of the conversation. To this end, we adapt a pretrained large language model (LLM) to perform a relatively course-grained annotation of mention spans in unfolding conversations by demarcating mention span boundaries in text via next-token prediction. Our findings indicate that even when using a moderately sized LLM, relatively small datasets, and parameter-efficient fine-tuning, a text-only approach can be effective, highlighting the relative importance of the linguistic context for this task. Nevertheless, we argue that the task represents an inherently multimodal problem and discuss limitations fundamental to unimodal approaches.

[Arxiv](https://arxiv.org/abs/2506.21294)