# 多模态机器学习中嵌入技术在精神疾病评估中的应用

发布时间：2025年04月02日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLM）应用于心理健康问题的诊断，特别是抑郁症和PTSD的检测。虽然它涉及多模态数据和机器学习技术，但核心在于将LLM作为工具来提升诊断的准确性，属于应用层面的研究。` `心理健康`

> Leveraging Embedding Techniques in Multimodal Machine Learning for Mental Illness Assessment

# 摘要

> 全球心理健康问题日益严重，抑郁症和创伤后应激障碍（PTSD）的患病率持续攀升，这迫切需要更客观、更高效的诊断工具。传统的临床评估方法往往存在可及性不足、客观性有限以及一致性欠佳等问题。本研究聚焦于多模态机器学习技术，旨在突破这些局限。通过整合文本、音频和视频数据中的互补信息，我们提出了一套全新的解决方案。我们的研究从数据预处理入手，探索了多种创新策略，包括基于语句的分块处理和格式化方法。在模型评估方面，我们系统性地对比了各类先进的嵌入模型，并结合卷积神经网络（CNNs）和双向长短时记忆网络（BiLSTMs）进行特征提取。在融合技术层面，我们不仅考察了数据级、特征级和决策级的多种融合方式，还首次尝试了将大型语言模型（LLM）的预测结果融入其中。实验结果表明，基于语句的分块处理显著提升了模型性能，尤其是在文本和音频模态中表现尤为突出。而将LLM预测结果纳入决策级融合，更是在抑郁症检测中实现了94.8%的平衡准确率，在PTSD检测中达到了96.2%的平衡准确率。结合CNN-BiLSTM架构和语句级分块处理，并融入外部LLM的预测能力，我们为心理健康问题的检测和评估提供了一种强大且精细的方法。本研究不仅验证了多模态机器学习在心理健康领域的巨大潜力，更为开发更精准、更易获取且更具个性化的心理健康护理工具开辟了新的可能。

> The increasing global prevalence of mental disorders, such as depression and PTSD, requires objective and scalable diagnostic tools. Traditional clinical assessments often face limitations in accessibility, objectivity, and consistency. This paper investigates the potential of multimodal machine learning to address these challenges, leveraging the complementary information available in text, audio, and video data. Our approach involves a comprehensive analysis of various data preprocessing techniques, including novel chunking and utterance-based formatting strategies. We systematically evaluate a range of state-of-the-art embedding models for each modality and employ Convolutional Neural Networks (CNNs) and Bidirectional LSTM Networks (BiLSTMs) for feature extraction. We explore data-level, feature-level, and decision-level fusion techniques, including a novel integration of Large Language Model (LLM) predictions. We also investigate the impact of replacing Multilayer Perceptron classifiers with Support Vector Machines. We extend our analysis to severity prediction using PHQ-8 and PCL-C scores and multi-class classification (considering co-occurring conditions). Our results demonstrate that utterance-based chunking significantly improves performance, particularly for text and audio modalities. Decision-level fusion, incorporating LLM predictions, achieves the highest accuracy, with a balanced accuracy of 94.8% for depression and 96.2% for PTSD detection. The combination of CNN-BiLSTM architectures with utterance-level chunking, coupled with the integration of external LLM, provides a powerful and nuanced approach to the detection and assessment of mental health conditions. Our findings highlight the potential of MMML for developing more accurate, accessible, and personalized mental healthcare tools.

[Arxiv](https://arxiv.org/abs/2504.01767)