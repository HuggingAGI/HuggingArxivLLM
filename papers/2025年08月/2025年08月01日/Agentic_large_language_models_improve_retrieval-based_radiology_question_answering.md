# 智能体大型语言模型提升基于检索的放射科问答性能
智能体大型语言模型在医学问答中的应用，尤其是在基于检索的放射科问题回答方面，展现出了显著的优势。通过多轮对话和动态调整检索策略，他们成功提升了回答的准确性和相关性。

发布时间：2025年08月01日

`Agent` `放射科` `人工智能`

> Agentic large language models improve retrieval-based radiology question answering

# 摘要

> 放射科的临床决策在AI，特别是大型语言模型（LLMs）的帮助下取得了显著进展。然而，传统的放射科问答RAG系统通常依赖单步检索，这限制了它们处理复杂临床推理任务的能力。我们提出了一种代理式RAG框架，使LLMs能够自主分解放射科问题，逐步从Radiopaedia中检索目标临床证据，并动态合成基于证据的回答。我们评估了24个LLMs，涵盖不同的架构、参数规模（0.5B到>670B）和训练范式（通用型、推理优化型、临床微调型），使用了来自先前建立的RSNA-RadioQA和ExtendedQA数据集的104个专家精选放射科问题。与零样本提示（73% vs. 64%；P<0.001）和传统在线RAG（73% vs. 68%；P<0.001）相比，代理式检索显著提高了诊断准确率。中型模型（如Mistral Large从72%提升到81%）和小型模型（如Qwen 2.5-7B从55%提升到71%）取得了最大的改进，而非常大的模型（>200B参数）仅表现出微小变化（<2%提升）。此外，代理式检索减少了幻觉（平均9.4%），并在46%的情况下检索到临床相关背景，大大增强了事实依据。即使是经过临床微调的模型也表现出显著改进（如MedGemma-27B从71%提升到81%），表明检索和微调的互补作用。这些结果突显了代理式框架在提高放射科问答的事实性和诊断准确性方面的潜力，特别是在中型LLMs中，未来的研究需要进一步验证其临床实用性。

> Clinical decision-making in radiology increasingly benefits from artificial intelligence (AI), particularly through large language models (LLMs). However, traditional retrieval-augmented generation (RAG) systems for radiology question answering (QA) typically rely on single-step retrieval, limiting their ability to handle complex clinical reasoning tasks. Here we propose an agentic RAG framework enabling LLMs to autonomously decompose radiology questions, iteratively retrieve targeted clinical evidence from Radiopaedia, and dynamically synthesize evidence-based responses. We evaluated 24 LLMs spanning diverse architectures, parameter scales (0.5B to >670B), and training paradigms (general-purpose, reasoning-optimized, clinically fine-tuned), using 104 expert-curated radiology questions from previously established RSNA-RadioQA and ExtendedQA datasets. Agentic retrieval significantly improved mean diagnostic accuracy over zero-shot prompting (73% vs. 64%; P<0.001) and conventional online RAG (73% vs. 68%; P<0.001). The greatest gains occurred in mid-sized models (e.g., Mistral Large improved from 72% to 81%) and small-scale models (e.g., Qwen 2.5-7B improved from 55% to 71%), while very large models (>200B parameters) demonstrated minimal changes (<2% improvement). Additionally, agentic retrieval reduced hallucinations (mean 9.4%) and retrieved clinically relevant context in 46% of cases, substantially aiding factual grounding. Even clinically fine-tuned models exhibited meaningful improvements (e.g., MedGemma-27B improved from 71% to 81%), indicating complementary roles of retrieval and fine-tuning. These results highlight the potential of agentic frameworks to enhance factuality and diagnostic accuracy in radiology QA, particularly among mid-sized LLMs, warranting future studies to validate their clinical utility.

[Arxiv](https://arxiv.org/abs/2508.00743)