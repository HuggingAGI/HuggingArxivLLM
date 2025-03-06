# COSINT智能体：知识驱动的中文开源情报多模态智能体

发布时间：2025年03月05日

`Agent` `开源情报` `情报分析`

> COSINT-Agent: A Knowledge-Driven Multimodal Agent for Chinese Open Source Intelligence

# 摘要

> 开源情报（OSINT）的实现需要整合多模态数据并进行推理，从非结构化数据源中提取可操作的情报这一过程充满挑战。传统方法，包括多模态大型语言模型（MLLMs），往往难以准确推断复杂的上下文关系或提供全面的情报。本文提出了一种专为中文领域OSINT挑战设计的知识驱动型多模态智能体——COSINT-Agent。该智能体将微调后的MLLMs的感知能力与实体-事件-场景知识图谱（EES-KG）的结构化推理能力完美结合。COSINT-Agent的核心是创新的EES-Match框架，它连接了COSINT-MLLM和EES-KG，实现了多模态见解的系统化提取、推理和情境化。这种整合使COSINT-Agent能够精准识别实体、解释事件并检索上下文，从而将原始多模态数据转化为可操作的情报。通过大量实验验证，COSINT-Agent在实体识别、EES生成和上下文匹配等核心OSINT任务中表现出色，充分展现了其作为强大且可扩展解决方案的潜力，不仅推动了多模态推理的自动化，还显著提升了OSINT方法的有效性。

> Open Source Intelligence (OSINT) requires the integration and reasoning of diverse multimodal data, presenting significant challenges in deriving actionable insights. Traditional approaches, including multimodal large language models (MLLMs), often struggle to infer complex contextual relationships or deliver comprehensive intelligence from unstructured data sources. In this paper, we introduce COSINT-Agent, a knowledge-driven multimodal agent tailored to address the challenges of OSINT in the Chinese domain. COSINT-Agent seamlessly integrates the perceptual capabilities of fine-tuned MLLMs with the structured reasoning power of the Entity-Event-Scene Knowledge Graph (EES-KG). Central to COSINT-Agent is the innovative EES-Match framework, which bridges COSINT-MLLM and EES-KG, enabling systematic extraction, reasoning, and contextualization of multimodal insights. This integration facilitates precise entity recognition, event interpretation, and context retrieval, effectively transforming raw multimodal data into actionable intelligence. Extensive experiments validate the superior performance of COSINT-Agent across core OSINT tasks, including entity recognition, EES generation, and context matching. These results underscore its potential as a robust and scalable solution for advancing automated multimodal reasoning and enhancing the effectiveness of OSINT methodologies.

[Arxiv](https://arxiv.org/abs/2503.03215)