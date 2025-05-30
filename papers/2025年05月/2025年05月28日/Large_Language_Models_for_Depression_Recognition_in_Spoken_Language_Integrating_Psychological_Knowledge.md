# # 摘要
融合心理知识的大型语言模型在口语抑郁情绪识别中的应用

发布时间：2025年05月28日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在抑郁症检测中的应用，提出了一种多模态方法，并将其应用于特定数据集。这属于LLM的实际应用，因此归类为LLM应用。` `心理健康`

> Large Language Models for Depression Recognition in Spoken Language Integrating Psychological Knowledge

# 摘要

> 抑郁症正日益成为一个备受关注的问题，不仅在公共讨论中，在人工智能研究领域也备受瞩目。尽管深度神经网络（DNNs）已被用于识别抑郁症，但它们在现实世界中的效果仍不理想。大型语言模型（LLMs）显示出强大的潜力，但需要特定领域的微调，并且在处理非文本线索方面存在困难。由于抑郁症往往通过语音语调和行为而非明确的文字表达，仅依赖语言是不够的。此外，缺乏心理专业知识的整合也影响了诊断的准确性。

为了解决这些局限性，我们提出了一个基于LLMs的多模态抑郁症检测方法，据我们所知，这是首次应用于DAIC-WOZ数据集。我们使用预训练模型Wav2Vec提取音频特征，并将其映射到基于文本的LLMs进行进一步处理。我们还提出了一种将心理知识整合到LLMs中的新策略，以提升诊断性能，具体方法是通过问答集授予LLMs授权知识。与相关原始论文提出的基准分数相比，我们的方法在平均绝对误差（MAE）和均方根误差（RMSE）方面均取得了显著改进。代码可在https://github.com/myxp-lyp/Depression-detection.git获取。

> Depression is a growing concern gaining attention in both public discourse and AI research. While deep neural networks (DNNs) have been used for recognition, they still lack real-world effectiveness. Large language models (LLMs) show strong potential but require domain-specific fine-tuning and struggle with non-textual cues. Since depression is often expressed through vocal tone and behaviour rather than explicit text, relying on language alone is insufficient. Diagnostic accuracy also suffers without incorporating psychological expertise. To address these limitations, we present, to the best of our knowledge, the first application of LLMs to multimodal depression detection using the DAIC-WOZ dataset. We extract the audio features using the pre-trained model Wav2Vec, and mapped it to text-based LLMs for further processing. We also propose a novel strategy for incorporating psychological knowledge into LLMs to enhance diagnostic performance, specifically using a question and answer set to grant authorised knowledge to LLMs. Our approach yields a notable improvement in both Mean Absolute Error (MAE) and Root Mean Square Error (RMSE) compared to a base score proposed by the related original paper. The codes are available at https://github.com/myxp-lyp/Depression-detection.git

[Arxiv](https://arxiv.org/abs/2505.22863)