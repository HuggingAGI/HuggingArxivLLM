# OpenAI HealthBench实践：基于真实临床查询评估LLM医疗助手

发布时间：2025年08月29日

`Agent` `医疗健康`

> OpenAIs HealthBench in Action: Evaluating an LLM-Based Medical Assistant on Realistic Clinical Queries

# 摘要

> 要评估大型语言模型（LLMs）生成高质量、准确且具备情境感知的临床问题答案的能力，不能仅依赖传统基准，还需考察其在复杂高风险临床场景中的实际表现。传统评估多局限于多选题，难以体现情境推理、感知及不确定性处理等关键能力。为此，我们借助HealthBench（一个由开放式专家注释健康对话构成的基于评分标准的基准），对智能体式、基于RAG的临床支持助手DR.INFO展开评估。在含1000个高难度案例的Hard子集上，DR.INFO的HealthBench得分为0.51，在所有行为维度（准确性、完整性、指令遵循等）均显著优于主流前沿LLMs（如GPT-5、o3、Grok 3、GPT-4、Gemini 2.5等）。在另一项针对同类智能体RAG助手（OpenEvidence、Pathway.md）的100样本评估中，其仍以0.54的HealthBench得分保持领先。这些结果既凸显了DR.INFO在沟通、指令遵循与准确性上的优势，也揭示了其在情境感知和回答完整性方面的提升空间。总体而言，研究证实，行为层面的评分标准评估对构建可靠可信的AI临床支持助手具有重要实用价值。

> Evaluating large language models (LLMs) on their ability to generate high-quality, accurate, situationally aware answers to clinical questions requires going beyond conventional benchmarks to assess how these systems behave in complex, high-stake clincal scenarios. Traditional evaluations are often limited to multiple-choice questions that fail to capture essential competencies such as contextual reasoning, awareness and uncertainty handling etc. To address these limitations, we evaluate our agentic, RAG-based clinical support assistant, DR.INFO, using HealthBench, a rubric-driven benchmark composed of open-ended, expert-annotated health conversations. On the Hard subset of 1,000 challenging examples, DR.INFO achieves a HealthBench score of 0.51, substantially outperforming leading frontier LLMs (GPT-5, o3, Grok 3, GPT-4, Gemini 2.5, etc.) across all behavioral axes (accuracy, completeness, instruction following, etc.). In a separate 100-sample evaluation against similar agentic RAG assistants (OpenEvidence, Pathway.md), it maintains a performance lead with a health-bench score of 0.54. These results highlight DR.INFOs strengths in communication, instruction following, and accuracy, while also revealing areas for improvement in context awareness and completeness of a response. Overall, the findings underscore the utility of behavior-level, rubric-based evaluation for building a reliable and trustworthy AI-enabled clinical support assistant.

[Arxiv](https://arxiv.org/abs/2509.02594)