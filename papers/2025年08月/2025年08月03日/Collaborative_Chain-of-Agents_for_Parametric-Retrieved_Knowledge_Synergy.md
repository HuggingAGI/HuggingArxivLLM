# 协作代理链实现参数检索的知识协同

发布时间：2025年08月03日

`RAG` `问答系统` `知识管理`

> Collaborative Chain-of-Agents for Parametric-Retrieved Knowledge Synergy

# 摘要

> 检索增强生成（RAG）作为一种有前景的框架，旨在提升大型语言模型（LLMs）的能力，尤其在知识密集型任务中表现突出。尽管具备诸多优势，当前的RAG方法在生成过程中往往难以*充分挖掘知识潜力*。特别是，模型内部的参数化知识与外部检索到的知识之间的协同作用仍然有限。检索到的内容有时可能误导生成过程，而某些生成内容则能够引导模型输出更精确的结果。针对这一问题，本研究提出了一种名为Collaborative Chain-of-Agents的框架，旨在增强对参数化知识和检索知识的协同利用。具体而言，我们首先引入了CoCoA-zero，这是一种多智能体RAG框架，它首先执行条件知识归纳，然后进行推理以生成答案。在此基础上，我们进一步开发了CoCoA，这是一种长链训练策略，通过整合CoCoA-zero中的多智能体推理轨迹，对LLM进行微调。该策略提升了模型在显式整合和协同利用参数化与检索知识方面的能力。实验结果显示，CoCoA-zero和CoCoA在开放领域和多跳问答任务中表现优异。

> Retrieval-Augmented Generation (RAG) has emerged as a promising framework for enhancing the capabilities of Large Language Models (LLMs), especially in knowledge-intensive tasks. Despite its advantages, current RAG methods often struggle to *fully exploit knowledge during generation*. In particular, the synergy between the model's internal parametric knowledge and external retrieved knowledge remains limited. Retrieved contents may sometimes mislead generation, while certain generated content can guide the model toward more accurate outputs. In this work, we propose Collaborative Chain-of-Agents, a framework designed to enhance explicitly synergy over both parametric and retrieved knowledge. Specifically, we first introduce CoCoA-zero, a multi-agent RAG framework that first performs conditional knowledge induction and then reasons answers. Building on this, we develop CoCoA, a long-chain training strategy that synthesizes extended multi-agent reasoning trajectories from CoCoA-zero to fine-tune the LLM. This strategy enhances the model's capability to explicitly integrate and jointly leverage parametric and retrieved knowledge. Experiments results show that CoCoA-zero and CoCoA achieve superior performance on open-domain and multi-hop QA tasks.

[Arxiv](https://arxiv.org/abs/2508.01696)