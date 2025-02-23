# 从正确性到理解：助力个性化错误诊断的教育AI智能助手

发布时间：2025年02月19日

`LLM应用` `个性化教育` `教育技术`

> From Correctness to Comprehension: AI Agents for Personalized Error Diagnosis in Education

# 摘要

> 大型语言模型（LLMs），如GPT-4，虽然在数学推理方面表现卓越，但在个性化教育中的应用却面临挑战。现有模型过分追求正确性，忽视了对错误的深入分析和有效的反馈生成，导致其教育价值受限。针对这一问题，我们提出了三大创新方案。首先，我们推出了	extbf{MathCCS}，一个专注于系统性错误分析和个性化反馈的多模态基准，包含真实问题、专家标注的错误类型和学生长期数据。实验结果显示，即便是	extit{Qwen2-VL}、	extit{LLaVA-OV}、	extit{Claude-3.5-Sonnet}和	extit{GPT-4o}等先进模型，其分类准确率也未超过30%，建议质量平均得分仅4/10，与人类水平差距显著。其次，我们开发了一个基于历史数据的趋势追踪框架，显著提升了诊断精度。最后，我们设计了一种多智能体协作系统，整合时间序列分析和实时优化功能，进一步优化了错误分类和反馈生成效果。这些成果为个性化教育的未来发展奠定了坚实基础，有效连接了AI技术与实际教学需求。

> Large Language Models (LLMs), such as GPT-4, have demonstrated impressive mathematical reasoning capabilities, achieving near-perfect performance on benchmarks like GSM8K. However, their application in personalized education remains limited due to an overemphasis on correctness over error diagnosis and feedback generation. Current models fail to provide meaningful insights into the causes of student mistakes, limiting their utility in educational contexts. To address these challenges, we present three key contributions. First, we introduce \textbf{MathCCS} (Mathematical Classification and Constructive Suggestions), a multi-modal benchmark designed for systematic error analysis and tailored feedback. MathCCS includes real-world problems, expert-annotated error categories, and longitudinal student data. Evaluations of state-of-the-art models, including \textit{Qwen2-VL}, \textit{LLaVA-OV}, \textit{Claude-3.5-Sonnet} and \textit{GPT-4o}, reveal that none achieved classification accuracy above 30\% or generated high-quality suggestions (average scores below 4/10), highlighting a significant gap from human-level performance. Second, we develop a sequential error analysis framework that leverages historical data to track trends and improve diagnostic precision. Finally, we propose a multi-agent collaborative framework that combines a Time Series Agent for historical analysis and an MLLM Agent for real-time refinement, enhancing error classification and feedback generation. Together, these contributions provide a robust platform for advancing personalized education, bridging the gap between current AI capabilities and the demands of real-world teaching.

[Arxiv](https://arxiv.org/abs/2502.13789)