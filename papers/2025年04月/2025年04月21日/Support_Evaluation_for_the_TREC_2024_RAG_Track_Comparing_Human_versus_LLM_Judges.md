# # 支持评估：对比 TREC 2024 RAG 赛道中的人类与 LLM 评委表现

发布时间：2025年04月21日

`RAG` `信息检索`

> Support Evaluation for the TREC 2024 RAG Track: Comparing Human versus LLM Judges

# 摘要

> 检索增强生成（RAG）让大型语言模型（LLMs）能够从包含“真实信息”的源文档中生成带引用的答案，从而有效减少系统幻觉。在RAG评估中，“支持”是一个关键考量点，即引用文档中的信息是否能有效支持答案。为此，我们对TREC 2024 RAG Track的36个主题进行了大规模比较研究，比较了自动LLM评委（GPT-4o）与人工评委在支持评估方面的表现。我们设置了两种评估条件：（1）从零开始的完全人工评估，以及（2）基于LLM预测进行后编辑的人工评估。研究结果显示，在56%的从零开始的完全人工评估中，人工评委与GPT-4o的预测完全一致（基于三个等级的评分标准），而在基于LLM预测进行后编辑的人工评估中，这一比例提升至72%。此外，通过仔细分析无偏见研究中的分歧，我们发现，独立的人工评委与GPT-4o的相关性比人工评委更好，这表明LLM评委可以成为支持评估的可靠替代方案。最后，我们对人工评委和GPT-4o的错误进行了定性分析，以帮助指导未来支持评估的改进。

> Retrieval-augmented generation (RAG) enables large language models (LLMs) to generate answers with citations from source documents containing "ground truth", thereby reducing system hallucinations. A crucial factor in RAG evaluation is "support", whether the information in the cited documents supports the answer. To this end, we conducted a large-scale comparative study of 45 participant submissions on 36 topics to the TREC 2024 RAG Track, comparing an automatic LLM judge (GPT-4o) against human judges for support assessment. We considered two conditions: (1) fully manual assessments from scratch and (2) manual assessments with post-editing of LLM predictions. Our results indicate that for 56% of the manual from-scratch assessments, human and GPT-4o predictions match perfectly (on a three-level scale), increasing to 72% in the manual with post-editing condition. Furthermore, by carefully analyzing the disagreements in an unbiased study, we found that an independent human judge correlates better with GPT-4o than a human judge, suggesting that LLM judges can be a reliable alternative for support assessment. To conclude, we provide a qualitative analysis of human and GPT-4o errors to help guide future iterations of support assessment.

[Arxiv](https://arxiv.org/abs/2504.15205)