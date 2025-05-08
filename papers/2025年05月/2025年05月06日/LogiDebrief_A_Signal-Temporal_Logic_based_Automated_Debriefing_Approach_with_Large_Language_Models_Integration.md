# # LogiDebrief：基于信号时态逻辑的自动化简报方法，集成大型语言模型

发布时间：2025年05月06日

`LLM应用` `公共安全` `通话质量评估`

> LogiDebrief: A Signal-Temporal Logic based Automated Debriefing Approach with Large Language Models Integration

# 摘要

> 紧急响应服务对公共安全至关重要，其中9-1-1接线员在确保及时有效的紧急行动中发挥着关键作用。为了保证接听电话的一致性，我们实施了质量保证措施，用于评估和提升接线员的技能。然而，传统的以人工为主的评估方式在面对大量电话时显得力不从心，导致覆盖范围有限和评估延迟。我们很高兴介绍LogiDebrief，这是一个创新的AI驱动框架，通过整合信号时态逻辑（STL）与大型语言模型（LLMs），实现了对传统9-1-1电话的自动化回溯，从而进行全面且严格的性能评估。LogiDebrief将接听电话的要求转化为逻辑规范，能够系统地评估9-1-1电话是否符合程序指南。它采用了一个三步验证流程：首先进行上下文理解，识别响应者类型、事件分类和关键情况；然后结合LLM进行STL运行时检查，确保合规性；最后自动汇总结果到质量保证报告中。除了技术上的突破，LogiDebrief还展示了显著的实际影响。它成功部署在纳什维尔大都会紧急通信部，协助回溯了1,701个真实电话，节省了311.85小时的活跃参与时间。通过真实数据的实证评估，我们证实了其准确性，而案例研究和广泛的用户研究则突显了其在提升接听电话表现方面的有效性。

> Emergency response services are critical to public safety, with 9-1-1 call-takers playing a key role in ensuring timely and effective emergency operations. To ensure call-taking performance consistency, quality assurance is implemented to evaluate and refine call-takers' skillsets. However, traditional human-led evaluations struggle with high call volumes, leading to low coverage and delayed assessments. We introduce LogiDebrief, an AI-driven framework that automates traditional 9-1-1 call debriefing by integrating Signal-Temporal Logic (STL) with Large Language Models (LLMs) for fully-covered rigorous performance evaluation. LogiDebrief formalizes call-taking requirements as logical specifications, enabling systematic assessment of 9-1-1 calls against procedural guidelines. It employs a three-step verification process: (1) contextual understanding to identify responder types, incident classifications, and critical conditions; (2) STL-based runtime checking with LLM integration to ensure compliance; and (3) automated aggregation of results into quality assurance reports. Beyond its technical contributions, LogiDebrief has demonstrated real-world impact. Successfully deployed at Metro Nashville Department of Emergency Communications, it has assisted in debriefing 1,701 real-world calls, saving 311.85 hours of active engagement. Empirical evaluation with real-world data confirms its accuracy, while a case study and extensive user study highlight its effectiveness in enhancing call-taking performance.

[Arxiv](https://arxiv.org/abs/2505.03985)