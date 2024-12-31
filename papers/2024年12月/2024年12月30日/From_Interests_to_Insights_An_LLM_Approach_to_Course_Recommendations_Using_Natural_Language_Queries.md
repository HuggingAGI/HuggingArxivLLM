# 从兴趣到洞察：一种运用自然语言查询进行课程推荐的 LLM 方式

发布时间：2024年12月30日

`RAG` `课程推荐`

> From Interests to Insights: An LLM Approach to Course Recommendations Using Natural Language Queries

# 摘要

> 在美国的多数大学，都鼓励学生在选定专业前探索学术领域，并通过满足各类要求来拓展学术面。每学期，学生要从成千上万涵盖数十个学科领域的课程中选取几门课程。课程环境是动态变化的，校园内沟通与搜索功能的不足可能限制学生发现感兴趣的新课程。为给这样环境中的学生和顾问提供帮助，我们探索了一种新型的大型语言模型（LLM）课程推荐系统，它将检索增强生成（RAG）方法应用于课程描述的语料库。系统首先会依据用户的查询生成“理想”的课程描述，再利用嵌入将其转化为搜索向量，然后通过比较嵌入相似度来查找内容相似的实际课程。我们阐述了该方法，并评估了部分示例提示的质量和公平性，还探讨了在校园部署试点系统的步骤。

> Most universities in the United States encourage their students to explore academic areas before declaring a major and to acquire academic breadth by satisfying a variety of requirements. Each term, students must choose among many thousands of offerings, spanning dozens of subject areas, a handful of courses to take. The curricular environment is also dynamic, and poor communication and search functions on campus can limit a student's ability to discover new courses of interest. To support both students and their advisers in such a setting, we explore a novel Large Language Model (LLM) course recommendation system that applies a Retrieval Augmented Generation (RAG) method to the corpus of course descriptions. The system first generates an 'ideal' course description based on the user's query. This description is converted into a search vector using embeddings, which is then used to find actual courses with similar content by comparing embedding similarities. We describe the method and assess the quality and fairness of some example prompts. Steps to deploy a pilot system on campus are discussed.

[Arxiv](https://arxiv.org/abs/2412.19312)