# MATRIX：多智能体模拟框架——用于安全交互与情境化临床对话评估

发布时间：2025年08月26日

`LLM应用` `医疗健康`

> MATRIX: Multi-Agent simulaTion fRamework for safe Interactions and conteXtual clinical conversational evaluation

# 摘要

> 尽管大型语言模型（LLMs）在临床对话系统中的应用愈发广泛，但现有评估多聚焦于任务完成度或流畅度，对安全关键系统不可或缺的行为规范与风险管理要求却缺乏深入考察。本文提出MATRIX（多智能体模拟框架，用于安全交互及情境化临床对话评估）——一个结构化、可扩展的框架，专为临床对话智能体的安全性评估设计。
  MATRIX包含三大核心组件：（1）基于结构化安全工程方法构建的安全导向分类体系，涵盖临床场景、系统预期行为及失效模式；（2）行为判断器（BehvJudge）——基于LLM的评估工具，可精准识别安全相关对话失误，并通过专家临床医生标注验证其有效性；（3）患者模拟机器人（PatBot）——能生成场景驱动的多样化回应，其真实性与行为一致性已通过人因工程专业评估及患者偏好研究双重验证。
  三项实验结果表明，MATRIX可实现系统性、可扩展的安全性评估。搭载Gemini 2.5-Pro的行为判断器展现出专家级风险检测能力（F1值0.96，灵敏度0.999），在240段对话的盲法评估中表现超越临床医生。我们还首次对基于LLM的患者模拟进行真实性分析，发现患者模拟机器人在定量与定性评估中均能稳定模拟真实患者行为。通过MATRIX，我们对五个LLM智能体完成基准测试，覆盖2100段模拟对话、14个风险场景及10个临床领域。
  MATRIX首创性地将结构化安全工程与可扩展、经过验证的对话式AI评估相融合，为符合监管要求的安全审计奠定基础。我们已公开所有评估工具、提示词、结构化场景及数据集。

> Despite the growing use of large language models (LLMs) in clinical dialogue systems, existing evaluations focus on task completion or fluency, offering little insight into the behavioral and risk management requirements essential for safety-critical systems. This paper presents MATRIX (Multi-Agent simulaTion fRamework for safe Interactions and conteXtual clinical conversational evaluation), a structured, extensible framework for safety-oriented evaluation of clinical dialogue agents.
  MATRIX integrates three components: (1) a safety-aligned taxonomy of clinical scenarios, expected system behaviors and failure modes derived through structured safety engineering methods; (2) BehvJudge, an LLM-based evaluator for detecting safety-relevant dialogue failures, validated against expert clinician annotations; and (3) PatBot, a simulated patient agent capable of producing diverse, scenario-conditioned responses, evaluated for realism and behavioral fidelity with human factors expertise, and a patient-preference study.
  Across three experiments, we show that MATRIX enables systematic, scalable safety evaluation. BehvJudge with Gemini 2.5-Pro achieves expert-level hazard detection (F1 0.96, sensitivity 0.999), outperforming clinicians in a blinded assessment of 240 dialogues. We also conducted one of the first realism analyses of LLM-based patient simulation, showing that PatBot reliably simulates realistic patient behavior in quantitative and qualitative evaluations. Using MATRIX, we demonstrate its effectiveness in benchmarking five LLM agents across 2,100 simulated dialogues spanning 14 hazard scenarios and 10 clinical domains.
  MATRIX is the first framework to unify structured safety engineering with scalable, validated conversational AI evaluation, enabling regulator-aligned safety auditing. We release all evaluation tools, prompts, structured scenarios, and datasets.

[Arxiv](https://arxiv.org/abs/2508.19163)