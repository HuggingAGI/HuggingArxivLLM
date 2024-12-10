# JAPAGEN：借助 LLM 生成日语训练数据集，实现高效的少/零样本学习

发布时间：2024年12月09日

`LLM应用` `语言任务`

> JAPAGEN: Efficient Few/Zero-shot Learning via Japanese Training Dataset Generation with LLM

# 摘要

> 最近，一些研究凸显了大型语言模型（LLMs）作为高效监督训练数据生成器的潜力，其优势包括提高推理效率、降低数据收集相关成本等。不过，这些研究大多聚焦于英语语言任务。在本文中，我们探讨了一个核心研究问题：LLMs 能否充当其他语言任务的出色训练数据生成器？具体而言，我们借助 LLMs 在少样本和零样本学习情境下，为六个不同的日本下游任务合成监督训练数据。随后，我们使用这些合成数据训练紧凑模型（如 BERT）。这种新颖的方法被称为 JAPAGEN。我们的实验发现表明，JAPAGEN 在需要正式文本输入的分类任务中表现强劲，与传统的 LLM 提示策略相比，成果颇具竞争力。

> Recently some studies have highlighted the potential of Large Language Models (LLMs) as effective generators of supervised training data, offering advantages such as enhanced inference efficiency and reduced costs associated with data collection. However, these studies have predominantly focused on English language tasks. In this paper, we address the fundamental research question: Can LLMs serve as proficient training data generators for other language tasks? Specifically, we leverage LLMs to synthesize supervised training data under few-shot and zero-shot learning scenarios across six diverse Japanese downstream tasks. Subsequently, we utilize this synthesized data to train compact models (e.g., BERT). This novel methodology is termed JAPAGEN. Our experimental findings underscore that JAPAGEN achieves robust performance in classification tasks that necessitate formal text inputs, demonstrating competitive results compared to conventional LLM prompting strategies.

[Arxiv](https://arxiv.org/abs/2412.06738)