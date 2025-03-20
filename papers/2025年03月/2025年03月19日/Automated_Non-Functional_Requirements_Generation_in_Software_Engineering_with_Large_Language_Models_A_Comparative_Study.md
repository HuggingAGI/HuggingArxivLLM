# 软件工程中的自动化非功能性需求生成：基于大型语言模型的比较研究

发布时间：2025年03月19日

`LLM应用` `软件工程` `需求工程`

> Automated Non-Functional Requirements Generation in Software Engineering with Large Language Models: A Comparative Study

# 摘要

> 忽视非功能性需求（NFRs）在软件开发早期可能会带来严重挑战。尽管NFRs对软件质量至关重要，但它们往往被忽视或难以识别。为了解决这一问题，我们开发了一个基于大型语言模型（LLMs）的框架，从功能性需求（FRs）中提取质量驱动的NFRs。通过在Deno管道中采用自定义提示技术，系统能够为每个FR识别相关质量属性，并生成对应的NFRs，从而实现系统化集成。

评估这些生成需求的质量和适用性是关键。我们选取34个功能性需求（作为3,964个FRs的代表性子集），基于ISO/IEC 25010:2023标准，通过LLMs推断出适用属性，生成了1,593个NFRs。评估从三个维度展开：NFR有效性、质量属性适用性以及分类精度。十位平均拥有13年经验的行业专家对部分生成结果进行了评估，结果显示LLM生成的NFRs与专家评估高度一致。在1-5分的评分中，有效性和适用性的中位数均为5.0（均值分别为4.63和4.59）。分类任务中，80.4%的LLM分配属性与专家选择匹配，8.3%接近匹配，11.3%不匹配。

对八种LLMs的比较分析显示了性能差异：gemini-1.5-pro在属性准确性上表现最佳，而llama-3.3-70B在有效性和适用性评分上更高。这些发现不仅证明了LLMs在自动化NFR生成中的可行性，也为进一步探索AI辅助需求工程奠定了基础。


> Neglecting non-functional requirements (NFRs) early in software development can lead to critical challenges. Despite their importance, NFRs are often overlooked or difficult to identify, impacting software quality. To support requirements engineers in eliciting NFRs, we developed a framework that leverages Large Language Models (LLMs) to derive quality-driven NFRs from functional requirements (FRs). Using a custom prompting technique within a Deno-based pipeline, the system identifies relevant quality attributes for each functional requirement and generates corresponding NFRs, aiding systematic integration. A crucial aspect is evaluating the quality and suitability of these generated requirements. Can LLMs produce high-quality NFR suggestions? Using 34 functional requirements - selected as a representative subset of 3,964 FRs-the LLMs inferred applicable attributes based on the ISO/IEC 25010:2023 standard, generating 1,593 NFRs. A horizontal evaluation covered three dimensions: NFR validity, applicability of quality attributes, and classification precision. Ten industry software quality evaluators, averaging 13 years of experience, assessed a subset for relevance and quality. The evaluation showed strong alignment between LLM-generated NFRs and expert assessments, with median validity and applicability scores of 5.0 (means: 4.63 and 4.59, respectively) on a 1-5 scale. In the classification task, 80.4% of LLM-assigned attributes matched expert choices, with 8.3% near misses and 11.3% mismatches. A comparative analysis of eight LLMs highlighted variations in performance, with gemini-1.5-pro exhibiting the highest attribute accuracy, while llama-3.3-70B achieved higher validity and applicability scores. These findings provide insights into the feasibility of using LLMs for automated NFR generation and lay the foundation for further exploration of AI-assisted requirements engineering.

[Arxiv](https://arxiv.org/abs/2503.15248)