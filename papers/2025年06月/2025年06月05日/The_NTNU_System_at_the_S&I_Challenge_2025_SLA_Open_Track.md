# NTNU系统在S&I挑战赛2025 SLA开放赛道中的表现

发布时间：2025年06月05日

`LLM应用

摘要讨论了将大语言模型（如Phi-4）与语音模型结合，应用于口语评估，属于LLM的应用场景。` `语音语言评估` `多模态`

> The NTNU System at the S&I Challenge 2025 SLA Open Track

# 摘要

> 近期语音语言评估（SLA）领域的研究采用BERT和wav2vec 2.0（W2V）等神经模型，通过语言和声学模态评估口语熟练度。尽管这两个模型都能有效捕捉与口语能力相关的特征，但每个模型都有其特定的局限性。基于BERT的方法依赖于ASR转录，通常无法捕捉到与SLA相关的韵律和语音特征。而基于W2V的方法擅长建模声学特征，但缺乏语义可解释性。为克服这些限制，我们提出了一种通过得分融合策略将W2V与Phi-4多模态大语言模型（MLLM）相结合的系统。该系统在Speak & Improve Challenge 2025官方测试集上实现了0.375的均方根误差（RMSE），在竞赛中获得第二名。相比之下，排名第一、第三和官方基线系统的RMSE分别为0.364、0.384和0.444。

> A recent line of research on spoken language assessment (SLA) employs neural models such as BERT and wav2vec 2.0 (W2V) to evaluate speaking proficiency across linguistic and acoustic modalities. Although both models effectively capture features relevant to oral competence, each exhibits modality-specific limitations. BERT-based methods rely on ASR transcripts, which often fail to capture prosodic and phonetic cues for SLA. In contrast, W2V-based methods excel at modeling acoustic features but lack semantic interpretability. To overcome these limitations, we propose a system that integrates W2V with Phi-4 multimodal large language model (MLLM) through a score fusion strategy. The proposed system achieves a root mean square error (RMSE) of 0.375 on the official test set of the Speak & Improve Challenge 2025, securing second place in the competition. For comparison, the RMSEs of the top-ranked, third-ranked, and official baseline systems are 0.364, 0.384, and 0.444, respectively.

[Arxiv](https://arxiv.org/abs/2506.05121)