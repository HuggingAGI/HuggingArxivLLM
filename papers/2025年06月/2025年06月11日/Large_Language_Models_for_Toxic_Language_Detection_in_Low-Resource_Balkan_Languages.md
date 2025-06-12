# 大型语言模型在资源匮乏的巴尔干语言中检测有毒语言的应用

发布时间：2025年06月11日

`LLM应用` `内容安全` `社交媒体`

> Large Language Models for Toxic Language Detection in Low-Resource Balkan Languages

# 摘要

> 网络上的有毒言论造成切实的危害，尤其在缺少 moderation 工具的地区。本研究评估了大型语言模型如何处理塞尔维亚语、克罗地亚语和波斯尼亚语中的有毒评论，这些语言的标注数据较为有限。我们构建并手动标注了一个包含4,500条 YouTube 和 TikTok 评论的数据集，这些评论来自涵盖音乐、政治、体育、模特、网红内容、性别主义讨论和一般话题的各类视频。我们测试了四个模型（GPT-3.5 Turbo、GPT-4.1、Gemini 1.5 Pro 和 Claude 3 Opus），分别采用零样本和上下文增强两种模式。我们测量了精确率、召回率、F1 分数、准确率和假阳性率。加入一个简短的上下文片段平均提高了约 0.12 的召回率，并将 F1 分数提高了最多 0.10，尽管有时会增加假阳性。Gemini 在上下文增强模式下表现最佳，达到了 0.82 的 F1 分数和 0.82 的准确率，而零样本模式下的 GPT-4.1 在精确率方面领先，并且假警报最少。我们展示了如何通过添加少量上下文来改善资源匮乏环境下的有毒语言检测，并提出了改进提示设计和阈值校准等实用策略。这些结果表明，仅通过优化提示设计，就能为巴尔干语系社区带来显著的毒性检测提升，尤其是在这些语言资源不足的情况下。

> Online toxic language causes real harm, especially in regions with limited moderation tools. In this study, we evaluate how large language models handle toxic comments in Serbian, Croatian, and Bosnian, languages with limited labeled data. We built and manually labeled a dataset of 4,500 YouTube and TikTok comments drawn from videos across diverse categories, including music, politics, sports, modeling, influencer content, discussions of sexism, and general topics. Four models (GPT-3.5 Turbo, GPT-4.1, Gemini 1.5 Pro, and Claude 3 Opus) were tested in two modes: zero-shot and context-augmented. We measured precision, recall, F1 score, accuracy and false positive rates. Including a short context snippet raised recall by about 0.12 on average and improved F1 score by up to 0.10, though it sometimes increased false positives. The best balance came from Gemini in context-augmented mode, reaching an F1 score of 0.82 and accuracy of 0.82, while zero-shot GPT-4.1 led on precision and had the lowest false alarms. We show how adding minimal context can improve toxic language detection in low-resource settings and suggest practical strategies such as improved prompt design and threshold calibration. These results show that prompt design alone can yield meaningful gains in toxicity detection for underserved Balkan language communities.

[Arxiv](https://arxiv.org/abs/2506.09992)