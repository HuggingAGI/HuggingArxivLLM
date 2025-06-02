# MedPAIR：评估医疗问答中医生与AI的相关性一致性

发布时间：2025年05月29日

`LLM应用` `问答系统`

> MedPAIR: Measuring Physicians and AI Relevance Alignment in Medical Question Answering

# 摘要

> 大型语言模型（LLMs）在医学问答（QA）基准测试中表现出色，包括标准化医学考试。但正确答案并不等同于正确逻辑，模型可能通过错误推理得出准确结论。为研究这一问题，我们推出了MedPAIR数据集，评估医生学员与LLMs在回答QA问题时如何筛选关键信息。我们从36名医生学员处获取了1,300个QA对的标注，对问题组件中的每个句子进行了相关性标注。通过对比分析，我们发现LLMs与医生学员在信息筛选上的差异显著。有趣的是，移除非相关句子后，医生学员和LLMs的准确率均有所提升。所有相关数据均可访问：http://medpair.csail.mit.edu/。

> Large Language Models (LLMs) have demonstrated remarkable performance on various medical question-answering (QA) benchmarks, including standardized medical exams. However, correct answers alone do not ensure correct logic, and models may reach accurate conclusions through flawed processes. In this study, we introduce the MedPAIR (Medical Dataset Comparing Physicians and AI Relevance Estimation and Question Answering) dataset to evaluate how physician trainees and LLMs prioritize relevant information when answering QA questions. We obtain annotations on 1,300 QA pairs from 36 physician trainees, labeling each sentence within the question components for relevance. We compare these relevance estimates to those for LLMs, and further evaluate the impact of these "relevant" subsets on downstream task performance for both physician trainees and LLMs. We find that LLMs are frequently not aligned with the content relevance estimates of physician trainees. After filtering out physician trainee-labeled irrelevant sentences, accuracy improves for both the trainees and the LLMs. All LLM and physician trainee-labeled data are available at: http://medpair.csail.mit.edu/.

[Arxiv](https://arxiv.org/abs/2505.24040)