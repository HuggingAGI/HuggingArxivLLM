# # 基于大型语言模型的小学数学文字题生成
通过大型语言模型实现小学数学文字题的生成

发布时间：2025年06月06日

`LLM应用` `数学教育`

> Elementary Math Word Problem Generation using Large Language Models

# 摘要

> 数学常被学生视为复杂难懂的学科，导致考试失败率居高不下。为了提高学生的数学能力，提供样题供他们练习解题是十分重要的。然而，手动创建数学应用题（MWPs）对于教师来说非常耗时，因为他们需要在遵守语法规则的同时用自然语言输入。现有的深度学习技术在生成数学应用题时，要么需要教师提供题目的初始部分，要么需要额外的信息，如方程式。本文提出了一种基于大型语言模型（LLMs）的数学应用题生成系统，该系统克服了对额外输入的需求。我们的系统只需要输入所需题目的数量、年级和题目类型（如加法、减法）。与现有的基于LLM的数学应用题生成解决方案不同，我们进行了广泛的实验，涵盖了不同的LLM、提示策略、提高题目多样性的技术，以及利用人类反馈提升LLM性能的技术。通过人工和自动化评估，我们证实了生成的数学应用题质量很高，几乎不存在拼写和语法错误。然而，LLM在生成符合指定年级和题目类型要求的问题时仍然面临挑战。

> Mathematics is often perceived as a complex subject by students, leading to high failure rates in exams. To improve Mathematics skills, it is important to provide sample questions for students to practice problem-solving. Manually creating Math Word Problems (MWPs) is time consuming for tutors, because they have to type in natural language while adhering to grammar and spelling rules of the language. Existing Deep Learning techniques for MWP generation either require a tutor to provide the initial portion of the MWP, and/or additional information such as an equation. In this paper, we present an MWP generation system based on Large Language Models (LLMs) that overcome the need for additional input - the only input to our system is the number of MWPs needed, the grade and the type of question (e.g. addition, subtraction). Unlike the existing LLM-based solutions for MWP generation, we carried out an extensive set of experiments involving different LLMs, prompting strategies, techniques to improve the diversity of questions, as well as techniques that employ human feedback to improve LLM performance. Human and automated evaluations confirmed that the generated MWPs are high in quality, with minimal spelling and grammar issues. However, LLMs still struggle to generate questions that adhere to the specified grade and question type requirements.

[Arxiv](https://arxiv.org/abs/2506.05950)