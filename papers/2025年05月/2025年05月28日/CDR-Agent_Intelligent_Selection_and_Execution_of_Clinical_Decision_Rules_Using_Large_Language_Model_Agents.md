# CDR代理：基于大型语言模型代理的临床决策规则智能选择与执行系统

发布时间：2025年05月28日

`Agent` `临床决策支持`

> CDR-Agent: Intelligent Selection and Execution of Clinical Decision Rules Using Large Language Model Agents

# 摘要

> 临床决策复杂且快速，尤其在急诊科（ED），这里需要迅速做出关键且高风险的决策。临床决策规则（CDR）是基于证据的标准工具，通过整合症状、体征和临床变量形成决策树，以实现一致且准确的诊断。然而，CDR的使用常受限于临床医生的认知负荷，影响其快速回忆和应用合适规则的能力。我们推出CDR-Agent，一个基于大型语言模型（LLM）的创新系统，旨在通过自主识别和应用最合适的CDR来提升ED的决策能力，这些CDR基于非结构化的临床记录。为了验证CDR-Agent的效果，我们整理了两个新型ED数据集：合成数据集和CDR-Bench，尽管CDR-Agent也可应用于非ED诊所。与独立的LLM基线相比，CDR-Agent在CDR选择上实现了56.3%（合成数据集）和8.7%（CDR-Bench）的准确率提升。此外，CDR-Agent显著降低了计算开销。通过这些数据集，我们证明CDR-Agent不仅能够高效选择相关CDR，还能谨慎而有效地做出影像决策，通过减少不必要的干预并成功识别大多数阳性诊断案例，超越了传统的LLM提示方法。我们的工作代码可在以下链接找到：https://github.com/zhenxianglance/medagent-cdr-agent

> Clinical decision-making is inherently complex and fast-paced, particularly in emergency departments (EDs) where critical, rapid and high-stakes decisions are made. Clinical Decision Rules (CDRs) are standardized evidence-based tools that combine signs, symptoms, and clinical variables into decision trees to make consistent and accurate diagnoses. CDR usage is often hindered by the clinician's cognitive load, limiting their ability to quickly recall and apply the appropriate rules. We introduce CDR-Agent, a novel LLM-based system designed to enhance ED decision-making by autonomously identifying and applying the most appropriate CDRs based on unstructured clinical notes. To validate CDR-Agent, we curated two novel ED datasets: synthetic and CDR-Bench, although CDR-Agent is applicable to non ED clinics. CDR-Agent achieves a 56.3\% (synthetic) and 8.7\% (CDR-Bench) accuracy gain relative to the standalone LLM baseline in CDR selection. Moreover, CDR-Agent significantly reduces computational overhead. Using these datasets, we demonstrated that CDR-Agent not only selects relevant CDRs efficiently, but makes cautious yet effective imaging decisions by minimizing unnecessary interventions while successfully identifying most positively diagnosed cases, outperforming traditional LLM prompting approaches. Code for our work can be found at: https://github.com/zhenxianglance/medagent-cdr-agent

[Arxiv](https://arxiv.org/abs/2505.23055)