# 遗忘并非删除：探究大语言模型中机器遗忘的可逆性

发布时间：2025年05月22日

`LLM理论

摘要讨论了大型语言模型中的遗忘机制，提出了一种新的评估框架，并提供了理论解释，属于对模型内部机制的理论研究。` `大型语言模型` `机器学习`

> Unlearning Isn't Deletion: Investigating Reversibility of Machine Unlearning in LLMs

# 摘要

> # 遗忘机制在大型语言模型中的挑战与突破

在大型语言模型（LLMs）中，遗忘机制旨在移除特定数据的影响，但目前的评估方法主要依赖于token级别的指标，如准确率和困惑度。然而，这些指标可能具有误导性：模型看似遗忘，但通过极小的微调即可迅速恢复其原始行为，这表明遗忘机制可能只是隐藏了信息，而非真正删除了它。

为了深入理解这一现象，我们引入了一个基于表示层面的评估框架，采用PCA相似性和位移、中心核对齐以及费舍尔信息等方法。通过将这一工具包应用于六种遗忘方法、三个领域（文本、代码、数学）以及两个开源的LLMs，我们发现了一个关键区别：可逆遗忘与不可逆遗忘。

在可逆情况下，模型在token级别上表现崩溃，但潜在特征得以保留；而在不可逆情况下，则会发生更深层次的表示损伤。我们进一步提供了一个理论解释，将输出层附近的浅层权重扰动与误导性遗忘信号联系起来，并展示了可逆性受任务类型和超参数的调节。

我们的研究揭示了当前评估实践中的根本性差距，并为LLMs中值得信赖的遗忘机制奠定了新的诊断基础。我们提供了一个统一的工具包，用于分析LLM在遗忘和重新学习过程中的表示变化：[查看工具包](https://github.com/XiaoyuXU1/Representational_Analysis_Tools.git)。


> Unlearning in large language models (LLMs) is intended to remove the influence of specific data, yet current evaluations rely heavily on token-level metrics such as accuracy and perplexity. We show that these metrics can be misleading: models often appear to forget, but their original behavior can be rapidly restored with minimal fine-tuning, revealing that unlearning may obscure information rather than erase it. To diagnose this phenomenon, we introduce a representation-level evaluation framework using PCA-based similarity and shift, centered kernel alignment, and Fisher information. Applying this toolkit across six unlearning methods, three domains (text, code, math), and two open-source LLMs, we uncover a critical distinction between reversible and irreversible forgetting. In reversible cases, models suffer token-level collapse yet retain latent features; in irreversible cases, deeper representational damage occurs. We further provide a theoretical account linking shallow weight perturbations near output layers to misleading unlearning signals, and show that reversibility is modulated by task type and hyperparameters. Our findings reveal a fundamental gap in current evaluation practices and establish a new diagnostic foundation for trustworthy unlearning in LLMs. We provide a unified toolkit for analyzing LLM representation changes under unlearning and relearning: https://github.com/XiaoyuXU1/Representational_Analysis_Tools.git.

[Arxiv](https://arxiv.org/abs/2505.16831)