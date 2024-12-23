# TouchASP：人人可触的弹性自动语音感知

发布时间：2024年12月20日

`其他` `语音识别` `自动语音感知`

> TouchASP: Elastic Automatic Speech Perception that Everyone Can Touch

# 摘要

> 大型自动语音识别（ASR）模型在训练时，需要众多参数、海量数据以及大量计算资源。然而，这类模型仅能部署在高算力的云平台上，且只能执行语音识别任务，这导致成本高、能力受限。在本报告中，我们先是提出了专家弹性混合（eMoE）模型，该模型只需训练一次，然后就能根据部署需求弹性缩放。其次，我们设计了无监督的数据创建与验证程序，并从不同领域收集了数百万小时的音频数据用于训练。凭借这两项技术，我们的系统实现了弹性部署能力，同时将 SpeechIO 测试集上的字符错误率（CER）从 4.98％降至 2.45％。再者，我们的模型不仅能做好普通话语音识别，还精通多语言、多方言、情感、性别和声音事件感知。我们称其为自动语音感知（ASP），感知结果在实验部分呈现。

> Large Automatic Speech Recognition (ASR) models demand a vast number of parameters, copious amounts of data, and significant computational resources during the training process. However, such models can merely be deployed on high-compute cloud platforms and are only capable of performing speech recognition tasks. This leads to high costs and restricted capabilities. In this report, we initially propose the elastic mixture of the expert (eMoE) model. This model can be trained just once and then be elastically scaled in accordance with deployment requirements. Secondly, we devise an unsupervised data creation and validation procedure and gather millions of hours of audio data from diverse domains for training. Using these two techniques, our system achieves elastic deployment capabilities while reducing the Character Error Rate (CER) on the SpeechIO testsets from 4.98\% to 2.45\%. Thirdly, our model is not only competent in Mandarin speech recognition but also proficient in multilingual, multi-dialect, emotion, gender, and sound event perception. We refer to this as Automatic Speech Perception (ASP), and the perception results are presented in the experimental section.

[Arxiv](https://arxiv.org/abs/2412.15622)