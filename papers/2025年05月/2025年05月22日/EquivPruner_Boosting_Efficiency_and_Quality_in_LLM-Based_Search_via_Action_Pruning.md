# EquivPruner：通过动作剪枝提升基于大型语言模型的搜索效率与质量

发布时间：2025年05月22日

`LLM应用` `数学推理`

> EquivPruner: Boosting Efficiency and Quality in LLM-Based Search via Action Pruning

# 摘要

> 大型语言模型（LLMs）在复杂推理任务中表现出色，但现有策略常常因冗余探索语义等价步骤而消耗大量token。现有的语义相似性方法在数学推理等特定领域背景下难以准确识别这种等价性。为解决这一问题，我们提出了一种简单而有效的EquivPruner方法，该方法能够在LLM推理搜索过程中识别并剪枝语义等价的动作。同时，我们还介绍了MathEquiv，这是我们创建的第一个用于数学陈述等价性的数据集，它支持训练一个轻量级的等价检测器。在不同模型和任务上的广泛实验表明，EquivPruner显著减少了token消耗，提高了搜索效率，同时通常增强了推理准确性。例如，当应用于Qwen2.5-Math-7B-Instruct在GSM8K上的推理时，EquivPruner将token消耗减少了48.1%，同时提高了准确率。我们的代码可在https://github.com/Lolo1222/EquivPruner获取。

> Large Language Models (LLMs) excel at complex reasoning through search algorithms, yet current strategies often suffer from massive token consumption due to redundant exploration of semantically equivalent steps. Existing semantic similarity methods struggle to accurately identify such equivalence in domain-specific contexts like mathematical reasoning. To address this, we propose EquivPruner, a simple yet effective approach that identifies and prunes semantically equivalent actions during LLM reasoning search. We also introduce MathEquiv, the first dataset we created for mathematical statement equivalence, which enables the training of a lightweight equivalence detector. Extensive experiments across various models and tasks demonstrate that EquivPruner significantly reduces token consumption, improving searching efficiency and often bolstering reasoning accuracy. For instance, when applied to Qwen2.5-Math-7B-Instruct on GSM8K, EquivPruner reduced token consumption by 48.1\% while also improving accuracy. Our code is available at https://github.com/Lolo1222/EquivPruner.

[Arxiv](https://arxiv.org/abs/2505.16312)