# AlphaPhysics符号重写系统用于物理考试中评分代数表达式

发布时间：2025年07月24日

`LLM应用` `物理教育`

> The AlphaPhysics Term Rewriting System for Marking Algebraic Expressions in Physics Exams

# 摘要

> 我们提出了一种自动批改物理考试的方法。该方法主要涉及根据标准答案评估学生书面回答的正确性，这是一个极具挑战性的问题。我们结合了计算机代数系统、SMT求解器和术语重写系统来解决这一问题。大语言模型被用于理解和去除学生回答中的错误，并将其转换为机器可读的格式。在形式化和语言对齐后，我们将应用自动化推理技术来评估学生解答的正确性。我们采用了两种自动定理证明方法：现成的SMT求解和专门针对涉及三角表达式的物理问题定制的术语重写系统。开发术语重写系统并建立终止性和一致性属性是一项复杂的任务，我们在论文中对此进行了详细介绍。我们在2023年澳大利亚物理奥林匹克竞赛中超过1500份真实学生考试回答的丰富数据集上对我们的系统进行了评估。

> We present our method for automatically marking Physics exams. The marking problem consists in assessing typed student answers for correctness with respect to a ground truth solution. This is a challenging problem that we seek to tackle using a combination of a computer algebra system, an SMT solver and a term rewriting system. A Large Language Model is used to interpret and remove errors from student responses and rewrite these in a machine readable format. Once formalized and language-aligned, the next step then consists in applying automated reasoning techniques for assessing student solution correctness. We consider two methods of automated theorem proving: off-the-shelf SMT solving and term rewriting systems tailored for physics problems involving trigonometric expressions. The development of the term rewrite system and establishing termination and confluence properties was not trivial, and we describe it in some detail in the paper. We evaluate our system on a rich pool of over 1500 real-world student exam responses from the 2023 Australian Physics Olympiad.

[Arxiv](https://arxiv.org/abs/2507.18337)