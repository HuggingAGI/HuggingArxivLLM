# # REPRO-Bench：自主AI能否评估社会科学的可重复性？

发布时间：2025年07月24日

`Agent` `社会科学` `AI代理`

> REPRO-Bench: Can Agentic AI Systems Assess the Reproducibility of Social Science Research?

# 摘要

> # 摘要  
评估社会科学论文的可重复性对于推动研究过程的严谨性至关重要，但手动评估成本高昂。随着智能体AI系统的最新进展，我们希望评估它们自动执行此过程的能力。然而，现有的用于复制研究论文的基准（1）仅关注使用提供的代码和数据来复制结果，而不评估其与论文的一致性，（2）过度简化了现实场景，（3）缺乏必要的数据格式和编程语言的多样性。为了解决这些问题，我们引入了REPRO-Bench，这是一个包含112个任务实例的集合，每个实例代表一篇具有公开可用复制报告的社会科学论文。代理的任务是根据原始论文PDF和相应的复制包来评估论文的可重复性。REPRO-Bench提供了对社会科学论文可重复性的端到端评估任务，其复杂度与现实世界评估相当。我们在REPRO-Bench上评估了三个代表性的AI代理，其中表现最佳的代理仅达到了21.4%的准确率。基于我们的实证分析，我们开发了REPRO-Agent，将现有代理实现的最高准确率提高了71%。我们得出结论，需要开发更先进的AI代理来自动化现实世界中的可重复性评估。REPRO-Bench可在https://github.com/uiuc-kang-lab/REPRO-Bench公开获取。

> Assessing the reproducibility of social science papers is essential for promoting rigor in research processes, but manual assessment is costly. With recent advances in agentic AI systems (i.e., AI agents), we seek to evaluate their capability to automate this process. However, existing benchmarks for reproducing research papers (1) focus solely on reproducing results using provided code and data without assessing their consistency with the paper, (2) oversimplify real-world scenarios, and (3) lack necessary diversity in data formats and programming languages. To address these issues, we introduce REPRO-Bench, a collection of 112 task instances, each representing a social science paper with a publicly available reproduction report. The agents are tasked with assessing the reproducibility of the paper based on the original paper PDF and the corresponding reproduction package. REPRO-Bench features end-to-end evaluation tasks on the reproducibility of social science papers with complexity comparable to real-world assessments. We evaluate three representative AI agents on REPRO-Bench, with the best-performing agent achieving an accuracy of only 21.4%. Building on our empirical analysis, we develop REPRO-Agent, which improves the highest accuracy achieved by existing agents by 71%. We conclude that more advanced AI agents should be developed to automate real-world reproducibility assessment. REPRO-Bench is publicly available at https://github.com/uiuc-kang-lab/REPRO-Bench.

[Arxiv](https://arxiv.org/abs/2507.18901)