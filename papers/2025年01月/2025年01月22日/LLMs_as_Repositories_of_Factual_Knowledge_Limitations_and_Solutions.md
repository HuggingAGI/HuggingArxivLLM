# LLMs 作为事实知识库：挑战与应对

发布时间：2025年01月22日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）作为事实知识库的适用性，并评估了其在回答时间敏感问题时的准确性和一致性。研究还提出了一种新的微调方法（ENAF）来提升模型性能。这些内容涉及LLMs的理论基础、知识表示和模型性能的改进，因此应归类为“LLM理论”。` `知识库`

> LLMs as Repositories of Factual Knowledge: Limitations and Solutions

# 摘要

> LLMs 的知识来源于不同时间戳和媒体类型（如维基、社交媒体等）收集的实体事实数据快照。这些非结构化知识会随时间变化，且不同信息源间存在不一致性和不准确性。因此，模型在训练或推理时对实体的知识可能受到干扰，导致性能不稳定。本研究探讨了LLMs作为事实知识库的适用性，评估了24种最先进的LLMs在回答时间敏感问题时的准确性和一致性，尤其是在提示受到干扰时。我们还评估了现有方法在提升LLMs准确性和一致性方面的效果，并提出了一种名为“ENtity-Aware Fine-tuning”（ENAF）的软神经符号方法，通过在微调中引入实体结构化表示来提升模型性能。

> LLMs' sources of knowledge are data snapshots containing factual information about entities collected at different timestamps and from different media types (e.g. wikis, social media, etc.). Such unstructured knowledge is subject to change due to updates through time from past to present. Equally important are the inconsistencies and inaccuracies occurring in different information sources. Consequently, the model's knowledge about an entity may be perturbed while training over the sequence of snapshots or at inference time, resulting in inconsistent and inaccurate model performance. In this work, we study the appropriateness of Large Language Models (LLMs) as repositories of factual knowledge. We consider twenty-four state-of-the-art LLMs that are either closed-, partially (weights), or fully (weight and training data) open-source. We evaluate their reliability in responding to time-sensitive factual questions in terms of accuracy and consistency when prompts are perturbed. We further evaluate the effectiveness of state-of-the-art methods to improve LLMs' accuracy and consistency. We then propose "ENtity-Aware Fine-tuning" (ENAF), a soft neurosymbolic approach aimed at providing a structured representation of entities during fine-tuning to improve the model's performance.

[Arxiv](https://arxiv.org/abs/2501.12774)