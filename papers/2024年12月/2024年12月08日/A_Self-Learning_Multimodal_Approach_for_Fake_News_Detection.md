# 一种用于检测假新闻的自学习多模态手段

发布时间：2024年12月08日

`LLM应用` `社交媒体` `新闻检测`

> A Self-Learning Multimodal Approach for Fake News Detection

# 摘要

> 社交媒体的迅猛发展致使在线新闻内容激增，从而让误导或虚假信息的传播大幅增多。尽管机器学习技术已广泛用于假新闻检测，可有标签数据集的匮乏仍是重大难题。错误信息往往以文本和图像成对的形式出现，比如一则新闻文章或标题搭配相关的视觉内容。在本文中，我们推出了一个用于假新闻分类的自学习多模态模型。该模型借助对比学习这一无需有标签数据就能进行特征提取的有力手段，并融合了大型语言模型（LLMs）的长处，共同对文本和图像特征加以分析。LLMs 之所以擅长此项任务，是因为它们能够处理从大量训练语料库中获取的各类语言数据。我们在一个公共数据集上的实验结果显示，所提出的模型胜过若干前沿的分类方法，准确率、精度、召回率和 F1 分数都超过 85％。这些发现彰显了该模型在应对多模态假新闻检测挑战时的有效性。

> The rapid growth of social media has resulted in an explosion of online news content, leading to a significant increase in the spread of misleading or false information. While machine learning techniques have been widely applied to detect fake news, the scarcity of labeled datasets remains a critical challenge. Misinformation frequently appears as paired text and images, where a news article or headline is accompanied by a related visuals. In this paper, we introduce a self-learning multimodal model for fake news classification. The model leverages contrastive learning, a robust method for feature extraction that operates without requiring labeled data, and integrates the strengths of Large Language Models (LLMs) to jointly analyze both text and image features. LLMs are excel at this task due to their ability to process diverse linguistic data drawn from extensive training corpora. Our experimental results on a public dataset demonstrate that the proposed model outperforms several state-of-the-art classification approaches, achieving over 85% accuracy, precision, recall, and F1-score. These findings highlight the model's effectiveness in tackling the challenges of multimodal fake news detection.

[Arxiv](https://arxiv.org/abs/2412.05843)