# 顺序效应：探究闭源LLM对提示的敏感性

发布时间：2025年02月06日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在输入顺序变化下的表现，特别是顺序敏感性对模型输出的影响。研究通过实验分析了输入顺序对任务性能的影响，并提出了现有方法的局限性。这些内容属于对LLM内部机制和行为的理论研究，旨在理解和改进模型的表现，因此归类为“LLM理论”。` `人工智能`

> The Order Effect: Investigating Prompt Sensitivity in Closed-Source LLMs

# 摘要

> 随着大型语言模型（LLMs）在各类应用中的广泛应用，确保其在多变输入条件下的可靠性至关重要。顺序敏感性是影响这一可靠性的关键问题，即输入顺序的微小变化可能导致输出不一致或带有偏见。尽管近期研究已在一定程度上降低了这种敏感性，但问题仍未彻底解决。本文通过在多任务（如释义、相关性判断和多项选择题）中展开实验，深入探讨了闭源LLMs的顺序敏感性。实验结果显示，输入顺序对任务性能有显著影响，打乱的输入会导致输出准确性明显下降。少样本提示虽有一定效果，但仅能部分缓解问题，无法彻底解决。这些发现揭示了高风险应用中持续存在的风险，并强调了未来开发中需要更强大的LLMs或更先进的输入处理技术。

> As large language models (LLMs) become integral to diverse applications, ensuring their reliability under varying input conditions is crucial. One key issue affecting this reliability is order sensitivity, wherein slight variations in input arrangement can lead to inconsistent or biased outputs. Although recent advances have reduced this sensitivity, the problem remains unresolved. This paper investigates the extent of order sensitivity in closed-source LLMs by conducting experiments across multiple tasks, including paraphrasing, relevance judgment, and multiple-choice questions. Our results show that input order significantly affects performance across tasks, with shuffled inputs leading to measurable declines in output accuracy. Few-shot prompting demonstrates mixed effectiveness and offers partial mitigation, however, fails to fully resolve the problem. These findings highlight persistent risks, particularly in high-stakes applications, and point to the need for more robust LLMs or improved input-handling techniques in future development.

[Arxiv](https://arxiv.org/abs/2502.04134)