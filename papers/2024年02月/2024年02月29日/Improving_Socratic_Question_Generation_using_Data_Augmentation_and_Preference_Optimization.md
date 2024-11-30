# 运用数据增强与偏好优化策略提升苏格拉底式问题生成效果，本研究致力于优化和完善该技术在生成高质量、启发性问题方面的表现。

发布时间：2024年02月29日

`LLM应用`

> Improving Socratic Question Generation using Data Augmentation and Preference Optimization

# 摘要

> 苏格拉底教学法巧妙地引领学生独立解题，而不直接给出答案，有助于显著提升学生的学习成效，但对教师而言却是一项复杂耗时的任务。为此，我们可以借助大型语言模型（LLMs）自动生成苏格拉底式问题，减轻教师负担。不过，当前采用LLMs生成问题时，偶尔会出现直接泄露答案或提供无关紧要、时机不当的问题。受RLAIF强化学习启示，我们首先创新性地提出一种数据扩充技术，有针对性地用特定类型的无效问题充实现存的苏格拉底问题数据集。然后，我们运用直接偏好优化（DPO）技术，优化诸如LLama 2这样的开源LLMs，让其更倾向于选择真实问题而非生成的无效问题。实验证明，在学生代码调试的苏格拉底问题数据集中，经DPO优化的7B参数LLama 2模型能够有效规避生成无效问题，并因此在性能上超越了现有的顶级提示方法。

> The Socratic method is a way of guiding students toward solving a problem independently without directly revealing the solution to the problem. Although this method has been shown to significantly improve student learning outcomes, it remains a complex labor-intensive task for instructors. Large language models (LLMs) can be used to augment human effort by automatically generating Socratic questions for students. However, existing methods that involve prompting these LLMs sometimes produce invalid outputs, e.g., those that directly reveal the solution to the problem or provide irrelevant or premature questions. To alleviate this problem, inspired by reinforcement learning with AI feedback (RLAIF), we first propose a data augmentation method to enrich existing Socratic questioning datasets with questions that are invalid in specific ways. Next, we propose a method to optimize open-source LLMs such as LLama 2 to prefer ground-truth questions over generated invalid ones, using direct preference optimization (DPO). Our experiments on a Socratic questions dataset for student code debugging show that a DPO-optimized 7B LLama 2 model can effectively avoid generating invalid questions, and as a result, outperforms existing state-of-the-art prompting methods.

[Arxiv](https://arxiv.org/abs/2403.00199)