# 提升肝病临床试验效率：一个安全、基于大型语言模型的预筛选流程

发布时间：2025年02月24日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLM）在临床试验患者筛选中的应用。虽然提到了智能体协作，但其核心是将LLM应用于实际问题，解决临床试验中的患者筛选问题。` `临床试验`

> Enhancing Hepatopathy Clinical Trial Efficiency: A Secure, Large Language Model-Powered Pre-Screening Pipeline

# 摘要

> # 背景  
在招募涉及复杂肝病（如肝细胞癌和肝硬化）的患者队列时，通常需要解读语义复杂的入选标准。传统的手动筛选方法耗时且容易出错。虽然AI驱动的预筛选提供了潜在的解决方案，但在准确性、效率和数据隐私方面仍存在挑战。  

# 方法  
我们开发了一种新型患者预筛选流水线，利用临床专业知识指导大型语言模型的精准、安全和高效应用。该流水线将复杂标准分解为一系列复合问题，然后采用两种策略通过电子健康记录进行语义问答：(1) 路径A，基于人类化专家的思路链策略；(2) 路径B，基于智能体协作的预设立场策略，特别是在处理复杂临床推理场景时。该流水线从问题和标准两个层面，依据三个关键指标进行评估：精准度、耗时和反事实推理。  

# 结果  
我们的流水线实现了高精准度（0.921，准则层面）和高效率（每任务0.44秒）。路径B在复杂推理方面表现尤为出色，而路径A在精准数据提取方面表现出色，且处理速度更快。两条路径的精准度相当。该流水线在肝细胞癌试验（0.878）和肝硬化试验（0.843）中均展现出良好效果。  

# 结论  
本研究提出的数据安全且高效的患者筛选流水线在肝病临床试验中展现出高精准度，为简化临床试验工作流程提供了有前景的解决方案。其高效性和适应性使其适合提升患者招募效率，而其在资源有限环境下的适用性进一步增强了其在临床场景中的实用性。

> Background: Recruitment for cohorts involving complex liver diseases, such as hepatocellular carcinoma and liver cirrhosis, often requires interpreting semantically complex criteria. Traditional manual screening methods are time-consuming and prone to errors. While AI-powered pre-screening offers potential solutions, challenges remain regarding accuracy, efficiency, and data privacy. Methods: We developed a novel patient pre-screening pipeline that leverages clinical expertise to guide the precise, safe, and efficient application of large language models. The pipeline breaks down complex criteria into a series of composite questions and then employs two strategies to perform semantic question-answering through electronic health records - (1) Pathway A, Anthropomorphized Experts' Chain of Thought strategy, and (2) Pathway B, Preset Stances within an Agent Collaboration strategy, particularly in managing complex clinical reasoning scenarios. The pipeline is evaluated on three key metrics-precision, time consumption, and counterfactual inference - at both the question and criterion levels. Results: Our pipeline achieved high precision (0.921, in criteria level) and efficiency (0.44s per task). Pathway B excelled in complex reasoning, while Pathway A was effective in precise data extraction with faster processing times. Both pathways achieved comparable precision. The pipeline showed promising results in hepatocellular carcinoma (0.878) and cirrhosis trials (0.843). Conclusions: This data-secure and time-efficient pipeline shows high precision in hepatopathy trials, providing promising solutions for streamlining clinical trial workflows. Its efficiency and adaptability make it suitable for improving patient recruitment. And its capability to function in resource-constrained environments further enhances its utility in clinical settings.

[Arxiv](https://arxiv.org/abs/2502.18531)