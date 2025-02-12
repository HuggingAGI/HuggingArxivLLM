# 通过自我选择优化检索增强生成中的知识整合

发布时间：2025年02月09日

`RAG` `问答系统`

> Optimizing Knowledge Integration in Retrieval-Augmented Generation with Self-Selection

# 摘要

> 检索增强生成（RAG）通过将外部知识整合到大型语言模型（LLMs）中，已被证明能有效提升LLMs生成更准确可靠回答的能力。然而，如何有效融合外部检索知识与LLMs内部参数知识仍是一项重大挑战。本研究提出了一种新颖的自选式RAG框架，使LLMs能够从仅基于内部参数知识生成的回答与结合外部检索知识生成的回答中进行选择，从而提升回答的准确性。为此，我们设计了一种自选式-RGP方法，通过在经过筛选的检索生成偏好（RGP）数据集上对LLMs进行直接偏好优化（DPO）训练，来增强LLMs在生成和选择正确答案方面的能力。实验结果表明，使用两个开源LLMs（即Llama2-13B-Chat和Mistral-7B）在自然问答（NQ）和简单问答（TrivialQA）数据集上的测试，我们的方法相较于其他基线方法具有明显优势。

> Retrieval-Augmented Generation (RAG), which integrates external knowledge into Large Language Models (LLMs), has proven effective in enabling LLMs to produce more accurate and reliable responses. However, it remains a significant challenge how to effectively integrate external retrieved knowledge with internal parametric knowledge in LLMs. In this work, we propose a novel Self-Selection RAG framework, where the LLM is made to select from pairwise responses generated with internal parametric knowledge solely and with external retrieved knowledge together to achieve enhanced accuracy. To this end, we devise a Self-Selection-RGP method to enhance the capabilities of the LLM in both generating and selecting the correct answer, by training the LLM with Direct Preference Optimization (DPO) over a curated Retrieval Generation Preference (RGP) dataset. Experimental results with two open-source LLMs (i.e., Llama2-13B-Chat and Mistral-7B) well demonstrate the superiority of our approach over other baseline methods on Natural Questions (NQ) and TrivialQA datasets.

[Arxiv](https://arxiv.org/abs/2502.06148)