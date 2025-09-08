# 基于自然语言处理（NLP）的医院分诊数据中运动相关损伤分类

发布时间：2025年09月05日

`LLM应用` `医疗健康`

> Classification of kinetic-related injury in hospital triage data using NLP

# 摘要

> 分诊记录是患者入院就诊时首份创建的医疗文书，蕴含丰富信息，可助力医护人员和研究人员掌握急诊科患者的流行病学特征，以及疾病或损伤的时效性严重程度。然而，将现代自然语言处理与机器学习技术应用于分诊数据分析时，却面临着不少难题：其一，医院数据包含高度敏感信息，受隐私法规严格管控，因此必须在本地进行分析；其二，多数医院及医疗机构缺乏微调大型语言模型（LLM）的硬件条件，更遑论从头训练；其三，为筛选出目标记录，需依赖专家手动标注数据集，耗时且成本高昂。本文提出了一种流程，能在有限计算资源下利用LLM实现分诊数据分类。具体而言，首先在GPU上，利用一个小型（2k样本）开源数据集，通过分类器对预训练LLM进行微调；随后在CPU上，使用包含1000个样本的医院特定数据集对模型进一步微调。研究表明，通过精心整理数据集，并充分利用现有模型与开源数据，可在有限计算资源下成功完成分诊数据分类任务。

> Triage notes, created at the start of a patient's hospital visit, contain a wealth of information that can help medical staff and researchers understand Emergency Department patient epidemiology and the degree of time-dependent illness or injury. Unfortunately, applying modern Natural Language Processing and Machine Learning techniques to analyse triage data faces some challenges: Firstly, hospital data contains highly sensitive information that is subject to privacy regulation thus need to be analysed on site; Secondly, most hospitals and medical facilities lack the necessary hardware to fine-tune a Large Language Model (LLM), much less training one from scratch; Lastly, to identify the records of interest, expert inputs are needed to manually label the datasets, which can be time-consuming and costly. We present in this paper a pipeline that enables the classification of triage data using LLM and limited compute resources. We first fine-tuned a pre-trained LLM with a classifier using a small (2k) open sourced dataset on a GPU; and then further fine-tuned the model with a hospital specific dataset of 1000 samples on a CPU. We demonstrated that by carefully curating the datasets and leveraging existing models and open sourced data, we can successfully classify triage data with limited compute resources.

[Arxiv](https://arxiv.org/abs/2509.04969)