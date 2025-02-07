# 社交媒体虚假信息中的情绪模式是否存在差异？——以瓦伦西亚DANA事件的推文和TikTok为例

发布时间：2025年01月28日

`LLM应用

理由：这篇论文主要探讨了使用GPT-4o等大型语言模型（LLM）在社交媒体平台上自动检测虚假信息的应用。论文中提到了使用GPT-4o的Few-Shot标注方法进行数据标注，并展示了LLM在虚假信息检测中的潜力。因此，这篇论文属于LLM应用的范畴。` `社交媒体` `虚假信息检测`

> Divergent Emotional Patterns in Disinformation on Social Media? An Analysis of Tweets and TikToks about the DANA in Valencia

# 摘要

> # 摘要
本研究探讨了2024年10月29日西班牙瓦伦西亚DANA事件期间社交媒体上虚假信息的传播。DANA事件引发了极端降雨和洪水。我们构建了一个包含650个TikTok和X帖子的数据集，并手动标注以区分虚假信息和可信内容。使用GPT-4o的Few-Shot标注方法与人工标注高度一致（Cohen's kappa为0.684）。情感分析显示，X平台上的虚假信息与悲伤和恐惧相关，而TikTok上的虚假信息则与愤怒和厌恶情绪相关。语言分析表明，可信内容语言清晰、事实性强，而虚假信息则通过否定词、感知词和个人轶事来增强可信度。音频分析发现，可信音频音调明亮、叙述单调，而虚假音频则通过音调变化和情感深度来吸引观众。在检测模型中，SVM+TF-IDF表现最佳，尤其在数据有限时。将音频特征融入roberta-large-bne后，模型准确率和F1分数均有所提升，超越了纯文本模型和SVM。GPT-4o Few-Shot也表现出色，展示了大型语言模型在自动检测虚假信息中的潜力。这些发现表明，在TikTok等多模态平台上，结合文本和音频特征能显著提升虚假信息检测效果。

> This study investigates the dissemination of disinformation on social media platforms during the DANA event (DANA is a Spanish acronym for Depresion Aislada en Niveles Altos, translating to high-altitude isolated depression) that resulted in extremely heavy rainfall and devastating floods in Valencia, Spain, on October 29, 2024. We created a novel dataset of 650 TikTok and X posts, which was manually annotated to differentiate between disinformation and trustworthy content. Additionally, a Few-Shot annotation approach with GPT-4o achieved substantial agreement (Cohen's kappa of 0.684) with manual labels. Emotion analysis revealed that disinformation on X is mainly associated with increased sadness and fear, while on TikTok, it correlates with higher levels of anger and disgust. Linguistic analysis using the LIWC dictionary showed that trustworthy content utilizes more articulate and factual language, whereas disinformation employs negations, perceptual words, and personal anecdotes to appear credible. Audio analysis of TikTok posts highlighted distinct patterns: trustworthy audios featured brighter tones and robotic or monotone narration, promoting clarity and credibility, while disinformation audios leveraged tonal variation, emotional depth, and manipulative musical elements to amplify engagement. In detection models, SVM+TF-IDF achieved the highest F1-Score, excelling with limited data. Incorporating audio features into roberta-large-bne improved both Accuracy and F1-Score, surpassing its text-only counterpart and SVM in Accuracy. GPT-4o Few-Shot also performed well, showcasing the potential of large language models for automated disinformation detection. These findings demonstrate the importance of leveraging both textual and audio features for improved disinformation detection on multimodal platforms like TikTok.

[Arxiv](https://arxiv.org/abs/2501.18640)