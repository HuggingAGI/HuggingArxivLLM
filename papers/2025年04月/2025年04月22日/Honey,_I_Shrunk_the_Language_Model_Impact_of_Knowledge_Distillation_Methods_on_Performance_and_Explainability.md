# 亲爱的，我把语言模型缩小了：知识蒸馏方法对性能与可解释性的影响

发布时间：2025年04月22日

`LLM理论` `人工智能` `问答系统`

> Honey, I Shrunk the Language Model: Impact of Knowledge Distillation Methods on Performance and Explainability

# 摘要

> 人工智能 (AI) 日益影响着现代社会，近期尤其得益于大型语言模型 (LLMs) 的重大进展。然而，LLMs 高昂的计算和存储需求仍限制了其在资源受限环境中的应用。知识蒸馏通过从大型教师模型训练小型学生模型来应对这一挑战。此前的研究为生成训练数据和训练学生模型提出了多种蒸馏方法。尽管这些方法具有相关性，但目前尚未对最先进蒸馏方法对模型性能和可解释性的影响进行全面研究和比较。本研究通过将反馈-修订提示应用于蒸馏数据生成，并整合现有方法用于训练，扩展了现有的方法集。针对这些方法，我们基于广泛使用的常识问答 (CQA) 数据集进行了系统性对比。我们在衡量性能时采用学生模型的准确率，同时借助基于人类的研究评估可解释性。我们贡献了新的蒸馏方法及其在性能和可解释性方面的对比。这将进一步推动小型语言模型的蒸馏研究，从而促进 LLM 技术的更广泛应用和更快普及。

> Artificial Intelligence (AI) has increasingly influenced modern society, recently in particular through significant advancements in Large Language Models (LLMs). However, high computational and storage demands of LLMs still limit their deployment in resource-constrained environments. Knowledge distillation addresses this challenge by training a small student model from a larger teacher model. Previous research has introduced several distillation methods for both generating training data and for training the student model. Despite their relevance, the effects of state-of-the-art distillation methods on model performance and explainability have not been thoroughly investigated and compared. In this work, we enlarge the set of available methods by applying critique-revision prompting to distillation for data generation and by synthesizing existing methods for training. For these methods, we provide a systematic comparison based on the widely used Commonsense Question-Answering (CQA) dataset. While we measure performance via student model accuracy, we employ a human-grounded study to evaluate explainability. We contribute new distillation methods and their comparison in terms of both performance and explainability. This should further advance the distillation of small language models and, thus, contribute to broader applicability and faster diffusion of LLM technology.

[Arxiv](https://arxiv.org/abs/2504.16056)