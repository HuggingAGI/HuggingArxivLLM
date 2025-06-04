# INESC-ID @ eRisk 2025：探索微调、基于相似度及基于提示方法的抑郁症症状识别研究

发布时间：2025年06月03日

`LLM应用` `心理健康` `信息检索`

> INESC-ID @ eRisk 2025: Exploring Fine-Tuned, Similarity-Based, and Prompt-Based Approaches to Depression Symptom Identification

# 摘要

> 在eRisk 2025任务1中，我们的团队专注于抑郁症症状搜索。给定一组句子和贝克抑郁量表-II（BDI）问卷，参与者需为每个BDI症状提交最多1000个句子，并按相关性排序。评估采用平均精度（AP）和R-精度（R-PREC）等标准信息检索指标。然而，提供的训练数据仅标注了句子是否与BDI症状相关。基于此限制，我们将任务定位为针对每个BDI症状的二分类问题，并进行了相应的评估。我们划分了训练集和验证集，探索了基础模型微调、句子相似度、大语言模型（LLM）提示和集成方法。验证结果表明，微调基础模型表现最佳，特别是在加入合成数据缓解类别不平衡时效果更佳。我们还发现，不同症状的最佳方法各不相同。基于这些发现，我们设计了五个独立的测试运行，其中两个采用了集成方法。最终，我们在官方评估中取得了最高分，超越了其他16个团队。

> In this work, we describe our team's approach to eRisk's 2025 Task 1: Search for Symptoms of Depression. Given a set of sentences and the Beck's Depression Inventory - II (BDI) questionnaire, participants were tasked with submitting up to 1,000 sentences per depression symptom in the BDI, sorted by relevance. Participant submissions were evaluated according to standard Information Retrieval (IR) metrics, including Average Precision (AP) and R-Precision (R-PREC). The provided training data, however, consisted of sentences labeled as to whether a given sentence was relevant or not w.r.t. one of BDI's symptoms. Due to this labeling limitation, we framed our development as a binary classification task for each BDI symptom, and evaluated accordingly. To that end, we split the available labeled data into training and validation sets, and explored foundation model fine-tuning, sentence similarity, Large Language Model (LLM) prompting, and ensemble techniques. The validation results revealed that fine-tuning foundation models yielded the best performance, particularly when enhanced with synthetic data to mitigate class imbalance. We also observed that the optimal approach varied by symptom. Based on these insights, we devised five independent test runs, two of which used ensemble methods. These runs achieved the highest scores in the official IR evaluation, outperforming submissions from 16 other teams.

[Arxiv](https://arxiv.org/abs/2506.02924)