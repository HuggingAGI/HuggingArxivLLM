# LLM4CD：借助大型语言模型实现开放世界知识增强的认知诊断

发布时间：2025年05月14日

`LLM应用` `智能教育`

> LLM4CD: Leveraging Large Language Models for Open-World Knowledge Augmented Cognitive Diagnosis

# 摘要

> 认知诊断（CD）在智能教育中发挥着关键作用，通过分析学生的考试历史来评估他们对知识概念的理解。然而，现有CD方法仅基于ID关系建模学生、练习和知识概念，忽视了教育数据中的丰富语义关系。此外，现代智能辅导系统（ITS）经常新增学生和练习，这对基于ID的方法来说是巨大挑战。大型语言模型（LLMs）的出现为利用开放世界知识解决这一问题带来了希望。本文提出LLM4CD，即利用大型语言模型进行基于开放世界知识增强的认知诊断。我们的方法通过LLMs的开放世界知识构建具有认知表达力的文本表示，并将其编码以引入CD任务中的丰富语义信息。此外，我们提出了一种创新的双级编码器框架，通过宏观层面的认知文本编码器和微观层面的知识状态编码器建模学生的考试历史。这种方法以语义表示替代传统ID嵌入，使模型能够利用开放世界知识容纳新学生和练习，并有效解决冷启动问题。大量实验结果表明，我们的方法在多个真实世界数据集上始终优于之前的CD模型，充分验证了利用LLMs将丰富语义信息引入CD任务的有效性。

> Cognitive diagnosis (CD) plays a crucial role in intelligent education, evaluating students' comprehension of knowledge concepts based on their test histories. However, current CD methods often model students, exercises, and knowledge concepts solely on their ID relationships, neglecting the abundant semantic relationships present within educational data space. Furthermore, contemporary intelligent tutoring systems (ITS) frequently involve the addition of new students and exercises, a situation that ID-based methods find challenging to manage effectively. The advent of large language models (LLMs) offers the potential for overcoming this challenge with open-world knowledge. In this paper, we propose LLM4CD, which Leverages Large Language Models for Open-World Knowledge Augmented Cognitive Diagnosis. Our method utilizes the open-world knowledge of LLMs to construct cognitively expressive textual representations, which are then encoded to introduce rich semantic information into the CD task. Additionally, we propose an innovative bi-level encoder framework that models students' test histories through two levels of encoders: a macro-level cognitive text encoder and a micro-level knowledge state encoder. This approach substitutes traditional ID embeddings with semantic representations, enabling the model to accommodate new students and exercises with open-world knowledge and address the cold-start problem. Extensive experimental results demonstrate that our proposed method consistently outperforms previous CD models on multiple real-world datasets, validating the effectiveness of leveraging LLMs to introduce rich semantic information into the CD task.

[Arxiv](https://arxiv.org/abs/2505.13492)