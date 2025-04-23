# CiteFix：借助后处理引文修正提升RAG系统的准确性

发布时间：2025年04月22日

`RAG` `信息检索` `商业智能`

> CiteFix: Enhancing RAG Accuracy Through Post-Processing Citation Correction

# 摘要

> 检索增强生成（RAG）作为大型语言模型（LLMs）的强大应用，革新了信息检索与消费方式。RAG系统结合传统搜索能力与LLMs，为用户查询生成全面解答，理想情况下带有准确引用。然而，在我们开发RAG产品的过程中发现，LLMs在来源归属上常常表现欠佳，这一问题也得到了行业其他研究的印证，指出 popular generative search engines 的引用准确率仅为约74%。为解决这一问题，我们提出了一种高效的后处理算法，旨在提升LLM生成回答中的引用准确性，同时对延迟和成本的影响降至最低。我们的方法通过关键词+语义匹配、基于BERTScore的微调模型，以及一种轻量级的LLM技术，对生成引用与检索文章进行交叉核验。实验结果表明，该方法使RAG系统的整体准确性指标提升了15.46%。这一显著提升可能使我们从当前的大型语言模型转向一个相对较小但性能相当的模型，其成本效益提高了约12倍，推理速度提升了3倍。这项研究为提升信息检索和总结任务中AI生成内容的可靠性和可信度做出了贡献，这对于赢得客户信任，特别是在商业产品中，至关重要。


> Retrieval Augmented Generation (RAG) has emerged as a powerful application of Large Language Models (LLMs), revolutionizing information search and consumption. RAG systems combine traditional search capabilities with LLMs to generate comprehensive answers to user queries, ideally with accurate citations. However, in our experience of developing a RAG product, LLMs often struggle with source attribution, aligning with other industry studies reporting citation accuracy rates of only about 74% for popular generative search engines. To address this, we present efficient post-processing algorithms to improve citation accuracy in LLM-generated responses, with minimal impact on latency and cost. Our approaches cross-check generated citations against retrieved articles using methods including keyword + semantic matching, fine tuned model with BERTScore, and a lightweight LLM-based technique. Our experimental results demonstrate a relative improvement of 15.46% in the overall accuracy metrics of our RAG system. This significant enhancement potentially enables a shift from our current larger language model to a relatively smaller model that is approximately 12x more cost-effective and 3x faster in inference time, while maintaining comparable performance. This research contributes to enhancing the reliability and trustworthiness of AI-generated content in information retrieval and summarization tasks which is critical to gain customer trust especially in commercial products.

[Arxiv](https://arxiv.org/abs/2504.15629)