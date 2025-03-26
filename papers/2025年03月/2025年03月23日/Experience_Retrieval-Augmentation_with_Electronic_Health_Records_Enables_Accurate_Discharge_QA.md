# 利用电子健康记录的经验检索增强实现精准出院问答

发布时间：2025年03月23日

`RAG` `临床应用`

> Experience Retrieval-Augmentation with Electronic Health Records Enables Accurate Discharge QA

# 摘要

> 为了提升大型语言模型在临床应用中的可靠性，检索增强生成（RAG）被广泛应用以提供事实性的医学知识。然而，除了来自开放数据集的一般医学知识外，临床案例为基础的知识对于有效的医学推理也至关重要，因为它提供了基于真实患者体验的背景。基于此，我们提出了基于电子健康记录（EHR）的体验检索增强框架——ExpRAG，旨在从其他患者的出院报告中提供相关背景。ExpRAG通过粗到细的过程进行检索，首先使用基于EHR的报告排名器高效识别相似患者，然后利用体验检索器提取与任务相关的内容以增强医学推理。为了评估ExpRAG，我们引入了DischargeQA，这是一个临床问答数据集，包含1,280个与出院相关的诊断、用药和指导任务问题。每个问题均基于EHR数据生成，以确保现实且具挑战性的场景。实验结果表明，ExpRAG在与文本排名器的对比中始终表现更优，平均相对提升达5.2%，突显了案例知识对医学推理的重要性。

> To improve the reliability of Large Language Models (LLMs) in clinical applications, retrieval-augmented generation (RAG) is extensively applied to provide factual medical knowledge. However, beyond general medical knowledge from open-ended datasets, clinical case-based knowledge is also critical for effective medical reasoning, as it provides context grounded in real-world patient experiences. Motivated by this, we propose Experience Retrieval Augmentation - ExpRAG framework based on Electronic Health Record (EHR), aiming to offer the relevant context from other patients' discharge reports. ExpRAG performs retrieval through a coarse-to-fine process, utilizing an EHR-based report ranker to efficiently identify similar patients, followed by an experience retriever to extract task-relevant content for enhanced medical reasoning. To evaluate ExpRAG, we introduce DischargeQA, a clinical QA dataset with 1,280 discharge-related questions across diagnosis, medication, and instruction tasks. Each problem is generated using EHR data to ensure realistic and challenging scenarios. Experimental results demonstrate that ExpRAG consistently outperforms a text-based ranker, achieving an average relative improvement of 5.2%, highlighting the importance of case-based knowledge for medical reasoning.

[Arxiv](https://arxiv.org/abs/2503.17933)