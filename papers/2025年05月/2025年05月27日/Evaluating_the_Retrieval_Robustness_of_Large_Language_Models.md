# 评估大型语言模型的检索鲁棒性

发布时间：2025年05月27日

`RAG` `问答系统`

> Evaluating the Retrieval Robustness of Large Language Models

# 摘要

> 检索增强生成（RAG）通常能提升大型语言模型（LLMs）处理知识密集型任务的能力。然而，RAG也可能引发性能下降，原因在于检索的不完善以及模型在利用检索内容方面的局限性。本研究旨在评估LLMs在实际RAG场景下的稳健性（以下简称检索稳健性）。我们重点关注三个研究问题：（1）RAG是否始终优于非RAG方法；（2）检索到的文档数量越多是否一定带来更好的性能；（3）文档的顺序是否会影响结果。为了支持这项研究，我们建立了一个包含1500个开放领域问题的基准测试集，每个问题都配有从维基百科检索的相关文档。我们引入了三个稳健性评估指标，每个指标对应一个研究问题。通过涉及11种LLMs和3种提示策略的全面实验，我们发现所有这些模型都展现出了令人惊讶的高检索稳健性；然而，不同程度的不完善稳健性阻碍了它们充分挖掘RAG的潜力。

> Retrieval-augmented generation (RAG) generally enhances large language models' (LLMs) ability to solve knowledge-intensive tasks. But RAG may also lead to performance degradation due to imperfect retrieval and the model's limited ability to leverage retrieved content. In this work, we evaluate the robustness of LLMs in practical RAG setups (henceforth retrieval robustness). We focus on three research questions: (1) whether RAG is always better than non-RAG; (2) whether more retrieved documents always lead to better performance; (3) and whether document orders impact results. To facilitate this study, we establish a benchmark of 1500 open-domain questions, each with retrieved documents from Wikipedia. We introduce three robustness metrics, each corresponds to one research question. Our comprehensive experiments, involving 11 LLMs and 3 prompting strategies, reveal that all of these LLMs exhibit surprisingly high retrieval robustness; nonetheless, different degrees of imperfect robustness hinders them from fully utilizing the benefits of RAG.

[Arxiv](https://arxiv.org/abs/2505.21870)