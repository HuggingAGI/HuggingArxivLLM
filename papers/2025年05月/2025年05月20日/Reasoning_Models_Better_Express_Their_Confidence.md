# 推理模型更擅长表达置信度

发布时间：2025年05月20日

`LLM理论`

> Reasoning Models Better Express Their Confidence

# 摘要

> 尽管大型语言模型（LLMs）表现优异，但它们常常无法准确传达其自信程度，这使得评估其何时可能出错变得困难，并限制了其可靠性。在本研究中，我们发现推理模型——即进行延伸链式思维（CoT）推理的LLMs——不仅在问题解决方面表现出色，而且在准确表达自信方面也更胜一筹。我们对六种推理模型进行了基准测试，覆盖六个数据集，发现它们在36种设置中的33种情况下，相较于非推理模型，实现了严格更好的信心校准。我们的分析表明，这些校准改进源于推理模型的慢思考行为，如探索替代方法和回溯，这些行为使它们能够在整个链式思维过程中动态调整自信，使其逐步变得更加准确。特别值得注意的是，推理模型随着链式思维的展开，其信心校准效果逐渐提升，这一趋势在非推理模型中并未观察到。此外，移除链式思维中的慢思考行为会导致校准效果显著下降。最后，我们证明这些改进并非推理模型独有——当非推理模型通过上下文学习引导进行慢思考时，它们也能获益。

> Despite their strengths, large language models (LLMs) often fail to communicate their confidence accurately, making it difficult to assess when they might be wrong and limiting their reliability. In this work, we demonstrate that reasoning models-LLMs that engage in extended chain-of-thought (CoT) reasoning-exhibit superior performance not only in problem-solving but also in accurately expressing their confidence. Specifically, we benchmark six reasoning models across six datasets and find that they achieve strictly better confidence calibration than their non-reasoning counterparts in 33 out of the 36 settings. Our detailed analysis reveals that these gains in calibration stem from the slow thinking behaviors of reasoning models-such as exploring alternative approaches and backtracking-which enable them to adjust their confidence dynamically throughout their CoT, making it progressively more accurate. In particular, we find that reasoning models become increasingly better calibrated as their CoT unfolds, a trend not observed in non-reasoning models. Moreover, removing slow thinking behaviors from the CoT leads to a significant drop in calibration. Lastly, we show that these gains are not exclusive to reasoning models-non-reasoning models also benefit when guided to perform slow thinking via in-context learning.

[Arxiv](https://arxiv.org/abs/2505.14489)