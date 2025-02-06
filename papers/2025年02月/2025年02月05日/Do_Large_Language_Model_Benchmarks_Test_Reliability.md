# 大型语言模型的基准测试真的能检验其可靠性吗？

发布时间：2025年02月05日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的可靠性评估问题，提出了“白金基准”概念，并通过对现有基准的修订和模型评估，揭示了前沿LLMs在简单任务上的错误模式。这些研究内容属于对LLMs的理论分析和评估方法的改进，因此归类为LLM理论。` `人工智能` `模型评估`

> Do Large Language Model Benchmarks Test Reliability?

# 摘要

> 部署大型语言模型（LLMs）时，确保其不仅强大而且可靠至关重要。虽然已有众多基准测试追踪LLMs的能力提升，但对其可靠性的评估却鲜有涉及。为探究这一盲区的潜在影响，我们深入分析了现有基准测试如何衡量模型可靠性。研究发现，标签错误普遍存在，可能削弱评估效果，掩盖模型故障，隐藏不可靠行为。
    针对这一评估盲区，我们提出了“白金基准”概念，即精心设计以最小化标签错误和歧义的基准测试。作为初步尝试，我们修订了十五个现有流行基准的示例。在这些白金基准上，我们对多种模型进行了评估，发现前沿LLMs在诸如小学数学应用题等简单任务上仍会出错。进一步分析这些错误，揭示了前沿模型持续存在的未识别问题模式。相关代码已开源，详见https://github.com/MadryLab/platinum-benchmarks。

> When deploying large language models (LLMs), it is important to ensure that these models are not only capable, but also reliable. Many benchmarks have been created to track LLMs' growing capabilities, however there has been no similar focus on measuring their reliability. To understand the potential ramifications of this gap, we investigate how well current benchmarks quantify model reliability. We find that pervasive label errors can compromise these evaluations, obscuring lingering model failures and hiding unreliable behavior.
  Motivated by this gap in the evaluation of reliability, we then propose the concept of so-called platinum benchmarks, i.e., benchmarks carefully curated to minimize label errors and ambiguity. As a first attempt at constructing such benchmarks, we revise examples from fifteen existing popular benchmarks. We evaluate a wide range of models on these platinum benchmarks and find that, indeed, frontier LLMs still exhibit failures on simple tasks such as elementary-level math word problems. Analyzing these failures further reveals previously unidentified patterns of problems on which frontier models consistently struggle. We provide code at https://github.com/MadryLab/platinum-benchmarks

[Arxiv](https://arxiv.org/abs/2502.03461)