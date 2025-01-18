# 利用大型语言模型为交互式机器学习笔记本提供代码编辑建议

发布时间：2025年01月16日

`LLM应用

理由：这篇论文主要探讨了使用大型语言模型（LLMs）来预测 Jupyter 笔记本中的代码编辑，并提出了一个相关的数据集。研究重点在于如何利用 LLMs 来改进机器学习代码的维护和编辑，这属于 LLM 在实际应用中的使用场景。因此，将其分类为“LLM应用”是合适的。` `机器学习` `软件开发`

> Suggesting Code Edits in Interactive Machine Learning Notebooks Using Large Language Models

# 摘要

> 机器学习开发者常用 Jupyter 等交互式计算笔记本来托管数据处理和模型训练的代码。尽管 Jupyter 笔记本为编写机器学习管道和交互式观察输出提供了便利，但其维护（如添加新功能或修复错误）却因笔记本的复杂性和长度而颇具挑战。此外，目前尚无与开发者对 Jupyter 笔记本编辑相关的基准。为此，我们首次提出了一个包含 48,398 个 Jupyter 笔记本编辑的数据集，这些编辑来自 GitHub 上 792 个机器学习仓库的 20,095 次修订，并首次研究了使用 LLMs 预测 Jupyter 笔记本中的代码编辑。我们的数据集详细记录了单元格和行级别的修改，为理解机器学习工作流中的实际维护模式奠定了基础。我们发现，Jupyter 笔记本的编辑高度局部化，仓库中的平均更改仅为 166 行代码。尽管较大的模型在代码编辑上优于较小的模型，但所有模型在我们的数据集上的准确性都很低，即使经过微调也是如此，这揭示了实际机器学习维护任务的复杂性。我们的研究结果强调了上下文信息在提升模型性能中的关键作用，并为提升大型语言模型在工程机器学习代码方面的能力指明了方向。

> Machine learning developers frequently use interactive computational notebooks, such as Jupyter notebooks, to host code for data processing and model training. Jupyter notebooks provide a convenient tool for writing machine learning pipelines and interactively observing outputs, however, maintaining Jupyter notebooks, e.g., to add new features or fix bugs, can be challenging due to the length and complexity of the notebooks. Moreover, there is no existing benchmark related to developer edits on Jupyter notebooks. To address this, we present the first dataset of 48,398 Jupyter notebook edits derived from 20,095 revisions of 792 machine learning repositories on GitHub, and perform the first study of the using LLMs to predict code edits in Jupyter notebooks. Our dataset captures granular details of cell-level and line-level modifications, offering a foundation for understanding real-world maintenance patterns in machine learning workflows. We observed that the edits on Jupyter notebooks are highly localized, with changes averaging only 166 lines of code in repositories. While larger models outperform smaller counterparts in code editing, all models have low accuracy on our dataset even after finetuning, demonstrating the complexity of real-world machine learning maintenance tasks. Our findings emphasize the critical role of contextual information in improving model performance and point toward promising avenues for advancing large language models' capabilities in engineering machine learning code.

[Arxiv](https://arxiv.org/abs/2501.09745)