# 多语言大语言模型评估中的测试集质量探讨

发布时间：2025年08月04日

`其他` `数据集质量评估`

> Test Set Quality in Multilingual LLM Evaluation

# 摘要

> 近年来，为了衡量大型语言模型（LLMs）在多语言能力方面的进展，人们以半自动的方式开发了多个多语言基准数据集。然而，尽管先前的工作已经识别出即使是完全由人工标注的测试集中的错误，但人们对数据集本身的质量关注仍然不够。在本文中，我们手动分析了近期在法语和泰卢固语两种语言中的多语言评估数据集，发现其中存在若干错误。我们将原始版本和修订版本的数据集在多个LLMs上的性能差异进行了比较，发现两种语言中的性能差异显著（某些情况下甚至接近10%）。基于这些结果，我们主张测试集不应被视为不可改变，应该重新审视、检查其正确性，并考虑进行版本控制。最后，我们为数据集的创建者和使用者提出了一些建议，以应对数据集质量问题。

> Several multilingual benchmark datasets have been developed in a semi-automatic manner in the recent past to measure progress and understand the state-of-the-art in the multilingual capabilities of Large Language Models. However, there is not a lot of attention paid to the quality of the datasets themselves, despite the existence of previous work in identifying errors in even fully human-annotated test sets. In this paper, we manually analyze recent multilingual evaluation sets in two languages - French and Telugu, identifying several errors in the process. We compare the performance difference across several LLMs with the original and revised versions of the datasets and identify large differences (almost 10% in some cases) in both languages). Based on these results, we argue that test sets should not be considered immutable and should be revisited, checked for correctness, and potentially versioned. We end with some recommendations for both the dataset creators as well as consumers on addressing the dataset quality issues.

[Arxiv](https://arxiv.org/abs/2508.02635)