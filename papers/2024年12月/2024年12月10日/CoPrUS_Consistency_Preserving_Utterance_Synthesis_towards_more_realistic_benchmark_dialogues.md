# CoPrUS：致力于保持一致性的话语合成，从而打造更真实的基准对话

发布时间：2024年12月10日

`LLM应用` `对话系统` `数据集`

> CoPrUS: Consistency Preserving Utterance Synthesis towards more realistic benchmark dialogues

# 摘要

> 大规模的绿野仙踪式对话数据集已能助力基于深度学习的对话系统的训练。尽管作为基准数据集它们表现出色，但仍缺少某些类型的话语，若能补足则会更贴近现实。在本研究中，我们探究了在自动流程中创建合成通信错误。基于语言理论，我们提出并遵循了一个简单的错误分类。我们聚焦于现实世界对话中可能出现但在基准数据集中体现不足的三种错误沟通类型：误解、不理解和模糊相关的问题。我们的两步法先是利用最先进的大型语言模型（LLM）制造错误，然后生成修复话语。我们开展基于语言模型的评估，以保障生成话语的质量。我们将该方法应用于 MultiWOZ 数据集，并从定性、实证以及人工评判等方面对其进行评估。我们的结果显示，当下的 LLM 能够助力将事后错误沟通添加到基准数据集中，作为一种数据增强的形式。我们发布了生成的数据集，其中近 1900 个对话已被修改，命名为 CoPrUS-MultiWOZ，以推动对话系统的未来研究工作。

> Large-scale Wizard-Of-Oz dialogue datasets have enabled the training of deep learning-based dialogue systems. While they are successful as benchmark datasets, they lack certain types of utterances, which would make them more realistic. In this work, we investigate the creation of synthetic communication errors in an automatic pipeline. Based on linguistic theory, we propose and follow a simple error taxonomy. We focus on three types of miscommunications that could happen in real-world dialogues but are underrepresented in the benchmark dataset: misunderstandings, non-understandings and vaguely related questions. Our two-step approach uses a state-of-the-art Large Language Model (LLM) to first create the error and secondly the repairing utterance. We perform Language Model-based evaluation to ensure the quality of the generated utterances. We apply the method to the MultiWOZ dataset and evaluate it both qualitatively and empirically as well as with human judges. Our results indicate that current LLMs can aid in adding post-hoc miscommunications to benchmark datasets as a form of data augmentation. We publish the resulting dataset, in which nearly 1900 dialogues have been modified, as CoPrUS-MultiWOZ to facilitate future work on dialogue systems.

[Arxiv](https://arxiv.org/abs/2412.07515)