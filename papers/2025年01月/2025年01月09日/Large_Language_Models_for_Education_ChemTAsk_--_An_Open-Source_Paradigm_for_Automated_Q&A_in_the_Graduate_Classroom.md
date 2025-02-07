# 教育领域的大型语言模型：ChemTAsk —— 研究生课堂自动问答的开源新范式

发布时间：2025年01月09日

`RAG

理由：这篇论文主要讨论了结合大型语言模型（LLMs）和检索增强生成（RAG）的ChemTAsk系统，用于研究生教育辅助。论文的核心在于利用RAG技术来增强LLMs的准确性和上下文相关性，特别是在教育场景中的应用。因此，这篇论文应归类为RAG。`

> Large Language Models for Education: ChemTAsk -- An Open-Source Paradigm for Automated Q&A in the Graduate Classroom

# 摘要

> # 摘要
大型语言模型（LLMs）在研究生教育辅助中展现出潜力，但其训练数据和潜在的虚构内容限制了其应用。我们开发了ChemTAsk，一个结合LLMs和检索增强生成（RAG）的开源管道，旨在提供准确且上下文相关的帮助。ChemTAsk利用课程材料，如讲座记录和主要出版物，生成对学生查询的精准回答。在宾夕法尼亚大学高级生物化学课程的九周实验中，学生可选择使用ChemTAsk辅助作业或理解课程内容。比较分析显示，ChemTAsk在理解学生问题和提供准确信息方面与人类助教（TAs）表现相当，尤其在创造性问题解决任务中表现突出。相比之下，TAs的回答更为精确，且能根据课程特点定制帮助。学生反馈认为ChemTAsk比TAs更准确、更有帮助且响应更快。Meta和OpenAI的开源与专有模型在原始生物化学基准上进行了测试，以优化ChemTAsk的未来版本。结果显示，OpenAI模型对输入提示的偏差更具容忍性，并在自我评估方面表现优异，有效防止了潜在的虚构内容。总体而言，ChemTAsk展示了LLMs与RAG结合在教育支持中的巨大潜力，为学生和教育者提供了一个可扩展的工具。

> Large language models (LLMs) show promise for aiding graduate level education, but are limited by their training data and potential confabulations. We developed ChemTAsk, an open-source pipeline that combines LLMs with retrieval-augmented generation (RAG) to provide accurate, context-specific assistance. ChemTAsk utilizes course materials, including lecture transcripts and primary publications, to generate accurate responses to student queries. Over nine weeks in an advanced biological chemistry course at the University of Pennsylvania, students could opt in to use ChemTAsk for assistance in any assignment or to understand class material. Comparative analysis showed ChemTAsk performed on par with human teaching assistants (TAs) in understanding student queries and providing accurate information, particularly excelling in creative problem-solving tasks. In contrast, TAs were more precise in their responses and tailored their assistance to the specifics of the class. Student feedback indicated that ChemTAsk was perceived as correct, helpful, and faster than TAs. Open-source and proprietary models from Meta and OpenAI respectively were tested on an original biological chemistry benchmark for future iterations of ChemTAsk. It was found that OpenAI models were more tolerant to deviations in the input prompt and excelled in self-assessment to safeguard for potential confabulations. Taken together, ChemTAsk demonstrates the potential of integrating LLMs with RAG to enhance educational support, offering a scalable tool for students and educators.

[Arxiv](https://arxiv.org/abs/2502.00016)