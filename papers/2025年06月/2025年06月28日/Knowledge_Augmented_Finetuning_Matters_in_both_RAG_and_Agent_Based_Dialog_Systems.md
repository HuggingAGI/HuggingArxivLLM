# 知识增强微调在RAG与基于代理的对话系统中至关重要。

发布时间：2025年06月28日

`LLM应用` `对话系统` `客户服务`

> Knowledge Augmented Finetuning Matters in both RAG and Agent Based Dialog Systems

# 摘要

> 大型语言模型（LLMs）在对话系统中得到了广泛应用，尽管取得了一定进展，但它们在知识密集型场景中仍容易出错。最近，基于检索增强生成（RAG）和智能体的方法应运而生，通过增强LLMs使用外部知识库检索到的知识，来提高事实准确性。这主要通过向LLMs提供指令、示例和检索到的知识来实现。然而，LLMs在特定领域生成响应时可能难以有效利用检索到的知识，因为它们并未经过专门训练。为了解决这一问题，我们提出了一种名为知识增强微调（KAFT）的方法，在基于RAG和智能体的系统中，使用领域特定数据和外部知识对LLMs进行微调。我们的研究基于MobileCS2数据集，这是一个具有密集知识交互的真实客服对话数据集，用于系统比较基于RAG和智能体系统的提示技术和KAFT技术。实验结果表明，KAFT在RAG和智能体系统中均显著优于提示技术，尤其是在事实准确性方面。据我们所知，本文是首个实证研究KAFT理念的坚实工作。

> Large language models (LLMs) have recently been applied to dialog systems. Despite making progress, LLMs are prone to errors in knowledge-intensive scenarios. Recently, approaches based on retrieval augmented generation (RAG) and agent have emerged to improve the factual accuracy by enhancing the LLMs with knowledge retrieved from external knowledge bases (KBs). This is mostly implemented by prompting the LLMs with instructions, examples and the retrieved knowledge. However, LLMs may have difficulty using the retrieved knowledge effectively for response generation, because they are not well trained to do such generation for specific domains. To mitigate this problem, we propose to finetune the LLMs in the RAG-based and agent-based systems with domain-specific data, together with domain-specific external knowledge, which is called knowledge augmented finetuning (KAFT). We base our study on the MobileCS2 dataset, a real-life customer service dialog dataset that features intensive knowledge interactions, to systematically compare the prompting and KAFT techniques in the RAG-based and agent-based systems. Experiment results show that KAFT substantially surpasses prompting in both RAG and agent systems, particularly in terms of factual accuracy. To the best of our knowledge, this paper represents the first solid empirical work to investigate the KAFT idea.

[Arxiv](https://arxiv.org/abs/2506.22852)