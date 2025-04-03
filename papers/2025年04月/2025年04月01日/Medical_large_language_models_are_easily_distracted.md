# 医疗大语言模型易受干扰

发布时间：2025年04月01日

`LLM应用` `医学考试`

> Medical large language models are easily distracted

# 摘要

> 大型语言模型（LLMs）有望彻底改变医学领域，但真实临床场景中的冗余信息可能会影响其表现。辅助技术如环境语音记录系统能从实时医患互动中自动生成草稿笔记，可能引入额外噪声，因此评估LLMs过滤相关数据的能力至关重要。为此，我们开发了MedDistractQA，这是一个嵌入模拟真实世界干扰的美国医师执照考试（USMLE）风格问题的基准测试。研究发现，干扰性陈述（即在非临床语境中使用具有临床意义的多义词，或提及不相关的健康状况）可使LLMs的准确率降低多达17.9%。旨在提高模型性能的常见解决方案，如检索增强生成（RAG）和医学领域微调，并未改变这一影响，某些情况下甚至引入了新的干扰因素，进一步降低了性能。研究结果表明，LLMs天生缺乏区分相关与不相关临床信息所需的逻辑机制，这对实际应用提出了挑战。MedDistractQA及其研究结果强调了开发强大缓解策略以增强LLMs抵御冗余信息能力的必要性。


> Large language models (LLMs) have the potential to transform medicine, but real-world clinical scenarios contain extraneous information that can hinder performance. The rise of assistive technologies like ambient dictation, which automatically generates draft notes from live patient encounters, has the potential to introduce additional noise making it crucial to assess the ability of LLM's to filter relevant data. To investigate this, we developed MedDistractQA, a benchmark using USMLE-style questions embedded with simulated real-world distractions. Our findings show that distracting statements (polysemous words with clinical meanings used in a non-clinical context or references to unrelated health conditions) can reduce LLM accuracy by up to 17.9%. Commonly proposed solutions to improve model performance such as retrieval-augmented generation (RAG) and medical fine-tuning did not change this effect and in some cases introduced their own confounders and further degraded performance. Our findings suggest that LLMs natively lack the logical mechanisms necessary to distinguish relevant from irrelevant clinical information, posing challenges for real-world applications. MedDistractQA and our results highlights the need for robust mitigation strategies to enhance LLM resilience to extraneous information.

[Arxiv](https://arxiv.org/abs/2504.01201)