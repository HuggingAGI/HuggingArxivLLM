# 通过立场分离的多智能体辩论来检测突发事件中的谣言

发布时间：2024年12月06日

`Agent` `社交媒体` `谣言检测`

> Breaking Event Rumor Detection via Stance-Separated Multi-Agent Debate

# 摘要

> 在突发事件期间，社交媒体平台上谣言的快速蔓延严重阻碍了真相的传播。以往研究显示，注释资源的缺失阻碍了对未在昨日新闻中涵盖的意外突发事件的直接侦测。借助大型语言模型（LLMs）进行谣言检测前景广阔。但由于多样性有限，LLMs难以对复杂或有争议的问题给出全面回应。在本项工作中，我们提出了立场分离的多智能体辩论（S2MAD）来解决此问题。具体而言，我们先是引入立场分离，将评论划分为支持或反对原始主张两类。接着，把主张分为主观或客观，让智能体针对每种类型的主张采用不同的提示策略生成合理的初始观点。之后，辩论者依照特定指示通过多轮辩论达成共识。若无法达成共识，裁判智能体将评估各方意见并对主张的真实性作出最终裁决。在两个真实世界的数据集上开展的大量实验表明，我们所提出的模型在性能上优于现有最先进的方法，有效提升了LLMs在突发事件谣言检测中的表现。

> The rapid spread of rumors on social media platforms during breaking events severely hinders the dissemination of the truth. Previous studies reveal that the lack of annotated resources hinders the direct detection of unforeseen breaking events not covered in yesterday's news. Leveraging large language models (LLMs) for rumor detection holds significant promise. However, it is challenging for LLMs to provide comprehensive responses to complex or controversial issues due to limited diversity. In this work, we propose the Stance Separated Multi-Agent Debate (S2MAD) to address this issue. Specifically, we firstly introduce Stance Separation, categorizing comments as either supporting or opposing the original claim. Subsequently, claims are classified as subjective or objective, enabling agents to generate reasonable initial viewpoints with different prompt strategies for each type of claim. Debaters then follow specific instructions through multiple rounds of debate to reach a consensus. If a consensus is not reached, a judge agent evaluates the opinions and delivers a final verdict on the claim's veracity. Extensive experiments conducted on two real-world datasets demonstrate that our proposed model outperforms state-of-the-art methods in terms of performance and effectively improves the performance of LLMs in breaking event rumor detection.

[Arxiv](https://arxiv.org/abs/2412.04859)