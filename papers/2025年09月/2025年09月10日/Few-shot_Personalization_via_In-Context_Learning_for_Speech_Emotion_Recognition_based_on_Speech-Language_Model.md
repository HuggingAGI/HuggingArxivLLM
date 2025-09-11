# 基于语音语言模型的语音情感识别：上下文学习驱动的少样本个性化

发布时间：2025年09月10日

`LLM应用` `媒体与娱乐`

> Few-shot Personalization via In-Context Learning for Speech Emotion Recognition based on Speech-Language Model

# 摘要

> 本文提出一种基于上下文学习（ICL）的语音情感识别（SER）个性化方法。情感表达因人而异，因此针对特定说话人的自适应对提升SER性能至关重要。传统SER方法依赖目标说话人的情感话语实现个性化，然而预先准备覆盖所有情感标签的话语往往存在困难。为解决这一问题，我们提出在基于ICL的推理过程中，通过对目标说话人的少量情感话语进行条件化处理，从而提取说话人特征。ICL是大型语言模型（LLMs）的一种推理方法，通过对少量输入-输出示例进行条件化处理，即可完成未见任务。我们对基于LLM扩展的语音-语言模型进行元训练，使其学会通过ICL实现个性化SER。基于新收集的SER数据集的实验结果显示，该方法性能优于传统方法。

> This paper proposes a personalization method for speech emotion recognition (SER) through in-context learning (ICL). Since the expression of emotions varies from person to person, speaker-specific adaptation is crucial for improving the SER performance. Conventional SER methods have been personalized using emotional utterances of a target speaker, but it is often difficult to prepare utterances corresponding to all emotion labels in advance. Our idea to overcome this difficulty is to obtain speaker characteristics by conditioning a few emotional utterances of the target speaker in ICL-based inference. ICL is a method to perform unseen tasks by conditioning a few input-output examples through inference in large language models (LLMs). We meta-train a speech-language model extended from the LLM to learn how to perform personalized SER via ICL. Experimental results using our newly collected SER dataset demonstrate that the proposed method outperforms conventional methods.

[Arxiv](https://arxiv.org/abs/2509.08344)