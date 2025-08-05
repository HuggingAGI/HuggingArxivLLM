# # 短视频用户互动预测：基于大型多模态模型的探索

发布时间：2025年08月04日

`LLM应用` `短视频` `推荐系统`

> Engagement Prediction of Short Videos with Large Multimodal Models

# 摘要

> 短视频平台上用户生成内容（UGC）的激增，使得视频互动预测在优化推荐系统和指导内容创作方面变得愈发重要。然而，这一任务仍具挑战性，原因在于语义内容、视觉质量、音频特征及用户背景等因素间的复杂交互作用。已有研究尝试从多模态数据中提取多种特征，如视觉质量、语义内容和背景音等，但往往难以有效建模跨特征与跨模态的交互。本研究实证探索了大型多模态模型（LMMs）在视频互动预测中的潜力。我们选取了两种典型的LMMs进行研究：VideoLLaMA2整合了音频、视觉与语言模态，而Qwen2.5-VL则专注于视觉与语言模态。具体而言，VideoLLaMA2能够同时处理关键视频帧、基于文本的元数据及背景音，而Qwen2.5-VL仅利用关键视频帧和文本元数据。在SnapUGC数据集上的训练结果显示，两种模型均展现出超越现有最优基线的竞争力，证明了LMMs在互动预测中的有效性。值得注意的是，VideoLLaMA2在预测中持续优于Qwen2.5-VL，凸显了音频特征在互动预测中的关键作用。通过将两种模型进行集成，我们在ICCV VQualA 2025 EVQA-SnapUGC挑战赛中斩获短视频互动预测的第一名。代码已开源，地址为https://github.com/sunwei925/LMM-EVQA.git。

> The rapid proliferation of user-generated content (UGC) on short-form video platforms has made video engagement prediction increasingly important for optimizing recommendation systems and guiding content creation. However, this task remains challenging due to the complex interplay of factors such as semantic content, visual quality, audio characteristics, and user background. Prior studies have leveraged various types of features from different modalities, such as visual quality, semantic content, background sound, etc., but often struggle to effectively model their cross-feature and cross-modality interactions. In this work, we empirically investigate the potential of large multimodal models (LMMs) for video engagement prediction. We adopt two representative LMMs: VideoLLaMA2, which integrates audio, visual, and language modalities, and Qwen2.5-VL, which models only visual and language modalities. Specifically, VideoLLaMA2 jointly processes key video frames, text-based metadata, and background sound, while Qwen2.5-VL utilizes only key video frames and text-based metadata. Trained on the SnapUGC dataset, both models demonstrate competitive performance against state-of-the-art baselines, showcasing the effectiveness of LMMs in engagement prediction. Notably, VideoLLaMA2 consistently outperforms Qwen2.5-VL, highlighting the importance of audio features in engagement prediction. By ensembling two types of models, our method achieves first place in the ICCV VQualA 2025 EVQA-SnapUGC Challenge on short-form video engagement prediction. The code is available at https://github.com/sunwei925/LMM-EVQA.git.

[Arxiv](https://arxiv.org/abs/2508.02516)