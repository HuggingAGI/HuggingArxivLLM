# DreamJourney：借助视频扩散模型实现持续视角生成

发布时间：2025年06月21日

`LLM应用` `计算机视觉` `视频生成`

> DreamJourney: Perpetual View Generation with Video Diffusion Models

# 摘要

> 永续视图生成旨在仅从单张输入图像中生成与任意摄像头轨迹相对应的长期视频。现有方法通常利用预训练的文本到图像扩散模型来生成摄像头运动过程中未见区域的新内容。然而，现有的2D扩散模型缺乏3D感知能力，导致生成内容出现视觉失真。此外，它们仅限于生成静态3D场景的视图，未能捕捉动态4D世界中的物体运动。为了解决这些问题，我们提出了DreamJourney，这是一个两阶段框架，利用视频扩散模型的世界模拟能力，触发一个新的永续场景视图生成任务，同时考虑摄像头运动和物体动力学。具体来说，在第一阶段，DreamJourney首先将输入图像提升为3D点云，并从特定摄像头轨迹渲染一系列部分图像。然后利用视频扩散模型作为生成先验，完成缺失区域并增强整个序列的视觉一致性，生成符合3D场景和摄像头轨迹的跨视图一致视频。同时，我们引入了两个简单而有效的策略（提前终止和视图填充），以进一步稳定生成过程并提高视觉质量。接下来，在第二阶段，DreamJourney利用多模态大型语言模型生成描述当前视图中物体运动的文本提示，并使用视频扩散模型为当前视图添加物体运动。第一阶段和第二阶段会反复进行，从而实现永续动态场景视图生成。大量实验表明，我们的DreamJourney在定量和定性方面均优于现有最先进的方法。我们的项目页面：https://dream-journey.vercel.app。


> Perpetual view generation aims to synthesize a long-term video corresponding to an arbitrary camera trajectory solely from a single input image. Recent methods commonly utilize a pre-trained text-to-image diffusion model to synthesize new content of previously unseen regions along camera movement. However, the underlying 2D diffusion model lacks 3D awareness and results in distorted artifacts. Moreover, they are limited to generating views of static 3D scenes, neglecting to capture object movements within the dynamic 4D world. To alleviate these issues, we present DreamJourney, a two-stage framework that leverages the world simulation capacity of video diffusion models to trigger a new perpetual scene view generation task with both camera movements and object dynamics. Specifically, in stage I, DreamJourney first lifts the input image to 3D point cloud and renders a sequence of partial images from a specific camera trajectory. A video diffusion model is then utilized as generative prior to complete the missing regions and enhance visual coherence across the sequence, producing a cross-view consistent video adheres to the 3D scene and camera trajectory. Meanwhile, we introduce two simple yet effective strategies (early stopping and view padding) to further stabilize the generation process and improve visual quality. Next, in stage II, DreamJourney leverages a multimodal large language model to produce a text prompt describing object movements in current view, and uses video diffusion model to animate current view with object movements. Stage I and II are repeated recurrently, enabling perpetual dynamic scene view generation. Extensive experiments demonstrate the superiority of our DreamJourney over state-of-the-art methods both quantitatively and qualitatively. Our project page: https://dream-journey.vercel.app.

[Arxiv](https://arxiv.org/abs/2506.17705)