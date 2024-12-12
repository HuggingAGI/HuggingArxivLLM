# 用于自动分子专利侵权评估的智能系统

发布时间：2024年12月10日

`Agent` `药物研发`

> Intelligent System for Automated Molecular Patent Infringement Assessment

# 摘要

> 自动化药物发现以机器驱动流程替代劳动密集型人工流程，为加快新型疗法的研发带来巨大潜力。但当前自动化框架存在关键瓶颈，无法判定新设计分子是否侵犯现有专利，带来重大法律和财务风险。我们推出了 PatentFinder，这一新颖的工具增强型多智能体框架，能精准全面评估小分子的专利侵权状况。它融合了针对分解子任务定制的启发式和基于模型的工具，比如：能对分子和 Markush 结构进行光学化学结构识别的 MarkushParser，以及能增强大型语言模型从分子中精确提取取代基能力的 MarkushMatcher。在基准数据集 MolPatent-240 中，PatentFinder 优于仅依赖大型语言模型的基线方法，F1 分数提升 13.8%，准确率提高 12%。实验结果显示，PatentFinder 减轻标签偏差，实现平衡预测，并自动生成详细且可解释的专利侵权报告。此项工作不仅解决了自动化药物发现中的关键难题，还展现了将复杂科学任务分解为可管理子任务，交由专门的、工具增强型智能体处理的可能性。

> Automated drug discovery offers significant potential for accelerating the development of novel therapeutics by substituting labor-intensive human workflows with machine-driven processes. However, a critical bottleneck persists in the inability of current automated frameworks to assess whether newly designed molecules infringe upon existing patents, posing significant legal and financial risks. We introduce PatentFinder, a novel tool-enhanced and multi-agent framework that accurately and comprehensively evaluates small molecules for patent infringement. It incorporates both heuristic and model-based tools tailored for decomposed subtasks, featuring: MarkushParser, which is capable of optical chemical structure recognition of molecular and Markush structures, and MarkushMatcher, which enhances large language models' ability to extract substituent groups from molecules accurately. On our benchmark dataset MolPatent-240, PatentFinder outperforms baseline approaches that rely solely on large language models, demonstrating a 13.8\% increase in F1-score and a 12\% rise in accuracy. Experimental results demonstrate that PatentFinder mitigates label bias to produce balanced predictions and autonomously generates detailed, interpretable patent infringement reports. This work not only addresses a pivotal challenge in automated drug discovery but also demonstrates the potential of decomposing complex scientific tasks into manageable subtasks for specialized, tool-augmented agents.

[Arxiv](https://arxiv.org/abs/2412.07819)