# # 概述  
ELOQUENT 2025实验室中的Sensemaking任务：LLMs在其中扮演教师、学生和评估者的角色

发布时间：2025年07月16日

`LLM应用`

> Overview of the Sensemaking Task at the ELOQUENT 2025 Lab: LLMs as Teachers, Students and Evaluators

# 摘要

> ELOQUENT 是一套共享任务，致力于为评估生成式语言模型创建易于测试的高级标准。Sensemaking 是其中一个典型任务。在 Sensemaking 中，我们通过三个步骤评估生成模型如何“从给定文本中理解意义”，这些步骤受到课堂考试的启发：(1) 教师系统需准备一组问题，(2) 学生系统需回答这些问题，(3) 评估系统需对这些答案进行评分，所有步骤都严格遵循给定的输入材料。

在 2025 年的 Sensemaking 中，我们采用了 7 个测试材料来源（包括事实核查分析、教科书、讲座录音转录和教育视频），覆盖了英语、德语、乌克兰语和捷克语。

今年有 4 个团队参与，为我们提供了 2 个教师系统、2 个学生系统和 2 个评估系统的提交。我们还引入了商业大型语言模型系统作为教师和学生的基线。我们设计了一个完全自动化的评估流程，并与极简的手动评估进行了对比。

通过实验，我们发现了一些有趣的现象。在第一个任务“创建问题”中，现有的评估策略仍有待改进，因为很难区分各种候选问题集的质量。在第二个任务“问答”中，LLM 的整体表现尚可，但限制它们的回答仅基于给定输入文本的约束仍然存在问题。在第三个任务“评估答案”中，我们的对抗性测试表明，采用 LLM 作为“裁判”的系统会错误地将混乱的问题-答案对以及对混淆问题的回答评为可接受。

> ELOQUENT is a set of shared tasks that aims to create easily testable high-level criteria for evaluating generative language models. Sensemaking is one such shared task.
  In Sensemaking, we try to assess how well generative models ``make sense out of a given text'' in three steps inspired by exams in a classroom setting: (1) Teacher systems should prepare a set of questions, (2) Student systems should answer these questions, and (3) Evaluator systems should score these answers, all adhering rather strictly to a given set of input materials.
  We report on the 2025 edition of Sensemaking, where we had 7 sources of test materials (fact-checking analyses of statements, textbooks, transcribed recordings of a lecture, and educational videos) spanning English, German, Ukrainian, and Czech languages.
  This year, 4 teams participated, providing us with 2 Teacher submissions, 2 Student submissions, and 2 Evaluator submissions. We added baselines for Teacher and Student using commercial large language model systems. We devised a fully automatic evaluation procedure, which we compare to a minimalistic manual evaluation.
  We were able to make some interesting observations. For the first task, the creation of questions, better evaluation strategies will still have to be devised because it is difficult to discern the quality of the various candidate question sets. In the second task, question answering, the LLMs examined overall perform acceptably, but restricting their answers to the given input texts remains problematic. In the third task, evaluation of question answers, our adversarial tests reveal that systems using the LLM-as-a-Judge paradigm erroneously rate both garbled question-answer pairs and answers to mixed-up questions as acceptable.

[Arxiv](https://arxiv.org/abs/2507.12143)