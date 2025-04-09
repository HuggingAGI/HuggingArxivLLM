# EduPlanner：基于 LLM 的多智能体系统，助力个性化智能教学设计

发布时间：2025年04月07日

`LLM应用

摘要中详细描述了大型语言模型在智能教育中的应用，特别是通过多智能体系统EduPlanner来优化教学设计。虽然提到了智能体，但核心是LLM在教育中的应用，因此属于LLM应用类别。` `教学设计`

> EduPlanner: LLM-Based Multi-Agent Systems for Customized and Intelligent Instructional Design

# 摘要

> 大型语言模型（LLMs）在人工通用智能（AGI）时代为智能教育带来了革命性的提升。其中，教学设计的自动泛化应用尤为突出，特别是在课程与学习活动的设计中，主要聚焦于两大核心方面：(1) 定制化生成：根据学生不同的学习能力和状态，量身定制教学内容；(2) 智能优化：通过学习效果或考试成绩的反馈，持续迭代优化教学内容。然而，目前单一的大型LLM尚无法全面胜任整个流程，为智能教学计划的设计带来了挑战。为了解决这一问题，我们开发了EduPlanner——一个基于LLM的多智能体系统，由评估智能体、优化智能体和问题分析师组成，通过协作对抗的方式，实现课程与学习活动的定制化、智能化教学设计。以数学课程为例，EduPlanner创新性地采用了Skill-Tree结构，精准建模学生群体的数学背景知识，根据学生知识水平和学习能力，个性化设计教学方案。此外，我们引入了CIDDP——一个基于LLM的五维评估模块，涵盖清晰度、完整性、深度、实用性和相关性，全面评估数学课程计划质量并引导智能优化。实验结果表明，EduPlanner在课程与学习活动的教学设计评估与优化方面表现卓越。消融实验进一步验证了框架内各组件的重要性和有效性。我们的代码已公开发布于 https://github.com/Zc0812/Edu_Planner

> Large Language Models (LLMs) have significantly advanced smart education in the Artificial General Intelligence (AGI) era. A promising application lies in the automatic generalization of instructional design for curriculum and learning activities, focusing on two key aspects: (1) Customized Generation: generating niche-targeted teaching content based on students' varying learning abilities and states, and (2) Intelligent Optimization: iteratively optimizing content based on feedback from learning effectiveness or test scores. Currently, a single large LLM cannot effectively manage the entire process, posing a challenge for designing intelligent teaching plans. To address these issues, we developed EduPlanner, an LLM-based multi-agent system comprising an evaluator agent, an optimizer agent, and a question analyst, working in adversarial collaboration to generate customized and intelligent instructional design for curriculum and learning activities. Taking mathematics lessons as our example, EduPlanner employs a novel Skill-Tree structure to accurately model the background mathematics knowledge of student groups, personalizing instructional design for curriculum and learning activities according to students' knowledge levels and learning abilities. Additionally, we introduce the CIDDP, an LLM-based five-dimensional evaluation module encompassing clarity, Integrity, Depth, Practicality, and Pertinence, to comprehensively assess mathematics lesson plan quality and bootstrap intelligent optimization. Experiments conducted on the GSM8K and Algebra datasets demonstrate that EduPlanner excels in evaluating and optimizing instructional design for curriculum and learning activities. Ablation studies further validate the significance and effectiveness of each component within the framework. Our code is publicly available at https://github.com/Zc0812/Edu_Planner

[Arxiv](https://arxiv.org/abs/2504.05370)