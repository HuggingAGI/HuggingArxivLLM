# DeepGesture：基于情感与语义的对话式手势合成系统

发布时间：2025年07月03日

`其他` `计算机图形学` `虚拟现实`

> DeepGesture: A conversational gesture synthesis system based on emotions and semantics

# 摘要

> # 摘要
伴随大型语言模型的蓬勃发展，语音合成技术的精进、硬件性能的提升以及计算机图形学的演进，当前数字角色创建的主要瓶颈在于生成与文本或语音输入自然对应的角色动作。在本研究中，我们推出DeepGesture——一个基于扩散模型的手势合成框架，旨在根据多模态信号（包括文本、语音、情感和初始动作）生成富有表现力的伴随语言手势。在DiffuseStyleGesture模型的基础上，DeepGesture引入了创新的架构改进，显著提升了生成手势的语义对齐度和情感表达能力。具体而言，我们整合了快速文本转录作为语义条件，并实现了情感引导的无分类器扩散机制，从而支持在不同情感状态下对手势生成的可控性。轻量级的Transformer主干网络结合了全自注意力和交叉局部注意力机制，以实现异质模态特征的有效融合。为了直观展示结果，我们基于模型输出的BVH数据，在Unity引擎中构建了一条完整的渲染管线。在ZeroEGGS数据集上的评估表明，DeepGesture生成的手势在类人性和情境适应性方面均有显著提升，并在平均意见评分和弗雷谢手势距离等指标上超越了现有基线方法。我们的系统不仅能够实现情感状态的插值过渡，还展现出对分布外语音的良好泛化能力，包括合成语音——这标志着迈向全模态、情感感知数字角色的重要一步。

> Along with the explosion of large language models, improvements in speech synthesis, advancements in hardware, and the evolution of computer graphics, the current bottleneck in creating digital humans lies in generating character movements that correspond naturally to text or speech inputs.
  In this work, we present DeepGesture, a diffusion-based gesture synthesis framework for generating expressive co-speech gestures conditioned on multimodal signals-text, speech, emotion, and seed motion. Built upon the DiffuseStyleGesture model, DeepGesture introduces novel architectural enhancements that improve semantic alignment and emotional expressiveness in generated gestures. Specifically, we integrate fast text transcriptions as semantic conditioning and implement emotion-guided classifier-free diffusion to support controllable gesture generation across affective states. A lightweight Transformer backbone combines full self-attention and cross-local attention for effective feature fusion of heterogeneous modalities. To visualize results, we implement a full rendering pipeline in Unity based on BVH output from the model. Evaluation on the ZeroEGGS dataset shows that DeepGesture produces gestures with improved human-likeness and contextual appropriateness, outperforming baselines on Mean Opinion Score and Frechet Gesture Distance metrics. Our system supports interpolation between emotional states and demonstrates generalization to out-of-distribution speech, including synthetic voices-marking a step forward toward fully multimodal, emotionally aware digital humans.

[Arxiv](https://arxiv.org/abs/2507.03147)