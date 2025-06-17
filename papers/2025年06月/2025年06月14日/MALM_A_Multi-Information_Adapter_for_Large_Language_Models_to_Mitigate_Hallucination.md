# # MALM：缓解大型语言模型幻觉的多信息适配器

发布时间：2025年06月14日

`LLM理论` `人工智能` `知识图谱`

> MALM: A Multi-Information Adapter for Large Language Models to Mitigate Hallucination

# 摘要

> 大型语言模型（LLMs）容易出现三种幻觉：输入冲突型、上下文冲突型和事实冲突型。本研究旨在通过揭示这三类幻觉之间的相互关联，提出一种名为多信息适配器（MALM）的解决方案。该框架采用多图学习方法，深入分析原始输入、上下文信息与外部事实知识之间的联系，从而在一个统一的框架内有效缓解幻觉问题。实验在HaluEval、TruthfulQA、Natural Questions 和 TriviaQA四个数据集上进行，结果表明：(1) MALM在7种典型LLMs上均表现出显著优势，尤其在LLaMA-2的基础上实现了性能提升；(2) MALM与三种主流检索器（BM25、Spider 和 DPR）结合后，展现出良好的泛化能力。通过GPT-4和人工志愿者的双重评估，79.4%和65.6%的案例中，MALM的表现更受青睐。这表明，通过多层图注意力网络整合三种幻觉的复杂交互关系，能够有效提升LLM的生成质量。此外，MALM的适配器设计在不同基础模型上均展现出良好的灵活性和稳定性。

> Large language models (LLMs) are prone to three types of hallucination: Input-Conflicting, Context-Conflicting and Fact-Conflicting hallucinations. The purpose of this study is to mitigate the different types of hallucination by exploiting the interdependence between them. For this purpose, we propose a Multi-Information Adapter for Large Language Models (MALM). This framework employs a tailored multi-graph learning approach designed to elucidate the interconnections between original inputs, contextual information, and external factual knowledge, thereby alleviating the three categories of hallucination within a cohesive framework. Experiments were carried out on four benchmarking datasets: HaluEval, TruthfulQA, Natural Questions, and TriviaQA. We evaluated the proposed framework in two aspects: (1) adaptability to different base LLMs on HaluEval and TruthfulQA, to confirm if MALM is effective when applied on 7 typical LLMs. MALM showed significant improvements over LLaMA-2; (2) generalizability to retrieval-augmented generation (RAG) by combining MALM with three representative retrievers (BM25, Spider and DPR) separately. Furthermore, automated and human evaluations were conducted to substantiate the correctness of experimental results, where GPT-4 and 3 human volunteers judged which response was better between LLaMA-2 and MALM. The results showed that both GPT-4 and human preferred MALM in 79.4% and 65.6% of cases respectively. The results validate that incorporating the complex interactions between the three types of hallucination through a multilayered graph attention network into the LLM generation process is effective to mitigate the them. The adapter design of the proposed approach is also proven flexible and robust across different base LLMs.

[Arxiv](https://arxiv.org/abs/2506.12483)