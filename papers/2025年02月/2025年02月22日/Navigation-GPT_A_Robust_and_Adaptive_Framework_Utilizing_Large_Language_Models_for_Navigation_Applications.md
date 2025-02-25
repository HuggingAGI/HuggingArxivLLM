# Navigation-GPT：一个利用大型语言模型的稳健且自适应导航应用框架

发布时间：2025年02月22日

`LLM应用` `船舶导航` `避碰规则`

> Navigation-GPT: A Robust and Adaptive Framework Utilizing Large Language Models for Navigation Applications

# 摘要

> 现有导航决策支持系统在处理非预定义场景时表现欠佳。本研究提出了一种基于大型语言模型（LLM）的双核框架，旨在解决这一难题。首先，通过基于ReAct的提示工程，较大的LLM核心将复杂导航任务分解为可管理的子任务，并自主调用外部工具收集相关信息，利用反馈降低LLM幻觉风险。随后，一个经过微调且紧凑的LLM核心，如同经验丰富的船员，被设计用于处理此类信息和非结构化数据，生成情境感知建议，最终提供符合《国际海上避碰规则》（COLREGs）的瞭望见解和导航提示。大量实验表明，该框架不仅在传统船舶避碰任务中表现出色，还能有效适应非结构化、非预定义和不可预测的场景。与DeepSeek-R1、GPT-4o等先进模型的比较分析进一步验证了该框架的有效性和合理性。本研究成功连接传统导航系统与LLM，为提升各类导航应用的安全性和效率提供了创新解决方案。


> Existing navigation decision support systems often perform poorly when handling non-predefined navigation scenarios. Leveraging the generalization capabilities of large language model (LLM) in handling unknown scenarios, this research proposes a dual-core framework for LLM applications to address this issue. Firstly, through ReAct-based prompt engineering, a larger LLM core decomposes intricate navigation tasks into manageable sub-tasks, which autonomously invoke corresponding external tools to gather relevant information, using this feedback to mitigate the risk of LLM hallucinations. Subsequently, a fine-tuned and compact LLM core, acting like a first-mate is designed to process such information and unstructured external data, then to generates context-aware recommendations, ultimately delivering lookout insights and navigation hints that adhere to the International Regulations for Preventing Collisions at Sea (COLREGs) and other rules. Extensive experiments demonstrate the proposed framework not only excels in traditional ship collision avoidance tasks but also adapts effectively to unstructured, non-predefined, and unpredictable scenarios. A comparative analysis with DeepSeek-R1, GPT-4o and other SOTA models highlights the efficacy and rationality of the proposed framework. This research bridges the gap between conventional navigation systems and LLMs, offering a framework to enhance safety and operational efficiency across diverse navigation applications.

[Arxiv](https://arxiv.org/abs/2502.16402)