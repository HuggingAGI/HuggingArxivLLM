# Multi-OphthaLingua：一个用于评估和消除中低收入国家 LLM 眼科问答偏差的多语言基准

发布时间：2024年12月18日

`LLM应用`

> Multi-OphthaLingua: A Multilingual Benchmark for Assessing and Debiasing LLM Ophthalmological QA in LMICs

# 摘要

> 当下的眼科临床工作流程被过度转诊、漫长等待以及繁杂且异构的医疗记录所困扰。大型语言模型（LLMs）为诸如分诊、视力评估之类的初步测试以及报告总结等各类程序的自动化带来了希望。然而，LLMs 在自然语言问答任务中于不同语言间的表现差异显著，可能会加大中低收入国家（LMICs）的医疗保健差距。本研究推出了首个多语言眼科问答基准，其中包含人工精心策划的跨语言平行问题，能够进行直接的跨语言比较。我们对 7 种不同语言的 6 个热门 LLMs 的评估显示出不同语言之间存在巨大偏差，凸显了在 LMICs 中临床部署 LLMs 的风险。现有的去偏方法，像翻译思维链或检索增强生成（RAG），本身难以缩小这种性能差距，往往无法提升所有语言的性能，而且在医疗领域缺乏针对性。为应对此问题，我们提出了 CLARA（跨语言反思智能体系统），这是一种创新的推理时去偏方法，借助检索增强生成和自我验证。我们的方法不但提升了所有语言的性能，还大幅缩小了多语言偏差差距，推动了全球范围内公平的 LLM 应用。

> Current ophthalmology clinical workflows are plagued by over-referrals, long waits, and complex and heterogeneous medical records. Large language models (LLMs) present a promising solution to automate various procedures such as triaging, preliminary tests like visual acuity assessment, and report summaries. However, LLMs have demonstrated significantly varied performance across different languages in natural language question-answering tasks, potentially exacerbating healthcare disparities in Low and Middle-Income Countries (LMICs). This study introduces the first multilingual ophthalmological question-answering benchmark with manually curated questions parallel across languages, allowing for direct cross-lingual comparisons. Our evaluation of 6 popular LLMs across 7 different languages reveals substantial bias across different languages, highlighting risks for clinical deployment of LLMs in LMICs. Existing debiasing methods such as Translation Chain-of-Thought or Retrieval-augmented generation (RAG) by themselves fall short of closing this performance gap, often failing to improve performance across all languages and lacking specificity for the medical domain. To address this issue, We propose CLARA (Cross-Lingual Reflective Agentic system), a novel inference time de-biasing method leveraging retrieval augmented generation and self-verification. Our approach not only improves performance across all languages but also significantly reduces the multilingual bias gap, facilitating equitable LLM application across the globe.

[Arxiv](https://arxiv.org/abs/2412.14304)