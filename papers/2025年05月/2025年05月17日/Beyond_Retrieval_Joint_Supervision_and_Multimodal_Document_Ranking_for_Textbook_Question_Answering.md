# # 超越检索：教材问答中的联合监督与多模态文档排序
大型语言模型（LLMs）的最新进展推动了一场革命性的转变，从传统的机器人流程自动化升级到智能体流程自动化，这一转变通过基于LLMs自动化工作流编排过程得以实现。

发布时间：2025年05月17日

`LLM应用` `问答系统`

> Beyond Retrieval: Joint Supervision and Multimodal Document Ranking for Textbook Question Answering

# 摘要

> 教科书问答（TQA）是一项复杂的任务，需要对复杂的多模态上下文进行解读。尽管 recent advances 在整体性能上有所提升，但在教育场景中，它们常常面临困难，因为这些场景需要准确的语义对齐和特定任务的文档检索。本文中，我们提出了一种通过多目标联合训练机制增强语义表示的新型多模态教科书问答方法。我们的模型，基于检索器-生成器架构的联合嵌入训练带有排名监督的教科书问答（JETRTQA），是一个多模态学习框架，采用检索增强生成的设置，其中多模态大型语言模型生成答案。JETRTQA旨在提高在复杂教育环境中检索到的文档的相关性。与传统的直接评分方法不同，JETRTQA通过结合成对排名和从答案中获得的隐式监督信号的监督信号，学习如何优化问题和文档的语义表示。我们在CK12-QA数据集上评估了我们的方法，并证明它显著提高了对信息丰富和不相关文档的辨别能力，即使这些文档是长的、复杂的和多模态的。JETRTQA超越了之前的最先进方法，在验证集上准确率提高了2.4%，在测试集上提高了11.1%。

> Textbook question answering (TQA) is a complex task, requiring the interpretation of complex multimodal context. Although recent advances have improved overall performance, they often encounter difficulties in educational settings where accurate semantic alignment and task-specific document retrieval are essential. In this paper, we propose a novel approach to multimodal textbook question answering by introducing a mechanism for enhancing semantic representations through multi-objective joint training. Our model, Joint Embedding Training With Ranking Supervision for Textbook Question Answering (JETRTQA), is a multimodal learning framework built on a retriever--generator architecture that uses a retrieval-augmented generation setup, in which a multimodal large language model generates answers. JETRTQA is designed to improve the relevance of retrieved documents in complex educational contexts. Unlike traditional direct scoring approaches, JETRTQA learns to refine the semantic representations of questions and documents through a supervised signal that combines pairwise ranking and implicit supervision derived from answers. We evaluate our method on the CK12-QA dataset and demonstrate that it significantly improves the discrimination between informative and irrelevant documents, even when they are long, complex, and multimodal. JETRTQA outperforms the previous state of the art, achieving a 2.4\% gain in accuracy on the validation set and 11.1\% on the test set.

[Arxiv](https://arxiv.org/abs/2505.13520)