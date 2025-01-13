# CognoSpeak：通过真实对话语音自动远程评估早期认知衰退

发布时间：2025年01月10日

`Agent

理由：这篇论文介绍了CognoSpeak，一个通过虚拟代理进行认知评估的系统。虚拟代理在这里扮演了关键角色，负责提出记忆探测问题、执行认知任务以及收集多模态数据。因此，这篇论文主要涉及Agent（代理）的应用，特别是虚拟代理在医疗领域的应用。` `认知评估`

> CognoSpeak: an automatic, remote assessment of early cognitive decline in real-world conversational speech

# 摘要

> 认知衰退的早期迹象往往在对话中显现，识别这些迹象对于应对神经退行性疾病的后期阶段至关重要。尽管临床检测成本高且耗时，且基于语音的自动检测系统虽有所进展，但这些系统通常训练于小规模数据库，缺乏详细的元数据和人口统计信息。本文介绍了CognoSpeak及其数据收集工作。CognoSpeak通过移动或网络平台上的虚拟代理，提出记忆探测问题，并执行语言流畅性、语义流畅性和图片描述等标准认知任务。此外，它还收集了音频、视频等多模态数据，以及来自初级和二级护理、记忆诊所和家庭等远程环境的丰富元数据。我们展示了126名受试者的手动转录音频结果，并评估了多种经典分类器和基于大型语言模型的分类器在不同提示下的表现。结果显示，使用DistilBERT模型在记忆反应、流畅性任务和“饼干盗窃”图片描述任务中，CognoSpeak能够有效区分认知障碍患者与健康志愿者，F1分数达到0.873。CognoSpeak提供了一种自动、远程、低成本、可重复、非侵入性且压力较小的替代现有临床认知评估的方法。

> The early signs of cognitive decline are often noticeable in conversational speech, and identifying those signs is crucial in dealing with later and more serious stages of neurodegenerative diseases. Clinical detection is costly and time-consuming and although there has been recent progress in the automatic detection of speech-based cues, those systems are trained on relatively small databases, lacking detailed metadata and demographic information. This paper presents CognoSpeak and its associated data collection efforts. CognoSpeak asks memory-probing long and short-term questions and administers standard cognitive tasks such as verbal and semantic fluency and picture description using a virtual agent on a mobile or web platform. In addition, it collects multimodal data such as audio and video along with a rich set of metadata from primary and secondary care, memory clinics and remote settings like people's homes. Here, we present results from 126 subjects whose audio was manually transcribed. Several classic classifiers, as well as large language model-based classifiers, have been investigated and evaluated across the different types of prompts. We demonstrate a high level of performance; in particular, we achieved an F1-score of 0.873 using a DistilBERT model to discriminate people with cognitive impairment (dementia and people with mild cognitive impairment (MCI)) from healthy volunteers using the memory responses, fluency tasks and cookie theft picture description. CognoSpeak is an automatic, remote, low-cost, repeatable, non-invasive and less stressful alternative to existing clinical cognitive assessments.

[Arxiv](https://arxiv.org/abs/2501.05755)