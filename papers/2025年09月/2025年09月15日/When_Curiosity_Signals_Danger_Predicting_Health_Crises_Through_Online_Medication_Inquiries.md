# 当好奇暗藏危机：从在线药物查询预测健康风险

发布时间：2025年09月15日

`LLM应用` `医疗健康`

> When Curiosity Signals Danger: Predicting Health Crises Through Online Medication Inquiries

# 摘要

> 在线医疗论坛蕴含着丰富的患者关切信息，却尚未被充分挖掘利用——尤其是在药物使用相关问题上。用户提出的诸多疑问中，有些可能暗示着用药困惑、误用，甚至是潜在健康危机的早期信号。因此，及时识别这些可能预示严重不良事件或危及生命并发症的关键问题，对提升患者安全、实现精准干预至关重要。本研究构建了一个全新标注数据集，收录了从在线论坛提取的药物相关提问，每个条目均依据临床风险因素手动标注其关键性。我们以TF-IDF文本表示为基础，对六种传统机器学习分类器进行了性能基准测试，同时评估了三种基于大型语言模型（LLM）的先进分类方法——这些方法能借助深度语境理解能力。研究结果表明，无论是经典算法还是现代技术，都有望为数字健康领域的实时分诊与警报系统提供有力支持。该数据集已公开分享，旨在推动患者生成数据、自然语言处理与关键健康事件预警系统交叉领域的深入研究。数据集及基准测试详情可访问：https://github.com/Dvora-coder/LLM-Medication-QA-Risk-Classifier-MediGuard。

> Online medical forums are a rich and underutilized source of insight into patient concerns, especially regarding medication use. Some of the many questions users pose may signal confusion, misuse, or even the early warning signs of a developing health crisis. Detecting these critical questions that may precede severe adverse events or life-threatening complications is vital for timely intervention and improving patient safety. This study introduces a novel annotated dataset of medication-related questions extracted from online forums. Each entry is manually labelled for criticality based on clinical risk factors. We benchmark the performance of six traditional machine learning classifiers using TF-IDF textual representations, alongside three state-of-the-art large language model (LLM)-based classification approaches that leverage deep contextual understanding. Our results highlight the potential of classical and modern methods to support real-time triage and alert systems in digital health spaces. The curated dataset is made publicly available to encourage further research at the intersection of patient-generated data, natural language processing, and early warning systems for critical health events. The dataset and benchmark are available at: https://github.com/Dvora-coder/LLM-Medication-QA-Risk-Classifier-MediGuard.

[Arxiv](https://arxiv.org/abs/2509.11802)