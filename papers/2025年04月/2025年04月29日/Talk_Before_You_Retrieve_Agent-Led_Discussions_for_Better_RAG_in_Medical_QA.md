# 先聊后查：智能体引导对话优化医疗问答中的RAG技术

发布时间：2025年04月29日

`RAG` `问答系统`

> Talk Before You Retrieve: Agent-Led Discussions for Better RAG in Medical QA

# 摘要

> 医学问答（QA）是一项推理密集型任务，大型语言模型（LLMs）因幻觉现象和过时的专业知识仍面临挑战。检索增强生成（RAG）通过利用外部知识提供了一种有前景的后训练解决方案。然而，现有医学RAG系统存在两个关键问题：缺乏对信息检索过程中类人推理行为的建模，以及依赖次优医学语料库，导致检索结果常出现不相关或噪声片段。为解决这些问题，我们提出了Discuss-RAG，这是一个即插即用模块，旨在通过协作代理推理增强医学QA的RAG系统。我们的方法引入了总结器代理，协调医学专家团队模拟多轮头脑风暴，提升检索内容相关性。此外，决策代理在最终集成前评估检索片段。实验结果显示，在四个基准医学QA数据集上，Discuss-RAG表现优于MedRAG，尤其在BioASQ和PubMedQA上，答案准确性分别提升了16.67%和12.20%。代码可在GitHub上获取：https://github.com/LLM-VLM-GSL/Discuss-RAG.

> Medical question answering (QA) is a reasoning-intensive task that remains challenging for large language models (LLMs) due to hallucinations and outdated domain knowledge. Retrieval-Augmented Generation (RAG) provides a promising post-training solution by leveraging external knowledge. However, existing medical RAG systems suffer from two key limitations: (1) a lack of modeling for human-like reasoning behaviors during information retrieval, and (2) reliance on suboptimal medical corpora, which often results in the retrieval of irrelevant or noisy snippets. To overcome these challenges, we propose Discuss-RAG, a plug-and-play module designed to enhance the medical QA RAG system through collaborative agent-based reasoning. Our method introduces a summarizer agent that orchestrates a team of medical experts to emulate multi-turn brainstorming, thereby improving the relevance of retrieved content. Additionally, a decision-making agent evaluates the retrieved snippets before their final integration. Experimental results on four benchmark medical QA datasets show that Discuss-RAG consistently outperforms MedRAG, especially significantly improving answer accuracy by up to 16.67% on BioASQ and 12.20% on PubMedQA. The code is available at: https://github.com/LLM-VLM-GSL/Discuss-RAG.

[Arxiv](https://arxiv.org/abs/2504.21252)