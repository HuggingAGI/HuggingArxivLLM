# 宏观思考，微观行动：多智能体大语言模型在CWE识别中的应用

发布时间：2025年08月02日

`LLM应用` `信息安全` `软件工程`

> Think Broad, Act Narrow: CWE Identification with Multi-Agent Large Language Models

# 摘要

> 近年来，机器学习和大型语言模型（LLMs）在漏洞检测领域备受关注。然而，现有技术表明，LLMs在区分漏洞函数与其良性版本时表现不佳，主要归因于三个关键问题：漏洞检测需要深入分析，而LLMs在单次预测时往往难以胜任；现有技术通常仅执行函数级别的分析，而有效的漏洞检测需要超出函数范围的上下文信息；对二分类的过度关注可能导致识别漏洞但将其错误地关联到不相关的安全弱点（CWE），从而误导开发人员。我们提出了一种新颖的多智能体LLM方法来解决识别CWE的挑战。该方法包含三个步骤：（1）一组LLM智能体对审查函数中的潜在CWE进行彻底搜索，（2）另一组智能体识别支持或反驳每个候选CWE的相关外部上下文，（3）最终智能体根据收集到的上下文对每个CWE做出知情的接受或拒绝决策。我们方法的初步评估显示了有前景的结果。在PrimeVul数据集中，步骤1在40.9%的研究漏洞函数中正确识别了适当的CWE。我们进一步在十个合成程序上评估了整个流程，发现整合上下文信息显著降低了误报数量，从6到9个CWE减少到仅1到2个，同时仍然在10个案例中的9个正确识别了真正的CWE。

> Machine learning and Large language models (LLMs) for vulnerability detection has received significant attention in recent years. Unfortunately, state-of-the-art techniques show that LLMs are unsuccessful in even distinguishing the vulnerable function from its benign counterpart, due to three main problems: Vulnerability detection requires deep analysis, which LLMs often struggle with when making a one-shot prediction. Existing techniques typically perform function-level analysis, whereas effective vulnerability detection requires contextual information beyond the function scope. The focus on binary classification can result in identifying a vulnerability but associating it with the wrong security weaknesses (CWE), which may mislead developers. We propose a novel multi-agent LLM approach to address the challenges of identifying CWEs. This approach consists of three steps: (1) a team of LLM agents performs an exhaustive search for potential CWEs in the function under review, (2) another team of agents identifies relevant external context to support or refute each candidate CWE, and (3) a final agent makes informed acceptance or rejection decisions for each CWE based on the gathered context. A preliminary evaluation of our approach shows promising results. In the PrimeVul dataset, Step 1 correctly identifies the appropriate CWE in 40.9\% of the studied vulnerable functions. We further evaluated the full pipeline on ten synthetic programs and found that incorporating context information significantly reduced false positives from 6 to 9 CWEs to just 1 to 2, while still correctly identifying the true CWE in 9 out of 10 cases.

[Arxiv](https://arxiv.org/abs/2508.01451)