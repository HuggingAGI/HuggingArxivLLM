# SLearnLLM：实现大型语言模型高效领域适应的自学习框架

发布时间：2025年05月23日

`LLM应用

摘要中的论文讨论了如何优化大型语言模型的监督微调（SFT）过程，提出了一种自学习框架，通过识别和利用SFT数据集中的未知知识来提升训练效率。这属于LLM的应用层面研究，因为它探讨了如何在实际任务中更高效地应用和优化模型。因此，分类为LLM应用。`

> SLearnLLM: A Self-Learning Framework for Efficient Domain-Specific Adaptation of Large Language Models

# 摘要

> 在将大型语言模型（LLMs）通过监督微调（SFT）适应特定领域时，我们面临一个关键问题：是否需要使用整个SFT数据集进行微调？由于缺乏关于LLMs先前训练数据的详细信息，常规做法是直接对整个数据集进行微调。然而，如果SFT数据集与模型已掌握的知识有大量重叠，性能提升将十分有限，导致计算资源的浪费。识别并利用SFT数据集中未知的知识进行微调，可以显著提升训练效率。为此，我们提出了一种受人类学习模式启发的自学习框架。该框架以特定领域的SFT数据集为输入，通过三步流程优化模型性能：首先，LLMs回答数据集中的问题；其次，LLMs客观评估回答并筛选出错误的问答对；最后，基于筛选后的问答集进行微调。在农业和医学领域的实验表明，与完整数据集微调相比，我们的方法在大幅减少训练时间的同时，实现了相当的性能提升。通过专注于SFT数据集中的未知知识，我们的方法显著提升了LLMs微调的效率。

> When using supervised fine-tuning (SFT) to adapt large language models (LLMs) to specific domains, a significant challenge arises: should we use the entire SFT dataset for fine-tuning? Common practice often involves fine-tuning directly on the entire dataset due to limited information on the LLM's past training data. However, if the SFT dataset largely overlaps with the model's existing knowledge, the performance gains are minimal, leading to wasted computational resources. Identifying the unknown knowledge within the SFT dataset and using it to fine-tune the model could substantially improve the training efficiency. To address this challenge, we propose a self-learning framework for LLMs inspired by human learning pattern. This framework takes a fine-tuning (SFT) dataset in a specific domain as input. First, the LLMs answer the questions in the SFT dataset. The LLMs then objectively grade the responses and filter out the incorrectly answered QA pairs. Finally, we fine-tune the LLMs based on this filtered QA set. Experimental results in the fields of agriculture and medicine demonstrate that our method substantially reduces training time while achieving comparable improvements to those attained with full dataset fine-tuning. By concentrating on the unknown knowledge within the SFT dataset, our approach enhances the efficiency of fine-tuning LLMs.

[Arxiv](https://arxiv.org/abs/2505.17470)