# 基于协作式多智能体LLM架构的SOAP记录临床问题自动化检测

发布时间：2025年08月29日

`Agent` `医疗健康`

> Automated Clinical Problem Detection from SOAP Notes using a Collaborative Multi-Agent LLM Architecture

# 摘要

> 准确解读临床病历对患者护理至关重要，然而这些记录的复杂性给自动化处理带来了挑战。尽管大型语言模型（LLMs）前景广阔，但单一模型方法往往难以满足高风险临床任务对稳健性的要求。为此，我们提出了一种协作式多智能体系统（MAS），通过模拟临床会诊团队来弥补这一不足。该系统的任务是仅分析SOAP病历中的主观（S）和客观（O）部分以识别临床问题，模拟将原始数据整合为评估结果的诊断推理过程。系统中，管理器智能体负责协调动态分配的专家智能体团队，这些专家智能体通过分层迭代的辩论最终达成共识。我们在包含420份MIMIC-III病历的精选数据集上，将该MAS与单一智能体基线模型进行了对比评估。结果显示，动态多智能体配置在识别充血性心力衰竭、急性肾损伤和败血症方面的性能持续提升。对智能体辩论的定性分析发现，这种结构能有效呈现并权衡冲突证据，不过偶尔也会受到群体思维的干扰。通过模拟临床团队的推理过程，我们的系统为开发更准确、稳健且可解释的临床决策支持工具开辟了一条有前景的道路。

> Accurate interpretation of clinical narratives is critical for patient care, but the complexity of these notes makes automation challenging. While Large Language Models (LLMs) show promise, single-model approaches can lack the robustness required for high-stakes clinical tasks. We introduce a collaborative multi-agent system (MAS) that models a clinical consultation team to address this gap. The system is tasked with identifying clinical problems by analyzing only the Subjective (S) and Objective (O) sections of SOAP notes, simulating the diagnostic reasoning process of synthesizing raw data into an assessment. A Manager agent orchestrates a dynamically assigned team of specialist agents who engage in a hierarchical, iterative debate to reach a consensus. We evaluated our MAS against a single-agent baseline on a curated dataset of 420 MIMIC-III notes. The dynamic multi-agent configuration demonstrated consistently improved performance in identifying congestive heart failure, acute kidney injury, and sepsis. Qualitative analysis of the agent debates reveals that this structure effectively surfaces and weighs conflicting evidence, though it can occasionally be susceptible to groupthink. By modeling a clinical team's reasoning process, our system offers a promising path toward more accurate, robust, and interpretable clinical decision support tools.

[Arxiv](https://arxiv.org/abs/2508.21803)