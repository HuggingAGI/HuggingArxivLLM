# 使用RoBERTa和DeBERTa的日语情感分类性能评估

发布时间：2025年04月22日

`LLM应用` `情感检测`

> Performance Evaluation of Emotion Classification in Japanese Using RoBERTa and DeBERTa

# 摘要

> # 背景
社交媒体监控和客户反馈分析等实际应用需要对日语文本进行准确的情感检测，然而资源匮乏和类别不平衡问题限制了模型性能。
# 目标
本研究旨在构建一个高精度模型，用于预测日语句子中八种普拉切克情绪的存在与否。
# 方法
我们使用WRIME语料库，将读者平均强度评分转换为二分类标签，并对四个预训练语言模型（BERT、RoBERTa、DeBERTa-v3-base、DeBERTa-v3-large）进行微调。为了对比，我们还评估了两个大型语言模型（TinySwallow-1.5B-Instruct 和 ChatGPT-4o）。采用准确率和F1值作为评估指标。
# 结果
DeBERTa-v3-large在平均准确率（0.860）和F1值（0.662）方面表现最佳，优于所有其他模型。它在高频情绪（如Joy、Anticipation）和低频情绪（如Anger、Trust）上均保持了稳健的F1值。大型语言模型的表现较弱，ChatGPT-4o和TinySwallow-1.5B-Instruct的平均F1值分别为0.527和0.292。
# 结论
微调后的DeBERTa-v3-large模型目前是日语二分类情感分类的最可靠解决方案。我们将其发布为可pip安装的包（pip install deberta-emotion-predictor）。未来工作应致力于增加稀有情绪的数据、减小模型规模，并探索提示工程以提升大型语言模型的性能。
本文正在接受《新世代计算》杂志的审稿，以期发表。


> Background Practical applications such as social media monitoring and customer-feedback analysis require accurate emotion detection for Japanese text, yet resource scarcity and class imbalance hinder model performance.
  Objective This study aims to build a high-accuracy model for predicting the presence or absence of eight Plutchik emotions in Japanese sentences.
  Methods Using the WRIME corpus, we transform reader-averaged intensity scores into binary labels and fine-tune four pre-trained language models (BERT, RoBERTa, DeBERTa-v3-base, DeBERTa-v3-large). For context, we also assess two large language models (TinySwallow-1.5B-Instruct and ChatGPT-4o). Accuracy and F1-score serve as evaluation metrics.
  Results DeBERTa-v3-large attains the best mean accuracy (0.860) and F1-score (0.662), outperforming all other models. It maintains robust F1 across both high-frequency emotions (e.g., Joy, Anticipation) and low-frequency emotions (e.g., Anger, Trust). The LLMs lag, with ChatGPT-4o and TinySwallow-1.5B-Instruct scoring 0.527 and 0.292 in mean F1, respectively.
  Conclusion The fine-tuned DeBERTa-v3-large model currently offers the most reliable solution for binary emotion classification in Japanese. We release this model as a pip-installable package (pip install deberta-emotion-predictor). Future work should augment data for rare emotions, reduce model size, and explore prompt engineering to improve LLM performance.
  This manuscript is under review for possible publication in New Generation Computing.

[Arxiv](https://arxiv.org/abs/2505.00013)