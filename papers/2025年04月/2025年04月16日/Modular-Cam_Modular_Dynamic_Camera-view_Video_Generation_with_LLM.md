# Modular-Cam：基于 LLM 的模块化动态摄像机视角视频生成

发布时间：2025年04月16日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型应用于文本到视频生成任务中，通过分析和分解复杂的文本提示来生成高质量的视频内容。因此，它属于LLM应用类别。`

> Modular-Cam: Modular Dynamic Camera-view Video Generation with LLM

# 摘要

> 文本到视频生成技术通过利用文本提示生成高质量视频，因其近期扩散模型的突破而受到广泛关注并取得显著成功。现有方法主要依赖预训练文本编码器捕获语义信息，并通过交叉注意力机制指导视频生成。然而，面对包含动态场景和多机位变换的复杂提示，现有方法在场景分解与视图切换方面存在明显局限。为此，我们提出了一种创新方法——Modular-Cam。该方法利用大型语言模型对复杂提示进行分析与分解，生成多个场景及过渡动作。通过整合时序 transformer 和提出 CamOperator 模块，Modular-Cam 能够实现场景内连续性和相机运动的精准控制。此外，我们开发的 AdaControlNet 确保了场景间的一致性，并支持视频色调的自适应调整。大量实验结果表明，Modular-Cam 在生成多场景视频及控制相机运动方面表现优异。更多生成示例请访问 https://modular-cam.github.io。

> Text-to-Video generation, which utilizes the provided text prompt to generate high-quality videos, has drawn increasing attention and achieved great success due to the development of diffusion models recently. Existing methods mainly rely on a pre-trained text encoder to capture the semantic information and perform cross attention with the encoded text prompt to guide the generation of video. However, when it comes to complex prompts that contain dynamic scenes and multiple camera-view transformations, these methods can not decompose the overall information into separate scenes, as well as fail to smoothly change scenes based on the corresponding camera-views. To solve these problems, we propose a novel method, i.e., Modular-Cam. Specifically, to better understand a given complex prompt, we utilize a large language model to analyze user instructions and decouple them into multiple scenes together with transition actions. To generate a video containing dynamic scenes that match the given camera-views, we incorporate the widely-used temporal transformer into the diffusion model to ensure continuity within a single scene and propose CamOperator, a modular network based module that well controls the camera movements. Moreover, we propose AdaControlNet, which utilizes ControlNet to ensure consistency across scenes and adaptively adjusts the color tone of the generated video. Extensive qualitative and quantitative experiments prove our proposed Modular-Cam's strong capability of generating multi-scene videos together with its ability to achieve fine-grained control of camera movements. Generated results are available at https://modular-cam.github.io.

[Arxiv](https://arxiv.org/abs/2504.12048)