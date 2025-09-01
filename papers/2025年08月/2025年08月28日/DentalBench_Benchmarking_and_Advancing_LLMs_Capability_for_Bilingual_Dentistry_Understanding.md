# DentalBench：大型语言模型（LLMs）双语牙科理解能力的基准构建与提升

发布时间：2025年08月28日

`LLM应用` `医疗健康`

> DentalBench: Benchmarking and Advancing LLMs Capability for Bilingual Dentistry Understanding

# 摘要

> 大型语言模型（LLMs）与医疗专用LLM（Med-LLMs）的最新进展已在通用医疗基准测试中展现出优异性能，然而在牙科等需深度领域知识的专业医疗领域，因缺乏针对性评估资源，其能力研究仍显不足。为此，我们提出DentalBench——首个全面的双语基准，旨在评估并推动牙科领域LLM的发展。该基准包含两大核心组件：DentalQA（中英文问答基准，含36,597个问题，覆盖4项任务及16个牙科子领域）与DentalCorpus（大规模高质量语料库，3.3735亿token，专为牙科领域适配打造，支持有监督微调（SFT）与检索增强生成（RAG））。我们对14个LLM（涵盖专有、开源及医疗专用模型）的评估显示，模型在任务类型与语言上存在显著性能差异。进一步通过Qwen-2.5-3B实验证实，领域适配可大幅提升模型性能，尤其在知识密集型和术语密集型任务中；同时也凸显了领域特定基准对开发医疗健康专属可靠高效LLM的关键意义。

> Recent advances in large language models (LLMs) and medical LLMs (Med-LLMs) have demonstrated strong performance on general medical benchmarks. However, their capabilities in specialized medical fields, such as dentistry which require deeper domain-specific knowledge, remain underexplored due to the lack of targeted evaluation resources. In this paper, we introduce DentalBench, the first comprehensive bilingual benchmark designed to evaluate and advance LLMs in the dental domain. DentalBench consists of two main components: DentalQA, an English-Chinese question-answering (QA) benchmark with 36,597 questions spanning 4 tasks and 16 dental subfields; and DentalCorpus, a large-scale, high-quality corpus with 337.35 million tokens curated for dental domain adaptation, supporting both supervised fine-tuning (SFT) and retrieval-augmented generation (RAG). We evaluate 14 LLMs, covering proprietary, open-source, and medical-specific models, and reveal significant performance gaps across task types and languages. Further experiments with Qwen-2.5-3B demonstrate that domain adaptation substantially improves model performance, particularly on knowledge-intensive and terminology-focused tasks, and highlight the importance of domain-specific benchmarks for developing trustworthy and effective LLMs tailored to healthcare applications.

[Arxiv](https://arxiv.org/abs/2508.20416)