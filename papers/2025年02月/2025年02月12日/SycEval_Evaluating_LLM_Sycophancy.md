# # SycEval：评估大型语言模型的顺从性

发布时间：2025年02月12日

`LLM应用` `人工智能`

> SycEval: Evaluating LLM Sycophancy

# 摘要

> 大型语言模型（LLMs）在教育、临床和专业环境中的应用日益广泛，但其“阿谀奉承”倾向——优先迎合用户而非独立推理——给可靠性带来了风险。本研究提出了一种框架，用于评估 ChatGPT-4o、Claude-Sonnet 和 Gemini-1.5-Pro 在 AMPS（数学）和 MedQuad（医疗建议）数据集中的阿谀奉承行为。

研究发现，在 58.19% 的情况下观察到阿谀奉承行为，其中 Gemini 的发生率最高（62.47%），而 ChatGPT 的发生率最低（56.71%）。在 43.52% 的情况下，阿谀奉承行为导致了正确答案，而在 14.66% 的情况下，阿谀奉承行为导致了错误答案。预先反驳的阿谀奉承率显著高于上下文反驳（61.75% vs. 56.52%，$Z=5.87$，$p<0.001$），尤其是在计算任务中，消极阿谀奉承显著增加（预先：8.13%，上下文：3.54%，$p<0.001$）。简单反驳最大限度地提高了积极阿谀奉承（$Z=6.59$，$p<0.001$），而基于引用的反驳表现出最高的消极阿谀奉承率（$Z=6.59$，$p<0.001$）。

无论上下文或模型如何，阿谀奉承行为显示出高度的持续性（78.5%，95% CI：[77.2%，79.8%]）。这些发现强调了在结构化和动态领域部署 LLMs 的风险和机遇，为更安全的 AI 应用提供了关于提示编程和模型优化的深刻见解。

> Large language models (LLMs) are increasingly applied in educational, clinical, and professional settings, but their tendency for sycophancy -- prioritizing user agreement over independent reasoning -- poses risks to reliability. This study introduces a framework to evaluate sycophantic behavior in ChatGPT-4o, Claude-Sonnet, and Gemini-1.5-Pro across AMPS (mathematics) and MedQuad (medical advice) datasets. Sycophantic behavior was observed in 58.19% of cases, with Gemini exhibiting the highest rate (62.47%) and ChatGPT the lowest (56.71%). Progressive sycophancy, leading to correct answers, occurred in 43.52% of cases, while regressive sycophancy, leading to incorrect answers, was observed in 14.66%. Preemptive rebuttals demonstrated significantly higher sycophancy rates than in-context rebuttals (61.75% vs. 56.52%, $Z=5.87$, $p<0.001$), particularly in computational tasks, where regressive sycophancy increased significantly (preemptive: 8.13%, in-context: 3.54%, $p<0.001$). Simple rebuttals maximized progressive sycophancy ($Z=6.59$, $p<0.001$), while citation-based rebuttals exhibited the highest regressive rates ($Z=6.59$, $p<0.001$). Sycophantic behavior showed high persistence (78.5%, 95% CI: [77.2%, 79.8%]) regardless of context or model. These findings emphasize the risks and opportunities of deploying LLMs in structured and dynamic domains, offering insights into prompt programming and model optimization for safer AI applications.

[Arxiv](https://arxiv.org/abs/2502.08177)