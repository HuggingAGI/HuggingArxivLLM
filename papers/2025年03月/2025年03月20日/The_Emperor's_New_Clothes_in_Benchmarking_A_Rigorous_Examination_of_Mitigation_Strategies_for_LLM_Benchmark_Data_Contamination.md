# 《皇帝的新装》在基准测试中？对大型语言模型基准数据污染的严格审查及其缓解策略的严谨探讨

发布时间：2025年03月20日

`LLM理论` `人工智能` `模型评估`

> The Emperor's New Clothes in Benchmarking? A Rigorous Examination of Mitigation Strategies for LLM Benchmark Data Contamination

# 摘要

> 基准数据污染（BDC）——即在训练集中包含基准测试样本——在大型语言模型（LLM）评估中引发了日益增长的担忧。它不仅夸大了模型性能，还削弱了评估的可靠性。为了解决这一问题，研究人员提出了各种缓解策略来更新现有基准，包括修改原始问题或基于它们生成新的问题。然而，对这些缓解策略有效性的严格评估仍然不足。本文设计了一个系统化且受控的管道，同时引入了两个新颖的指标——保真度和抗污染能力——以对现有BDC缓解策略进行细致全面的评估。先前的评估方法，如准确率下降和准确率匹配，仅关注总体准确率，常常导致不完整或误导性的结论。我们的指标通过强调问题级别的评估结果匹配，解决了这一局限性。通过使用10个LLM、5个基准、20个BDC缓解策略以及2种污染场景进行的广泛实验表明，现有的策略在所有基准上并未显著提高抗污染能力（即不更新基准的情况），也没有有效平衡保真度和抗污染能力。这些发现凸显了设计更有效的BDC缓解策略的迫切需求。我们的代码仓库可在https://github.com/ASTRAL-Group/BDC_mitigation_assessment获取。

> Benchmark Data Contamination (BDC)-the inclusion of benchmark testing samples in the training set-has raised increasing concerns in Large Language Model (LLM) evaluation, leading to falsely inflated performance estimates and undermining evaluation reliability. To address this, researchers have proposed various mitigation strategies to update existing benchmarks, including modifying original questions or generating new ones based on them. However, a rigorous examination of the effectiveness of these mitigation strategies remains lacking. In this paper, we design a systematic and controlled pipeline along with two novel metrics-fidelity and contamination resistance-to provide a fine-grained and comprehensive assessment of existing BDC mitigation strategies. Previous assessment methods, such as accuracy drop and accuracy matching, focus solely on aggregate accuracy, often leading to incomplete or misleading conclusions. Our metrics address this limitation by emphasizing question-level evaluation result matching. Extensive experiments with 10 LLMs, 5 benchmarks, 20 BDC mitigation strategies, and 2 contamination scenarios reveal that no existing strategy significantly improves resistance over the vanilla case (i.e., no benchmark update) across all benchmarks, and none effectively balances fidelity and contamination resistance. These findings underscore the urgent need for designing more effective BDC mitigation strategies. Our code repository is available at https://github.com/ASTRAL-Group/BDC_mitigation_assessment.

[Arxiv](https://arxiv.org/abs/2503.16402)