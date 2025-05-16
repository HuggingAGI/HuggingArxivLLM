# 图检索增强生成在MOOC学习者知识概念理解中的应用

发布时间：2025年05月15日

`RAG` `知识图谱`

> Leveraging Graph Retrieval-Augmented Generation to Support Learners' Understanding of Knowledge Concepts in MOOCs

# 摘要

> 大规模开放在线课程（MOOCs）由于缺乏师生直接互动，使得学习者难以掌握新知识。近年来，学习者开始借助大型语言模型（LLMs）来辅助学习，但LLMs容易产生幻觉，可靠性不足。检索增强生成（RAG）通过先检索文档再生成回答来解决这一问题，但非结构化学习材料限制了其在MOOCs中的应用。此外，现有RAG系统未能主动满足学习者的学习需求。

为解决这些问题，我们提出了一种基于教育知识图谱（EduKGs）和个人知识图谱（PKGs）的Graph RAG管道，以帮助学习者在MOOC平台CourseMapper上更好地理解知识概念。具体而言，我们实现了两项创新：（1）基于PKG的问题生成方法，能够根据学习者需求推荐个性化问题；（2）基于EduKG的问题回答方法，通过知识图谱中的概念关系提供精准解答。

我们在CourseMapper平台上选取了3个不同MOOCs，并与3位专家教师合作进行了实验研究。结果表明，Graph RAG能够有效提升学习者在个性化学习过程中的知识理解能力，展现了广阔的应用前景。

> Massive Open Online Courses (MOOCs) lack direct interaction between learners and instructors, making it challenging for learners to understand new knowledge concepts. Recently, learners have increasingly used Large Language Models (LLMs) to support them in acquiring new knowledge. However, LLMs are prone to hallucinations which limits their reliability. Retrieval-Augmented Generation (RAG) addresses this issue by retrieving relevant documents before generating a response. However, the application of RAG across different MOOCs is limited by unstructured learning material. Furthermore, current RAG systems do not actively guide learners toward their learning needs. To address these challenges, we propose a Graph RAG pipeline that leverages Educational Knowledge Graphs (EduKGs) and Personal Knowledge Graphs (PKGs) to guide learners to understand knowledge concepts in the MOOC platform CourseMapper. Specifically, we implement (1) a PKG-based Question Generation method to recommend personalized questions for learners in context, and (2) an EduKG-based Question Answering method that leverages the relationships between knowledge concepts in the EduKG to answer learner selected questions. To evaluate both methods, we conducted a study with 3 expert instructors on 3 different MOOCs in the MOOC platform CourseMapper. The results of the evaluation show the potential of Graph RAG to empower learners to understand new knowledge concepts in a personalized learning experience.

[Arxiv](https://arxiv.org/abs/2505.10074)