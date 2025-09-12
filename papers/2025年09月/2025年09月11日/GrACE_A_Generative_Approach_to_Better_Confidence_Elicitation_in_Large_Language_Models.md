# GrACE：提升大型语言模型置信度获取的生成式方法

发布时间：2025年09月11日

`LLM应用` `医疗健康` `金融科技`

> GrACE: A Generative Approach to Better Confidence Elicitation in Large Language Models

# 摘要

> 在医疗、金融等高风险领域，通过置信度提取评估大型语言模型（LLMs）的可靠性是保障AI安全的关键手段。然而现有方法或计算成本高昂，或校准效果欠佳，导致其在实际应用中难以落地且可靠性不足。为此，我们提出了GrACE——一种生成式置信度提取方法，旨在为LLMs提供可扩展且可靠的置信度评估能力。GrACE的核心创新在于其独特机制：模型通过实时计算最后一个隐藏状态与词汇表中新增特殊标记嵌入的相似度来表达置信度。我们通过微调模型，以准确性为校准目标，实现对置信度的精准校准。在三个LLM和两个基准数据集上的实验显示，GrACE在开放式生成任务中展现出最佳的区分能力和校准效果，无需额外采样或辅助模型，性能便超越了六种现有方法。此外，我们还基于GrACE生成的置信度，提出了两种优化测试时扩展的策略。实验结果证实，GrACE不仅提升了最终决策的准确性，还大幅减少了测试时扩展所需的样本量，有望成为部署LLMs时实现可扩展、可靠且实时置信度估计的实用方案。

> Assessing the reliability of Large Language Models (LLMs) by confidence elicitation is a prominent approach to AI safety in high-stakes applications, such as healthcare and finance. Existing methods either require expensive computational overhead or suffer from poor calibration, making them impractical and unreliable for real-world deployment. In this work, we propose GrACE, a Generative Approach to Confidence Elicitation that enables scalable and reliable confidence elicitation for LLMs. GrACE adopts a novel mechanism in which the model expresses confidence by the similarity between the last hidden state and the embedding of a special token appended to the vocabulary, in real-time. We fine-tune the model for calibrating the confidence with calibration targets associated with accuracy. Experiments with three LLMs and two benchmark datasets show that the confidence produced by GrACE achieves the best discriminative capacity and calibration on open-ended generation tasks, outperforming six competing methods without resorting to additional sampling or an auxiliary model. Moreover, we propose two strategies for improving test-time scaling based on confidence induced by GrACE. Experimental results show that using GrACE not only improves the accuracy of the final decision but also significantly reduces the number of required samples in the test-time scaling scheme, indicating the potential of GrACE as a practical solution for deploying LLMs with scalable, reliable, and real-time confidence estimation.

[Arxiv](https://arxiv.org/abs/2509.09438)