# 文本 vs. 图像：输入表示与模型在表格问答任务中的有效性细致分析

发布时间：2025年05月20日

`LLM应用

摘要中探讨了大语言模型在表格问答任务中的应用，比较了不同输入方式的效果，并提出了一种动态选择方法以提升性能。这属于模型应用的研究，因此归类为LLM应用。` `问答系统`

> Texts or Images? A Fine-grained Analysis on the Effectiveness of Input Representations and Models for Table Question Answering

# 摘要

> 在表格问答任务 (TQA) 中，表格可被编码为文本或图像。先前研究表明，将表格图像传递给多模态大语言模型 (MLLMs) 的效果与使用文本输入的传统大语言模型 (LLMs) 相当甚至更优。然而，由于缺乏受控实验环境，这些方法之间的细微差别尚不明确。本文首次从问题复杂度和表格规模两个角度，对多种表格表示方法与模型的组合效果进行了受控研究。我们基于现有 TQA 数据集构建了新的基准测试。通过对七组 MLLMs 和 LLMs 的系统分析，我们发现最佳的表格表示与模型组合会因实验环境的不同而变化。我们提出了一种动态选择表格表示的方法 FRES，并观察到与不加区分地使用两种表示方法相比，平均性能提升了 10%。


> In table question answering (TQA), tables are encoded as either texts or images. Prior work suggests that passing images of tables to multi-modal large language models (MLLMs) performs comparably to or even better than using textual input with large language models (LLMs). However, the lack of controlled setups limits fine-grained distinctions between these approaches. In this paper, we conduct the first controlled study on the effectiveness of several combinations of table representations and models from two perspectives: question complexity and table size. We build a new benchmark based on existing TQA datasets. In a systematic analysis of seven pairs of MLLMs and LLMs, we find that the best combination of table representation and model varies across setups. We propose FRES, a method selecting table representations dynamically, and observe a 10% average performance improvement compared to using both representations indiscriminately.

[Arxiv](https://arxiv.org/abs/2505.14131)