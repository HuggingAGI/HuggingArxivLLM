# LookAlike：数学选择题干扰项生成的一致性研究

发布时间：2025年05月03日

`LLM应用`

> LookAlike: Consistent Distractor Generation in Math MCQs

# 摘要

> 大型语言模型（LLMs）正被广泛应用于生成多选题（MCQs）的干扰项，特别是在数学教育等领域。然而，现有方法在确保生成的干扰项与学生常见错误保持一致方面存在局限。我们提出了LookAlike方法，通过偏好优化提升错误-干扰项的一致性。我们的两大主要创新在于：(a) 从模型不一致中挖掘合成偏好对；(b) 通过交替进行有监督微调（SFT）和直接偏好优化（DPO）来稳定训练。与依赖启发式或人工标注偏好数据的先前工作不同，LookAlike利用自身生成的不一致作为不受欢迎的样本，从而实现可扩展且稳定的训练。在包含1,400多个数学MCQ的真实数据集上进行评估，LookAlike在LLM作为评判标准的评估中，干扰项生成准确率为51.6%，错误生成准确率为57.2%，优于现有最优方法（45.6% / 47.7%）。这些改进凸显了基于偏好的正则化和不一致挖掘在大规模生成一致数学MCQ干扰项方面的有效性。

> Large language models (LLMs) are increasingly used to generate distractors for multiple-choice questions (MCQs), especially in domains like math education. However, existing approaches are limited in ensuring that the generated distractors are consistent with common student errors. We propose LookAlike, a method that improves error-distractor consistency via preference optimization. Our two main innovations are: (a) mining synthetic preference pairs from model inconsistencies, and (b) alternating supervised fine-tuning (SFT) with Direct Preference Optimization (DPO) to stabilize training. Unlike prior work that relies on heuristics or manually annotated preference data, LookAlike uses its own generation inconsistencies as dispreferred samples, thus enabling scalable and stable training. Evaluated on a real-world dataset of 1,400+ math MCQs, LookAlike achieves 51.6% accuracy in distractor generation and 57.2% in error generation under LLM-as-a-judge evaluation, outperforming an existing state-of-the-art method (45.6% / 47.7%). These improvements highlight the effectiveness of preference-based regularization and inconsistency mining for generating consistent math MCQ distractors at scale.

[Arxiv](https://arxiv.org/abs/2505.01903)