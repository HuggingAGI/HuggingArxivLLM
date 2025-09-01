# HealthProcessAI：基于大型语言模型增强的医疗流程挖掘技术框架与概念验证

发布时间：2025年08月29日

`LLM应用` `医疗健康`

> HealthProcessAI: A Technical Framework and Proof-of-Concept for LLM-Enhanced Healthcare Process Mining

# 摘要

> 流程挖掘已成为解析复杂医疗工作流的强大分析技术，但在实际应用中仍面临诸多阻碍，如技术复杂度高、缺乏标准化方法，以及实用培训资源难以获取。为此，我们推出HealthProcessAI——一个生成式人工智能（GenAI）框架。该框架通过全面封装现有的Python（PM4PY）和R（bupaR）库，致力于简化流程挖掘在医疗与流行病学领域的应用。为消除使用门槛并提升易用性，框架集成了多个大型语言模型（LLMs），可自动解读流程图谱并生成报告，助力将技术分析转化为各类用户都能轻松理解的结果。我们以脓毒症进展数据为概念验证案例，对该框架进行了有效性验证，同时通过OpenRouter平台对比了五个顶尖LLM模型的输出结果。为测试其功能，该框架在四个概念验证场景中成功处理了脓毒症数据，展现出优异的技术性能，以及通过自动化LLM分析生成报告的能力。我们采用五个独立的LLM作为自动化评估工具，对模型性能进行评估，结果显示各模型各具优势：其中Claude Sonnet-4和Gemini 2.5-Pro在自动化LLM评估中表现最佳，一致性评分分别达到3.79/4.0和3.65/4.0。通过集成多个大型语言模型（LLMs）实现自动化解读与报告生成，该框架有效解决了用户对流程挖掘结果普遍不熟悉的问题，让临床医生、数据科学家和研究人员都能更轻松地理解和使用这些结果。这种结构化分析与AI驱动解读相结合的方式，标志着在将复杂流程挖掘结果转化为医疗应用中潜在可操作见解方面，取得了创新性的方法学突破。

> Process mining has emerged as a powerful analytical technique for understanding complex healthcare workflows. However, its application faces significant barriers, including technical complexity, a lack of standardized approaches, and limited access to practical training resources. We introduce HealthProcessAI, a GenAI framework designed to simplify process mining applications in healthcare and epidemiology by providing a comprehensive wrapper around existing Python (PM4PY) and R (bupaR) libraries. To address unfamiliarity and improve accessibility, the framework integrates multiple Large Language Models (LLMs) for automated process map interpretation and report generation, helping translate technical analyses into outputs that diverse users can readily understand. We validated the framework using sepsis progression data as a proof-of-concept example and compared the outputs of five state-of-the-art LLM models through the OpenRouter platform. To test its functionality, the framework successfully processed sepsis data across four proof-of-concept scenarios, demonstrating robust technical performance and its capability to generate reports through automated LLM analysis. LLM evaluation using five independent LLMs as automated evaluators revealed distinct model strengths: Claude Sonnet-4 and Gemini 2.5-Pro achieved the highest consistency scores (3.79/4.0 and 3.65/4.0) when evaluated by automated LLM assessors. By integrating multiple Large Language Models (LLMs) for automated interpretation and report generation, the framework addresses widespread unfamiliarity with process mining outputs, making them more accessible to clinicians, data scientists, and researchers. This structured analytics and AI-driven interpretation combination represents a novel methodological advance in translating complex process mining results into potentially actionable insights for healthcare applications.

[Arxiv](https://arxiv.org/abs/2508.21540)