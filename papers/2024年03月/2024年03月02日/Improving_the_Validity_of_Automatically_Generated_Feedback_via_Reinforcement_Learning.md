# 本研究运用强化学习技术，致力于提升自动化生成反馈的可靠性和准确性。

发布时间：2024年03月02日

`LLM应用`

> Improving the Validity of Automatically Generated Feedback via Reinforcement Learning

# 摘要

> 借助LLMs在智能教学系统和在线平台自动生成反馈，有助于提升广大学生的学习效果。但无论是生成还是评估反馈，都面临着艰巨挑战——特别是在数学这类科目中，要求模型深入理解问题、答案及学生的误区，确保反馈内容准确无误；同时，反馈还需遵循教育原则，反映有效的教学策略，例如解读潜在误解，激励学生等。本研究旨在解决反馈生成与评估两大难题，并兼顾其准确性与针对性。首先，我们设计了一套数学反馈评估准则，实验证明GPT-4能成功运用此准则评价人工编写和LLMs生成的反馈。接着，我们提出一套基于强化学习(RL)的反馈生成框架，旨在同步优化反馈的准确度与针对性。具体而言，我们利用GPT-4标注的反馈信息，在增强数据集上构建反馈对的优先级关系，通过直接偏好优化(DPO)方法进行训练。研究表明，采用此方法可显著提升开源LLM Llama 2生成反馈的准确度与针对性。此外，我们通过对案例研究的定性分析，展示了生成与评估系统的效能，并指出了未来工作的几个重要方向。

> Automatically generating feedback via large language models (LLMs) in intelligent tutoring systems and online learning platforms has the potential to improve the learning outcomes of many students. However, both feedback generation and evaluation are challenging: feedback content has to be valid especially in subjects like math, which requires models to understand the problem, the solution, and where the student's error lies. Feedback also has to be pedagogically valid to reflect effective tutoring strategies, such as explaining possible misconceptions and encouraging the student, among other desirable features. In this work, we address both problems of automatically generating and evaluating feedback while considering both correctness and alignment. First, we propose a rubric for evaluating math feedback and show that GPT-4 is able to effectively use it to annotate human-written and LLM-generated feedback. Second, we propose a framework for feedback generation that optimizes both correctness and alignment using reinforcement learning (RL). Specifically, we use GPT-4's annotations to create preferences over feedback pairs in an augmented dataset for training via direct preference optimization (DPO). We show that our methods significantly increase the correctness and alignment of generated feedback with Llama 2, an open-source LLM, qualitatively analyze our generation and evaluation systems using case studies, and outline several areas for future work.

[Arxiv](https://arxiv.org/abs/2403.01304)