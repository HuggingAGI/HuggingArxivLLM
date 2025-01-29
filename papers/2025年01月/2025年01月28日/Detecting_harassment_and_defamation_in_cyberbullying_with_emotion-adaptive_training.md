# 情感自适应训练助力网络欺凌中的骚扰与诽谤检测

发布时间：2025年01月28日

`LLM应用

理由：这篇论文主要讨论了在低资源环境下使用多种基于Transformer的模型（包括大型语言模型如Llama2和Llama3）进行网络欺凌检测的任务。虽然论文涉及了多种模型，但其核心应用场景是利用大型语言模型（LLM）来解决具体的实际问题（网络欺凌检测），并且提出了情感自适应训练框架（EAT）来提升模型性能。因此，这篇论文应归类为LLM应用。` `社交媒体` `网络欺凌检测`

> Detecting harassment and defamation in cyberbullying with emotion-adaptive training

# 摘要

> # 摘要
现有研究主要关注社交媒体上的网络欺凌检测，尤其是骚扰行为，通常将其视为二元分类任务。然而，网络欺凌形式多样，如诽谤和骚扰，名人尤其容易成为目标。此外，针对这些不同形式的训练数据仍然匮乏。本研究首先构建了一个包含骚扰和诽谤两种事件的名人网络欺凌数据集。我们在低资源环境下，测试了多种基于Transformer的模型，包括掩码（RoBERTa、Bert、DistilBert）、替换（Electra）、自回归（XLnet）、掩码&置换（Mpnet）、文本-文本（T5）以及大型语言模型（Llama2和Llama3）。结果显示，这些模型在显式骚扰的二元检测上表现优异，但在骚扰和诽谤的多分类任务上表现较差。为此，我们提出了情感自适应训练框架（EAT），通过将情感检测领域的知识迁移到网络欺凌检测领域，帮助识别间接网络欺凌事件。在低资源环境下，EAT在九种基于Transformer的模型中，将网络欺凌检测的平均宏F1、精确率和召回率提升了20%。我们的结论得到了理论分析和大量实验的支持。

> Existing research on detecting cyberbullying incidents on social media has primarily concentrated on harassment and is typically approached as a binary classification task. However, cyberbullying encompasses various forms, such as denigration and harassment, which celebrities frequently face. Furthermore, suitable training data for these diverse forms of cyberbullying remains scarce. In this study, we first develop a celebrity cyberbullying dataset that encompasses two distinct types of incidents: harassment and defamation. We investigate various types of transformer-based models, namely masked (RoBERTa, Bert and DistilBert), replacing(Electra), autoregressive (XLnet), masked&permuted (Mpnet), text-text (T5) and large language models (Llama2 and Llama3) under low source settings. We find that they perform competitively on explicit harassment binary detection. However, their performance is substantially lower on harassment and denigration multi-classification tasks. Therefore, we propose an emotion-adaptive training framework (EAT) that helps transfer knowledge from the domain of emotion detection to the domain of cyberbullying detection to help detect indirect cyberbullying events. EAT consistently improves the average macro F1, precision and recall by 20% in cyberbullying detection tasks across nine transformer-based models under low-resource settings. Our claims are supported by intuitive theoretical insights and extensive experiments.

[Arxiv](https://arxiv.org/abs/2501.16925)