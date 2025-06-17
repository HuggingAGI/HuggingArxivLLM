# 为最小编辑语法错误修正适配大型语言模型

发布时间：2025年06月16日

`LLM应用`

> Adapting LLMs for Minimal-edit Grammatical Error Correction

# 摘要

> 解码器-only大型语言模型在流利度编辑的英文语法错误修正任务中表现优异，但在最小编辑英文语法错误修正任务中的应用仍有待深入研究。为了提升其在最小编辑方法中的效果，我们深入探讨了错误率适应性问题，并提出了一种全新的训练计划方法。实验结果表明，我们的方法在BEA测试集上取得了新的单模型系统最优结果。此外，我们对最常见的英文语法错误修正数据集进行了脱词处理，使其更贴近自然的文本书写方式。在此过程中，我们发现了一些错误。通过实验，我们分析了在脱词数据集上进行训练是否会影响结果，并衡量了使用包含更正错误示例的数据集的影响。为了方便研究者们复现实验，我们已开源了训练模型的源代码。

> Decoder-only large language models have shown superior performance in the fluency-edit English Grammatical Error Correction, but their adaptation for minimal-edit English GEC is still underexplored. To improve their effectiveness in the minimal-edit approach, we explore the error rate adaptation topic and propose a novel training schedule method. Our experiments set a new state-of-the-art result for a single-model system on the BEA-test set. We also detokenize the most common English GEC datasets to match the natural way of writing text. During the process, we find that there are errors in them. Our experiments analyze whether training on detokenized datasets impacts the results and measure the impact of the usage of the datasets with corrected erroneous examples. To facilitate reproducibility, we have released the source code used to train our models.

[Arxiv](https://arxiv.org/abs/2506.13148)