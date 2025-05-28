# # 决策流：提升大型语言模型成为基于原则的决策者

发布时间：2025年05月27日

`LLM应用`

> DecisionFlow: Advancing Large Language Model as Principled Decision Maker

# 摘要

> 在医疗和金融等高风险领域，有效的决策不仅需要准确的结果，还需要透明且可解释的推理过程。然而，当前的语言模型通常缺乏执行此类任务所需的结构化推理，而是以一种孤立、事后的方式生成决策和理由。为了解决这一问题，我们提出了DecisionFlow，这是一种开创性的决策建模框架，引导模型在结构化的动作、属性和约束表示上进行推理。与直接从提示中预测答案不同，DecisionFlow构建了一个语义上有依据的决策空间，并推断出一个潜在效用函数，以透明且基于效用的方式评估权衡。这一过程生成的决策与可解释的理由紧密相关，直观地反映了模型的推理过程。在两个高风险基准测试中的实证结果表明，DecisionFlow不仅在准确率上比强大的提示基线提升了高达30%，还增强了结果的一致性。我们的工作是将符号推理与LLMs相结合的重要一步，使LLMs支持的决策系统更具问责性、可解释性和可靠性。我们已在GitHub上发布了数据和代码：https://github.com/xiusic/DecisionFlow。

> In high-stakes domains such as healthcare and finance, effective decision-making demands not just accurate outcomes but transparent and explainable reasoning. However, current language models often lack the structured deliberation needed for such tasks, instead generating decisions and justifications in a disconnected, post-hoc manner. To address this, we propose DecisionFlow, a novel decision modeling framework that guides models to reason over structured representations of actions, attributes, and constraints. Rather than predicting answers directly from prompts, DecisionFlow builds a semantically grounded decision space and infers a latent utility function to evaluate trade-offs in a transparent, utility-driven manner. This process produces decisions tightly coupled with interpretable rationales reflecting the model's reasoning. Empirical results on two high-stakes benchmarks show that DecisionFlow not only achieves up to 30% accuracy gains over strong prompting baselines but also enhances alignment in outcomes. Our work is a critical step toward integrating symbolic reasoning with LLMs, enabling more accountable, explainable, and reliable LLM decision support systems. We release the data and code at https://github.com/xiusic/DecisionFlow.

[Arxiv](https://arxiv.org/abs/2505.21397)