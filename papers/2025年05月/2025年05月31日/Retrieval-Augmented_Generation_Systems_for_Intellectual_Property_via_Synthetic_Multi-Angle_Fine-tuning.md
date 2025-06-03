# # 面向知识产权的检索增强生成系统借助合成多角度微调技术

发布时间：2025年05月31日

`RAG` `知识产权` `问答系统`

> Retrieval-Augmented Generation Systems for Intellectual Property via Synthetic Multi-Angle Fine-tuning

# 摘要

> 在知识产权领域，检索增强生成（RAG）系统常因用户多样化查询（如口语化表达、拼写错误和模糊术语）而导致检索不准确和响应效果不佳。针对这一问题，我们提出了多角度问题生成与检索微调方法（MQG-RFM），这是一种基于大型语言模型（LLMs）的新型框架，通过模拟多样化用户查询并微调检索模型，使其适应语义等价但语言多样的问题。与复杂架构修改不同，MQG-RFM采用轻量级的Data-to-Tune范式，结合提示工程化的查询生成与硬负样本挖掘，无需昂贵的基础设施更改即可显著增强检索鲁棒性。实验结果表明，在台湾专利问答数据集上，MQG-RFM的检索准确率和生成质量均显著优于基准方法（专利咨询数据集分别提升185.62%和14.22%，新颖专利技术报告数据集分别提升262.26%和53.58%）。通过语义感知的检索优化，MQG-RFM弥合了用户意图与系统理解之间的差距，为寻求可靠专利情报解决方案的小型和中型机构提供了一种实用且可扩展的快速、低成本部署方法。此外，该方法已被中国最大的专业研究社交网络平台ScholarMate采用，支持现实世界中的开发和部署。该方法的演示版本可在GitHub上获取。

> Retrieval-Augmented Generation (RAG) systems in the Intellectual Property (IP) field often struggle with diverse user queries, including colloquial expressions, spelling errors, and ambiguous terminology, leading to inaccurate retrieval and suboptimal responses. To address this challenge, we propose Multi-Angle Question Generation and Retrieval Fine-Tuning Method (MQG-RFM), a novel framework that leverages large language models (LLMs) to simulate varied user inquiries and fine-tunes retrieval models to align semantically equivalent but linguistically diverse questions. Unlike complex architectural modifications, MQG-RFM adopts a lightweight Data-to-Tune paradigm, combining prompt-engineered query generation with hard negative mining to enhance retrieval robustness without costly infrastructure changes. Experimental results on a Taiwan patent Q&A dataset show 185.62% improvement in retrieval accuracy on the Patent Consultation dataset and 262.26% improvement on the Novel Patent Technology Report dataset, with 14.22% and 53.58% improvements in generation quality over the baselines, respectively. By bridging the gap between user intent and system comprehension through semantic-aware retrieval optimization, MQG-RFM offers a practical, scalable approach for rapid, cost-effective deployment among small and medium-sized agencies seeking reliable patent intelligence solutions. Additionally, our proposed method has already been adopted by ScholarMate, the largest professional research social networking platform in China, to support real-world development and deployment. A demo version of the instantiated is available at https://github.com/renruntao/patent_rag.

[Arxiv](https://arxiv.org/abs/2506.00527)