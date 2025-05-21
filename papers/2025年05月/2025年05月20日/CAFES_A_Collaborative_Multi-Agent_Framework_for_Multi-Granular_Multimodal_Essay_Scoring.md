# CAFES：面向多粒度多模态作文评分的协作式多智能体框架

发布时间：2025年05月20日

`Agent`

> CAFES: A Collaborative Multi-Agent Framework for Multi-Granular Multimodal Essay Scoring

# 摘要

> 自动评分系统（AES）对现代教育至关重要，尤其是在多模态评估日益普及的背景下。然而，传统AES方法在评估泛化能力和多模态感知方面存在困难，而即使是最近基于多模态大型语言模型（MLLM）的方法，也可能生成不切实际的解释，评分与人工评判不一致。为了解决这些问题，我们推出了CAVES，这是首个专为AES设计的协作式多智能体框架。CAVES协调三个专门智能体：初始评分员，用于快速、针对具体特征的评估；反馈池管理员，汇总详细且有依据的优点；以及反思评分员，根据反馈逐步调整评分，以提升与人工评判的一致性。通过使用最先进的多模态大型语言模型进行广泛实验，CAVES在二次加权卡帕（QWK）评分上平均相对提升了21%，尤其是在语法和词汇多样性方面。我们提出的CAVES框架为智能多模态AES系统奠定了基础，代码将在接收后公开。

> Automated Essay Scoring (AES) is crucial for modern education, particularly with the increasing prevalence of multimodal assessments. However, traditional AES methods struggle with evaluation generalizability and multimodal perception, while even recent Multimodal Large Language Model (MLLM)-based approaches can produce hallucinated justifications and scores misaligned with human judgment. To address the limitations, we introduce CAFES, the first collaborative multi-agent framework specifically designed for AES. It orchestrates three specialized agents: an Initial Scorer for rapid, trait-specific evaluations; a Feedback Pool Manager to aggregate detailed, evidence-grounded strengths; and a Reflective Scorer that iteratively refines scores based on this feedback to enhance human alignment. Extensive experiments, using state-of-the-art MLLMs, achieve an average relative improvement of 21% in Quadratic Weighted Kappa (QWK) against ground truth, especially for grammatical and lexical diversity. Our proposed CAFES framework paves the way for an intelligent multimodal AES system. The code will be available upon acceptance.

[Arxiv](https://arxiv.org/abs/2505.13965)