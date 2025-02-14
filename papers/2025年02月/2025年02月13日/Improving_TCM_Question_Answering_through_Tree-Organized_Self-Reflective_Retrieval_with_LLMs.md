# 结合大语言模型，采用树状组织的自我反思检索方法，提升中医问答效果

发布时间：2025年02月13日

`RAG` `中医药` `问答系统`

> Improving TCM Question Answering through Tree-Organized Self-Reflective Retrieval with LLMs

# 摘要

> # 目标
大型语言模型（LLMs）能够利用医学知识进行智能问答（Q&A），为辅助诊断和医学人才培养带来潜力。然而，中医药领域（TCM）目前缺乏高效的检索增强生成（RAG）框架。本研究旨在探讨树状组织自我反思检索（TOSRR）框架在LLMs中的应用效果，特别是在中医问答任务中。
# 材料与方法
我们创新性地构建了一个层次分明的树状知识库，并在推理过程中通过自我反思框架整合跨章节信息。研究数据来自中医执业医师资格考试（MLE）和大学经典课程考试（CCE），随机选取问题作为基准数据集。
# 结果
结合GPT-4，该框架在中医MLE基准上的绝对准确率提升了19.85%，CCE数据集的召回准确率从27%跃升至38%。人工评估显示，框架在安全性、一致性、可解释性、合规性和连贯性等方面整体提升了18.52分。
# 结论
TOSRR框架显著增强了LLM在中医问答任务中的表现，展现了其在中医药领域的重要应用价值。


> Objectives: Large language models (LLMs) can harness medical knowledge for intelligent question answering (Q&A), promising support for auxiliary diagnosis and medical talent cultivation. However, there is a deficiency of highly efficient retrieval-augmented generation (RAG) frameworks within the domain of Traditional Chinese Medicine (TCM). Our purpose is to observe the effect of the Tree-Organized Self-Reflective Retrieval (TOSRR) framework on LLMs in TCM Q&A tasks.
  Materials and Methods: We introduce the novel approach of knowledge organization, constructing a tree structure knowledge base with hierarchy. At inference time, our self-reflection framework retrieves from this knowledge base, integrating information across chapters. Questions from the TCM Medical Licensing Examination (MLE) and the college Classics Course Exam (CCE) were randomly selected as benchmark datasets.
  Results: By coupling with GPT-4, the framework can improve the best performance on the TCM MLE benchmark by 19.85% in absolute accuracy, and improve recall accuracy from 27% to 38% on CCE datasets. In manual evaluation, the framework improves a total of 18.52 points across dimensions of safety, consistency, explainability, compliance, and coherence.
  Conclusion: The TOSRR framework can effectively improve LLM's capability in Q&A tasks of TCM.

[Arxiv](https://arxiv.org/abs/2502.09156)