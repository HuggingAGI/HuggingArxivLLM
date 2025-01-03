# Monty Hall 与优化保形预测：提升 LLMs 决策能力

发布时间：2024年12月31日

`LLM理论

理由：这篇论文主要讨论了如何通过保形预测（CP）和提出的CP-OPT框架来优化大型语言模型（LLMs）在决策场景中的不确定性量化问题。论文的核心在于理论框架的提出和优化方法的探讨，旨在提高LLM在高风险领域中的决策安全性和准确性。因此，这篇论文更偏向于LLM理论的研究，而不是具体的应用或Agent的实现。`

> Monty Hall and Optimized Conformal Prediction to Improve Decision-Making with LLMs

# 摘要

> # 摘要
大型语言模型（LLMs）在工具使用、API调用和多项选择题（MCQs）等决策场景中表现出色，但其过于自信的错误预测在医疗和金融等高风险领域可能带来隐患。为应对这一挑战，近期研究引入了保形预测（CP），一种模型无关的不确定性量化框架。CP将【数学公式】转化为高概率包含正确答案的预测集。尽管CP为任意分数提供了覆盖保证，但分数质量直接影响预测集的大小。以往研究依赖LLM的logits或启发式分数，缺乏质量保障。为此，我们提出了CP-OPT，一个优化框架，旨在学习既能最小化集大小又能保持覆盖的分数。此外，受蒙提霍尔问题启发，我们扩展了CP的应用，不仅用于不确定性量化，还通过【数学公式】修改问题，将选择范围缩小至预测集内。CP的覆盖保证确保正确答案大概率存在于修改后的问题提示中，而更少的选择提升了LLM回答正确的概率。在MMLU、ToolAlpaca和TruthfulQA数据集上，使用Gemma-2、Llama-3和Phi-3模型的实验表明，CP-OPT在保持覆盖的同时显著缩小了预测集，而CROQ则进一步提升了准确性，尤其是在与CP-OPT分数结合时。CP-OPT与CROQ共同构建了一个增强LLM决策安全性与准确性的强大框架。

> Large language models (LLMs) are empowering decision-making in several applications, including tool or API usage and answering multiple-choice questions (MCQs). However, they often make overconfident, incorrect predictions, which can be risky in high-stakes settings like healthcare and finance. To mitigate these risks, recent works have used conformal prediction (CP), a model-agnostic framework for distribution-free uncertainty quantification. CP transforms a \emph{score function} into prediction sets that contain the true answer with high probability. While CP provides this coverage guarantee for arbitrary scores, the score quality significantly impacts prediction set sizes. Prior works have relied on LLM logits or other heuristic scores, lacking quality guarantees. We address this limitation by introducing CP-OPT, an optimization framework to learn scores that minimize set sizes while maintaining coverage. Furthermore, inspired by the Monty Hall problem, we extend CP's utility beyond uncertainty quantification to improve accuracy. We propose \emph{conformal revision of questions} (CROQ) to revise the problem by narrowing down the available choices to those in the prediction set. The coverage guarantee of CP ensures that the correct choice is in the revised question prompt with high probability, while the smaller number of choices increases the LLM's chances of answering it correctly. Experiments on MMLU, ToolAlpaca, and TruthfulQA datasets with Gemma-2, Llama-3 and Phi-3 models show that CP-OPT significantly reduces set sizes while maintaining coverage, and CROQ improves accuracy over the standard inference, especially when paired with CP-OPT scores. Together, CP-OPT and CROQ offer a robust framework for improving both the safety and accuracy of LLM-driven decision-making.

[Arxiv](https://arxiv.org/abs/2501.00555)