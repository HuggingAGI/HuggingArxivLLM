# 利用大型语言模型从应用商店用户评论中挖掘需求

发布时间：2024年09月23日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来自动化地获取移动应用的用户需求，通过分析用户评论来提取需求。这属于LLM在实际应用中的使用，因此分类为LLM应用。` `移动应用` `需求分析`

> Exploring Requirements Elicitation from App Store User Reviews Using Large Language Models

# 摘要

> 移动应用已成为我们日常生活的必备工具，覆盖了从通信、娱乐到医疗、金融等各个领域，影响深远。然而，开发出真正满足用户需求的应用程序仍是一大挑战。传统的需求获取方法，如用户访谈，不仅耗时，还容易受限于范围和主观性。为此，我们提出了一种基于大型语言模型（LLMs）的自动化需求获取方法，通过分析用户评论来提取需求。我们在一个标注了有用性的应用评论数据集上微调了BERT、DistilBERT和GEMMA三个LLMs。评估结果显示，BERT表现最佳，准确率和F1分数分别达到92.40%和92.39%，证明了其在精准分类有用评论上的强大能力。尽管GEMMA整体表现稍逊，但其召回率高达93.39%，显示出其在捕捉全面用户见解方面的潜力。这些结果表明，LLMs为移动应用开发中的需求获取提供了一条高效路径，有助于打造更贴近用户需求、更成功的应用程序。

> Mobile applications have become indispensable companions in our daily lives. Spanning over the categories from communication and entertainment to healthcare and finance, these applications have been influential in every aspect. Despite their omnipresence, developing apps that meet user needs and expectations still remains a challenge. Traditional requirements elicitation methods like user interviews can be time-consuming and suffer from limited scope and subjectivity. This research introduces an approach leveraging the power of Large Language Models (LLMs) to analyze user reviews for automated requirements elicitation. We fine-tuned three well-established LLMs BERT, DistilBERT, and GEMMA, on a dataset of app reviews labeled for usefulness. Our evaluation revealed BERT's superior performance, achieving an accuracy of 92.40% and an F1-score of 92.39%, demonstrating its effectiveness in accurately classifying useful reviews. While GEMMA displayed a lower overall performance, it excelled in recall (93.39%), indicating its potential for capturing a comprehensive set of valuable user insights. These findings suggest that LLMs offer a promising avenue for streamlining requirements elicitation in mobile app development, leading to the creation of more user-centric and successful applications.

[Arxiv](https://arxiv.org/abs/2409.15473)