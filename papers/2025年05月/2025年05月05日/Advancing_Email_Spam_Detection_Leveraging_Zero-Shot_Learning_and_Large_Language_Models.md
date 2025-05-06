# 提升邮件垃圾检测：借助零样本学习与大型语言模型

发布时间：2025年05月05日

`LLM应用

理由：这篇论文将大型语言模型（如BERT和FLAN-T5）应用于电子邮件垃圾检测任务，属于LLM的应用层面。` `信息安全`

> Advancing Email Spam Detection: Leveraging Zero-Shot Learning and Large Language Models

# 摘要

> 电子邮件垃圾检测是现代通信系统中的重要任务，对保障生产力、安全性和用户体验至关重要。传统机器学习和深度学习方法虽然有效，但在应对垃圾邮件策略演变、类别不平衡和数据稀缺性方面存在明显局限。为解决这些问题，本研究提出了一种创新方法，结合零样本学习（Zero-Shot Learning）与FLAN-T5，以及BERT等先进自然语言处理（NLP）技术，用于电子邮件垃圾检测。通过BERT预处理和提取电子邮件内容中的关键信息，并利用FLAN-T5在零样本框架下进行分类，本研究旨在突破传统垃圾检测系统的限制。FLAN-T5与BERT的结合使垃圾检测无需依赖大量标注数据集或频繁重新训练，从而能够灵活应对未知垃圾邮件模式和对抗环境。本研究展示了零样本学习与NLP技术在垃圾检测中的巨大潜力，为应对垃圾检测任务的动态性和复杂性提供了重要见解。

> Email spam detection is a critical task in modern communication systems, essential for maintaining productivity, security, and user experience. Traditional machine learning and deep learning approaches, while effective in static settings, face significant limitations in adapting to evolving spam tactics, addressing class imbalance, and managing data scarcity. These challenges necessitate innovative approaches that reduce dependency on extensive labeled datasets and frequent retraining. This study investigates the effectiveness of Zero-Shot Learning using FLAN-T5, combined with advanced Natural Language Processing (NLP) techniques such as BERT for email spam detection. By employing BERT to preprocess and extract critical information from email content, and FLAN-T5 to classify emails in a Zero-Shot framework, the proposed approach aims to address the limitations of traditional spam detection systems. The integration of FLAN-T5 and BERT enables robust spam detection without relying on extensive labeled datasets or frequent retraining, making it highly adaptable to unseen spam patterns and adversarial environments. This research highlights the potential of leveraging zero-shot learning and NLPs for scalable and efficient spam detection, providing insights into their capability to address the dynamic and challenging nature of spam detection tasks.

[Arxiv](https://arxiv.org/abs/2505.02362)