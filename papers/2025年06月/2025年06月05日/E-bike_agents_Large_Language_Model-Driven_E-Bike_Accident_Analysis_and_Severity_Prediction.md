# 电动自行车事故分析与严重性预测研究：基于大型语言模型的电动自行车代理

发布时间：2025年06月05日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLM）在处理非结构化数据和提取安全变量方面的应用。虽然提到了“agent”，但这些agent是基于LLM的，核心在于LLM的应用，特别是在交通领域的特定应用中。因此，这篇论文应归类为LLM应用。` `数据分析`

> E-bike agents: Large Language Model-Driven E-Bike Accident Analysis and Severity Prediction

# 摘要

> 电动自行车（e-bikes）的使用量激增，随之而来的是事故报告的增加，引发了人们对安全性的担忧。然而，现有的e-bike事故报告多以非结构化叙述形式呈现，这为定量安全分析带来了挑战。本研究提出了一种名为E-bike agents的框架，该框架利用大型语言模型（LLM）驱动的代理，从非结构化事故报告中分类和提取安全变量。我们的框架由四个LLM代理构成，分别负责数据分类、信息提取、受伤原因确定和组件链接，以识别可能导致电动自行车事故并影响其严重程度的关键因素。此外，我们采用有序logit模型，深入分析了事故严重程度与提取出的因素（包括性别、原因类型及环境条件）之间的关系。研究发现，设备问题略多于人为因素，但后者更常导致致命事故。具体而言，踏板、轮胎和刹车是常见的事故诱因。模型在分类准确率上达到了0.87的高加权F1分数，彰显了在特定领域（如交通）中使用LLMs提取非结构化数据的潜力。我们的方法不仅为提升电动自行车安全分析提供了可扩展的解决方案，更为政策制定者、设计者和监管机构提供了切实可行的参考信息。

> Electric bicycles (e-bikes) are rapidly increasing in use, raising safety concerns due to a rise in accident reports. However, e-bike incident reports often use unstructured narrative formats, which hinders quantitative safety analysis. This study introduces E-bike agents, a framework that uses large language models (LLM) powered agents to classify and extract safety variables from unstructured incident reports. Our framework consists of four LLM agents, handling data classification, information extraction, injury cause determination, and component linkage, to extract the key factors that could lead to E-bike accidents and cause varying severity levels. Furthermore, we used an ordered logit model to examine the relationship between the severity of the incident and the factors retrieved, such as gender, the type of cause, and environmental conditions. Our research shows that equipment issues are slightly more common than human-related ones, but human-related incidents are more often fatal. Specifically, pedals, tires, and brakes are frequent contributors to accidents. The model achieves a high weighted F1 score of 0.87 in classification accuracy, highlighting the potential of using LLMs to extract unstructured data in niche domains, such as transportation. Our method offers a scalable solution to improve e-bike safety analytics and provides actionable information for policy makers, designers, and regulators.

[Arxiv](https://arxiv.org/abs/2506.04654)