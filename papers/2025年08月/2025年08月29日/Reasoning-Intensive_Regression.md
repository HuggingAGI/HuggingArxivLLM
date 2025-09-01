# 推理密集型回归

发布时间：2025年08月29日

`LLM应用` `基础理论`

> Reasoning-Intensive Regression

# 摘要

> AI研究人员与从业者正将大型语言模型（LLMs）越来越多地应用于我们称为推理密集型回归（RiR）的任务——即从文本中推断细微的数值属性。与情感分析、相似度计算等标准语言回归任务不同，RiR常出现在特定场景问题中，例如基于评分标准的评分或特定领域检索。这类任务不仅需要深度文本分析，且特定任务的训练数据与计算资源往往有限。我们将三个实际问题构建为RiR任务以建立初步基准，并借此验证假设：提示冻结LLMs与通过梯度下降微调Transformer编码器，在RiR任务中均表现欠佳。为此，我们提出MENTAT——一种结合批量反思式提示优化与神经集成学习的轻量简便方法。该方法相比两种基线方法性能提升高达65%，不过RiR领域未来仍有巨大的提升空间。

> AI researchers and practitioners increasingly apply large language models (LLMs) to what we call reasoning-intensive regression (RiR), i.e. deducing subtle numerical properties from text. Unlike standard language regression tasks, e.g. for sentiment or similarity, RiR often appears instead in ad-hoc problems like rubric-based scoring or domain-specific retrieval, where much deeper analysis of text is required while only limited task-specific training data and computation are available. We cast three realistic problems as RiR tasks to establish an initial benchmark, and use that to test our hypothesis that prompting frozen LLMs and finetuning Transformer encoders via gradient descent will both often struggle in RiR. We then propose MENTAT, a simple and lightweight method that combines batch-reflective prompt optimization with neural ensemble learning. MENTAT achieves up to 65% improvement over both baselines, though substantial room remains for future advances in RiR.

[Arxiv](https://arxiv.org/abs/2508.21762)