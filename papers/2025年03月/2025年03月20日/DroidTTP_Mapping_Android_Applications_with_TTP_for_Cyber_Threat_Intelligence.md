# DroidTTP：基于TTP的Android应用映射技术，助力网络威胁情报分析

发布时间：2025年03月20日

`LLM应用` `移动安全` `网络安全`

> DroidTTP: Mapping Android Applications with TTP for Cyber Threat Intelligence

# 摘要

> 安卓设备在银行和通信等敏感操作中的广泛应用，使其成为网络威胁的首要目标，尤其是针对高级持续性威胁（APT）和复杂恶意软件攻击。传统恶意软件检测方法依赖二分类，无法揭示对手的战术、技术和程序（TTPs）。理解恶意软件行为对提升网络安全防御至关重要。为解决这一问题，我们提出了DroidTTP框架，基于MITRE ATT&CK框架，将Android恶意软件行为映射到TTPs。我们整理的精选数据集明确关联了MITRE TTPs与Android应用程序。我们开发了一种基于问题转化方法（PTA）和大型语言模型（LLMs）的自动化解决方案，用于将应用程序映射到战术和技巧。此外，我们还采用了检索增强生成（RAG），结合提示工程和LLM微调，进行TTP预测。我们的结构化管道包括数据集创建、超参数调整、数据增强、特征选择、模型开发以及基于SHAP的模型可解释性。在LLMs中，Llama在战术分类中取得了最高性能，Jaccard相似度为0.9583，汉明损失为0.0182；在技巧分类中，Jaccard相似度为0.9348，汉明损失为0.0127。然而，Label Powerset XGBoost模型表现优于LLMs，其战术分类的Jaccard相似度为0.9893，技巧分类为0.9753，汉明损失分别为0.0054和0.0050。尽管XGBoost表现更优，但其优势微弱，凸显了基于LLM方法在TTP分类中的潜力。

> The widespread adoption of Android devices for sensitive operations like banking and communication has made them prime targets for cyber threats, particularly Advanced Persistent Threats (APT) and sophisticated malware attacks. Traditional malware detection methods rely on binary classification, failing to provide insights into adversarial Tactics, Techniques, and Procedures (TTPs). Understanding malware behavior is crucial for enhancing cybersecurity defenses. To address this gap, we introduce DroidTTP, a framework mapping Android malware behaviors to TTPs based on the MITRE ATT&CK framework. Our curated dataset explicitly links MITRE TTPs to Android applications. We developed an automated solution leveraging the Problem Transformation Approach (PTA) and Large Language Models (LLMs) to map applications to both Tactics and Techniques. Additionally, we employed Retrieval-Augmented Generation (RAG) with prompt engineering and LLM fine-tuning for TTP predictions. Our structured pipeline includes dataset creation, hyperparameter tuning, data augmentation, feature selection, model development, and SHAP-based model interpretability. Among LLMs, Llama achieved the highest performance in Tactic classification with a Jaccard Similarity of 0.9583 and Hamming Loss of 0.0182, and in Technique classification with a Jaccard Similarity of 0.9348 and Hamming Loss of 0.0127. However, the Label Powerset XGBoost model outperformed LLMs, achieving a Jaccard Similarity of 0.9893 for Tactic classification and 0.9753 for Technique classification, with a Hamming Loss of 0.0054 and 0.0050, respectively. While XGBoost showed superior performance, the narrow margin highlights the potential of LLM-based approaches in TTP classification.

[Arxiv](https://arxiv.org/abs/2503.15866)