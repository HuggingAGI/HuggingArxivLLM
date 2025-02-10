# MedRAG：利用知识图谱引导的推理提升检索增强生成，助力医疗领域智能助手

发布时间：2025年02月06日

`RAG` `医疗信息处理`

> MedRAG: Enhancing Retrieval-augmented Generation with Knowledge Graph-Elicited Reasoning for Healthcare Copilot

# 摘要

> 检索增强生成（RAG）是一种非常适合用于处理隐私敏感的电子健康记录（EHR）的技术，可作为医疗协 pilot 的关键模块，帮助减少医疗从业者和患者的误诊。然而，现有基于启发式方法的 RAG 模型在医疗领域的诊断准确性和特异性不足，尤其是在处理具有相似症状的疾病时。本文提出了一种增强的 RAG 模型 MedRAG，该模型通过知识图谱（KG）引导的推理，在医疗领域根据症状检索诊断和治疗建议。MedRAG 系统性地构建了一个包含多种疾病关键诊断差异的四层分级诊断知识图谱。这些差异与从 EHR 数据库中检索到的类似 EHR 动态集成，并在大型语言模型中进行推理。这一过程不仅能够提供更准确和具体的决策支持，还能主动提供后续问题，从而增强个性化医疗决策。我们在公开数据集 DDXPlus 和从新加坡陈笃生医院收集的慢性疼痛诊断数据集（CPDD）上对 MedRAG 进行了评估，并将其性能与多种现有 RAG 方法进行了比较。实验结果表明，通过利用 KG 的信息整合和关联能力，我们的 MedRAG 提供了更具体的诊断见解，并在降低误诊率方面优于现有最先进的模型。我们的代码将在 https://github.com/SNOWTEAM2023/MedRAG 上公开。

> Retrieval-augmented generation (RAG) is a well-suited technique for retrieving privacy-sensitive Electronic Health Records (EHR). It can serve as a key module of the healthcare copilot, helping reduce misdiagnosis for healthcare practitioners and patients. However, the diagnostic accuracy and specificity of existing heuristic-based RAG models used in the medical domain are inadequate, particularly for diseases with similar manifestations. This paper proposes MedRAG, a RAG model enhanced by knowledge graph (KG)-elicited reasoning for the medical domain that retrieves diagnosis and treatment recommendations based on manifestations. MedRAG systematically constructs a comprehensive four-tier hierarchical diagnostic KG encompassing critical diagnostic differences of various diseases. These differences are dynamically integrated with similar EHRs retrieved from an EHR database, and reasoned within a large language model. This process enables more accurate and specific decision support, while also proactively providing follow-up questions to enhance personalized medical decision-making. MedRAG is evaluated on both a public dataset DDXPlus and a private chronic pain diagnostic dataset (CPDD) collected from Tan Tock Seng Hospital, and its performance is compared against various existing RAG methods. Experimental results show that, leveraging the information integration and relational abilities of the KG, our MedRAG provides more specific diagnostic insights and outperforms state-of-the-art models in reducing misdiagnosis rates. Our code will be available at https://github.com/SNOWTEAM2023/MedRAG

[Arxiv](https://arxiv.org/abs/2502.04413)