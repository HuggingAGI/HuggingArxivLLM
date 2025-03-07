# 知识解耦协同学习：基于多语言大型模型的协作方法实现少样本多模态对话意图识别

发布时间：2025年03月06日

`LLM应用

这篇论文主要讨论了如何将大语言模型应用于多模态对话意图识别，并提出了一种新的方法来改进模型的性能。因此，它属于LLM应用类别。` `意图识别`

> Knowledge-Decoupled Synergetic Learning: An MLLM based Collaborative Approach to Few-shot Multimodal Dialogue Intention Recognition

# 摘要

> 少样本多模态对话意图识别是电商领域的重要挑战。以往方法主要通过后训练技术提升模型分类能力。然而，我们发现，少样本多模态对话意图识别的训练涉及两个相互关联的任务，导致多任务学习中的跷跷板效应。这一现象源于训练过程中权重矩阵更新叠加引发的知识干扰。为此，我们提出了知识解耦协同学习（KDSL），通过小模型将知识转化为可解释规则，结合大模型后训练，有效缓解这些问题。通过促进大、小多模态大语言模型在预测任务中的协作，我们的方法取得了显著改进。在两个真实淘宝数据集上，我们的方法在在线加权F1分数上分别比现有最优方法提升了6.37%和6.28%，充分验证了我们框架的有效性。

> Few-shot multimodal dialogue intention recognition is a critical challenge in the e-commerce domainn. Previous methods have primarily enhanced model classification capabilities through post-training techniques. However, our analysis reveals that training for few-shot multimodal dialogue intention recognition involves two interconnected tasks, leading to a seesaw effect in multi-task learning. This phenomenon is attributed to knowledge interference stemming from the superposition of weight matrix updates during the training process. To address these challenges, we propose Knowledge-Decoupled Synergetic Learning (KDSL), which mitigates these issues by utilizing smaller models to transform knowledge into interpretable rules, while applying the post-training of larger models. By facilitating collaboration between the large and small multimodal large language models for prediction, our approach demonstrates significant improvements. Notably, we achieve outstanding results on two real Taobao datasets, with enhancements of 6.37\% and 6.28\% in online weighted F1 scores compared to the state-of-the-art method, thereby validating the efficacy of our framework.

[Arxiv](https://arxiv.org/abs/2503.04201)