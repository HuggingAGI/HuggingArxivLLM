# 面对事实！在实际场景中评估基于 RAG 的事实核查流程

发布时间：2024年12月19日

`RAG` `事实核查`

> Face the Facts! Evaluating RAG-based Fact-checking Pipelines in Realistic Settings

# 摘要

> 自然语言处理和生成系统近来展现出能够辅助并简化专业事实核查人员那耗费大量成本和时间的工作的潜力。在本研究中，我们解除了当前基于检索增强生成（RAG）范式的自动化事实核查最先进流程的若干限制。我们旨在更现实的场景下，对基于 RAG 的判决生成方法进行基准测试，也就是生成讨论声明真实性的短文，并在文体复杂的声明和异构但可靠的知识库上对其进行评估。我们的发现呈现出复杂的态势，比如基于 LLM 的检索器胜过其他检索技术，然而面对异构知识库仍有困难；较大的模型在判决的忠实度上表现卓越，较小的模型在上下文依从性方面更优，人类评估倾向于零次和一次的方法以获取更多信息，而微调模型在情感一致性方面表现出色。

> Natural Language Processing and Generation systems have recently shown the potential to complement and streamline the costly and time-consuming job of professional fact-checkers. In this work, we lift several constraints of current state-of-the-art pipelines for automated fact-checking based on the Retrieval-Augmented Generation (RAG) paradigm. Our goal is to benchmark, under more realistic scenarios, RAG-based methods for the generation of verdicts - i.e., short texts discussing the veracity of a claim - evaluating them on stylistically complex claims and heterogeneous, yet reliable, knowledge bases. Our findings show a complex landscape, where, for example, LLM-based retrievers outperform other retrieval techniques, though they still struggle with heterogeneous knowledge bases; larger models excel in verdict faithfulness, while smaller models provide better context adherence, with human evaluations favouring zero-shot and one-shot approaches for informativeness, and fine-tuned models for emotional alignment.

[Arxiv](https://arxiv.org/abs/2412.15189)