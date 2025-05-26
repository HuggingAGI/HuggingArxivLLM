# 多模态对话结构理解

发布时间：2025年05月23日

`LLM应用` `对话系统`

> Multimodal Conversation Structure Understanding

# 摘要

> 对话通常由角色构建——谁在发言，谁是受众，谁在倾听——并沿着因说话者轮换或话题变化而展开的线程进行。尽管大型语言模型在对话和推理方面表现出色，但它们对细粒度对话结构的理解，尤其是在多模态、多方场景中，仍有待深入探索。为填补这一研究空白，我们推出了一套专注于对话角色归属（包括说话者、受话者和旁听者）和对话线程（涉及话语链接与聚类）的任务，并结合对话分析和社会语言学理论进行设计。为此，我们构建了一个包含 4,398 个说话者和回复关系标注、5,755 个受话者以及 3,142 个旁听者的人工标注数据集。

在我们的数据集上评估了多种主流的视听 LLM 和视觉语言模型，实验结果表明，多模态对话结构理解仍具挑战性。其中，表现最佳的视听 LLM 在所有评估指标上均优于视觉语言模型，尤其在说话者和受话者识别方面优势明显。然而，当对话参与者被匿名化时，其性能显著下降。对话参与者数量是角色归属性能的最强负向预测因子，而语音清晰度（通过音调和频谱质心衡量）和面部覆盖范围则与性能呈正相关。我们希望这项研究能为未来评估和发展更高效推理对话结构的多模态 LLM 提供坚实基础。


> Conversations are usually structured by roles -- who is speaking, who's being addressed, and who's listening -- and unfold in threads that break with changes in speaker floor or topical focus. While large language models (LLMs) have shown incredible capabilities in dialogue and reasoning, their ability to understand fine-grained conversational structure, especially in multi-modal, multi-party settings, remains underexplored. To address this gap, we introduce a suite of tasks focused on conversational role attribution (speaker, addressees, side-participants) and conversation threading (utterance linking and clustering), drawing on conversation analysis and sociolinguistics. To support those tasks, we present a human annotated dataset of 4,398 annotations for speakers and reply-to relationship, 5,755 addressees, and 3,142 side-participants.
  We evaluate popular audio-visual LLMs and vision-language models on our dataset, and our experimental results suggest that multimodal conversational structure understanding remains challenging. The most performant audio-visual LLM outperforms all vision-language models across all metrics, especially in speaker and addressee recognition. However, its performance drops significantly when conversation participants are anonymized. The number of conversation participants in a clip is the strongest negative predictor of role-attribution performance, while acoustic clarity (measured by pitch and spectral centroid) and detected face coverage yield positive associations. We hope this work lays the groundwork for future evaluation and development of multimodal LLMs that can reason more effectively about conversation structure.

[Arxiv](https://arxiv.org/abs/2505.17536)