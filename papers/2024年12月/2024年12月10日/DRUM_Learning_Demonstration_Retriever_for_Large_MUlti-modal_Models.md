# DRUM：大型多模态模型的学习演示检索工具

发布时间：2024年12月10日

`LLM应用` `视觉语言` `多模态模型`

> DRUM: Learning Demonstration Retriever for Large MUlti-modal Models

# 摘要

> 最近，大型语言模型（LLMs）借助上下文学习（ICL）在处理新任务时展现出了非凡的能力。在大型视觉语言模型（LVLMs）的研究中，实施 ICL 时，研究人员通常采用诸如在不同样本中使用固定演示，或者直接通过视觉语言嵌入模型选取演示等简单策略。然而，这些方法无法确保配置的演示契合 LVLMs 的需求。为解决此问题，我们现提出一个全新框架——用于大型多模态模型的演示检索器（DRUM），它对视觉语言嵌入模型进行微调，以更好地满足 LVLM 的需求。首先，假定给定一个嵌入模型，我们探讨了视觉语言任务的检索策略，并提议将图像和文本嵌入相连接以提升检索性能。其次，我们建议依据 LVLM 的反馈对嵌入模型检索到的演示进行重新排序，并计算列表排序损失来训练嵌入模型。第三，我们提出一种迭代演示挖掘策略来优化嵌入模型的训练。通过在 3 种视觉语言任务、7 个基准数据集上开展的大量实验，我们的 DRUM 框架被证实能通过检索更恰当的演示，有效地提升 LVLM 的上下文学习性能。

> Recently, large language models (LLMs) have demonstrated impressive capabilities in dealing with new tasks with the help of in-context learning (ICL). In the study of Large Vision-Language Models (LVLMs), when implementing ICL, researchers usually adopts the naive strategies like fixed demonstrations across different samples, or selecting demonstrations directly via a visual-language embedding model. These methods does not guarantee the configured demonstrations fit the need of the LVLMs. To address this issue, we now propose a novel framework, \underline{d}emonstration \underline{r}etriever for large m\underline{u}lti-modal \underline{m}odel (DRUM), which fine-tunes the visual-language embedding model to better meet the LVLM's needs. First, we discuss the retrieval strategies for a visual-language task, assuming an embedding model is given. And we propose to concate the image and text embeddings to enhance the retrieval performance. Second, we propose to re-rank the demonstrations retrieved by the embedding model via the LVLM's feedbacks, and calculate a list-wise ranking loss for training the embedding model. Third, we propose an iterative demonstration mining strategy to improve the training of the embedding model. Through extensive experiments on 3 types of visual-language tasks, 7 benchmark datasets, our DRUM framework is proven to be effective in boosting the LVLM's in-context learning performance via retrieving more proper demonstrations.

[Arxiv](https://arxiv.org/abs/2412.07619)