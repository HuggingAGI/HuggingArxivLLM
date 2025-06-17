# 探索音频线索，提升视频模型在测试时的适应能力

发布时间：2025年06月14日

`LLM应用`

> Exploring Audio Cues for Enhanced Test-Time Video Model Adaptation

# 摘要

> 测试时间适应（TTA）通过在测试阶段进行自/无监督学习，旨在提升模型的泛化能力。现有视频TTA方法多依赖视觉信号，却忽视了音频数据的潜力。我们提出了一种创新方法，将音频信息引入视频TTA。通过音频中的丰富语义，我们生成了音频辅助伪标签这一新概念。具体而言，我们采用预训练音频模型对视频音频进行分类，并借助大型语言模型将音频预测映射至视频标签空间，实现了音频类别与视频标签的关联。为充分利用伪标签，我们设计了一种灵活的适应循环，基于损失变化和视角一致性，为每个样本确定最佳适应次数，实现个性化适应。在UCF101-C、Kinetics-Sounds-C以及新构建的AVE-C和AVMIT-C数据集上的实验表明，我们的方法显著优于现有方案。无论是在不同视频分类模型上的表现，还是在音频信息整合方面，都取得了重要突破。代码已开源：https://github.com/keikeiqi/Audio-Assisted-TTA。

> Test-time adaptation (TTA) aims to boost the generalization capability of a trained model by conducting self-/unsupervised learning during the testing phase. While most existing TTA methods for video primarily utilize visual supervisory signals, they often overlook the potential contribution of inherent audio data. To address this gap, we propose a novel approach that incorporates audio information into video TTA. Our method capitalizes on the rich semantic content of audio to generate audio-assisted pseudo-labels, a new concept in the context of video TTA. Specifically, we propose an audio-to-video label mapping method by first employing pre-trained audio models to classify audio signals extracted from videos and then mapping the audio-based predictions to video label spaces through large language models, thereby establishing a connection between the audio categories and video labels. To effectively leverage the generated pseudo-labels, we present a flexible adaptation cycle that determines the optimal number of adaptation iterations for each sample, based on changes in loss and consistency across different views. This enables a customized adaptation process for each sample. Experimental results on two widely used datasets (UCF101-C and Kinetics-Sounds-C), as well as on two newly constructed audio-video TTA datasets (AVE-C and AVMIT-C) with various corruption types, demonstrate the superiority of our approach. Our method consistently improves adaptation performance across different video classification models and represents a significant step forward in integrating audio information into video TTA. Code: https://github.com/keikeiqi/Audio-Assisted-TTA.

[Arxiv](https://arxiv.org/abs/2506.12481)