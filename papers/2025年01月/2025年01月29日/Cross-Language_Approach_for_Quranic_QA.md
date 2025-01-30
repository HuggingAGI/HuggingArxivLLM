# 古兰经问答的跨语言方法

发布时间：2025年01月29日

`LLM应用

理由：这篇论文主要讨论了如何通过跨语言策略和预训练语言模型的微调来提升古兰经问答系统的性能。虽然涉及了多种预训练模型（如BERT、RoBERTa、DeBERTa等），但核心关注点是如何将这些模型应用于特定的问答任务，特别是针对资源匮乏的语言环境。因此，这篇论文属于LLM应用类别。`

> Cross-Language Approach for Quranic QA

# 摘要

> # 摘要
问答系统在资源匮乏的语言中面临严峻挑战，开发稳健模型尤为困难。古兰经问答系统因其能帮助全球超过十亿人深入理解古兰经而显得尤为重要。然而，这些系统面临独特挑战：现代标准阿拉伯语问题与古典阿拉伯语古兰经答案之间的语言差异，以及数据集规模小，限制了模型性能。为此，我们采用跨语言策略：（1）数据集增强：通过机器翻译将阿拉伯语问题转为英语，改写问题以增加语言多样性，并从古兰经英译中检索答案，满足多语言训练需求；（2）语言模型微调：使用BERT-Medium、RoBERTa-Base、DeBERTa-v3-Base、ELECTRA-Large、Flan-T5、Bloom和Falcon等预训练模型，满足古兰经问答的特定需求。实验结果显示，跨语言方法显著提升了模型性能，RoBERTa-Base在MAP@10（0.34）和MRR（0.52）上表现最佳，DeBERTa-v3-Base在Recall@10（0.50）和Precision@10（0.24）上表现优异。这些发现证明了跨语言策略在克服语言障碍和提升古兰经问答系统方面的有效性。

> Question answering systems face critical limitations in languages with limited resources and scarce data, making the development of robust models especially challenging. The Quranic QA system holds significant importance as it facilitates a deeper understanding of the Quran, a Holy text for over a billion people worldwide. However, these systems face unique challenges, including the linguistic disparity between questions written in Modern Standard Arabic and answers found in Quranic verses written in Classical Arabic, and the small size of existing datasets, which further restricts model performance. To address these challenges, we adopt a cross-language approach by (1) Dataset Augmentation: expanding and enriching the dataset through machine translation to convert Arabic questions into English, paraphrasing questions to create linguistic diversity, and retrieving answers from an English translation of the Quran to align with multilingual training requirements; and (2) Language Model Fine-Tuning: utilizing pre-trained models such as BERT-Medium, RoBERTa-Base, DeBERTa-v3-Base, ELECTRA-Large, Flan-T5, Bloom, and Falcon to address the specific requirements of Quranic QA. Experimental results demonstrate that this cross-language approach significantly improves model performance, with RoBERTa-Base achieving the highest MAP@10 (0.34) and MRR (0.52), while DeBERTa-v3-Base excels in Recall@10 (0.50) and Precision@10 (0.24). These findings underscore the effectiveness of cross-language strategies in overcoming linguistic barriers and advancing Quranic QA systems

[Arxiv](https://arxiv.org/abs/2501.17449)