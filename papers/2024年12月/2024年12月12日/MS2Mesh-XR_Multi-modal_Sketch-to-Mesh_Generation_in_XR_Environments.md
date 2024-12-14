# MS2Mesh-XR：XR 环境中的多模态草图转网格生成

发布时间：2024年12月12日

`LLM应用` `扩展现实（XR）` `3D 建模`

> MS2Mesh-XR: Multi-modal Sketch-to-Mesh Generation in XR Environments

# 摘要

> 我们带来了 MS2Mesh-XR，这是一种全新的多模态草图转网格生成管线，能让用户在扩展现实（XR）环境中，借助语音输入的手绘草图来打造逼真的 3D 物体。具体而言，用户能在虚拟环境里，凭借自然的手部在空中动作直观地绘制物体。通过融合语音输入，我们设计了 ControlNet，依据绘制的草图和解读的文本提示来推断逼真的图像。接着，用户可以查看并挑选自己心仪的图像，然后使用卷积重建模型将其重建成精细的 3D 网格。特别要指出的是，我们提出的管线能在 20 秒以内生成高品质的 3D 网格，实现运行时 XR 场景中的沉浸式可视化和操作。我们通过 XR 场景中的两个用例证明了我们管线的实用性。凭借自然的用户输入和前沿的生成式 AI 能力，我们的方法能够显著推动基于 XR 的创意生产，并提升用户体验。我们的代码和演示可在以下网址获取：https://yueqiu0911.github.io/MS2Mesh-XR/

> We present MS2Mesh-XR, a novel multi-modal sketch-to-mesh generation pipeline that enables users to create realistic 3D objects in extended reality (XR) environments using hand-drawn sketches assisted by voice inputs. In specific, users can intuitively sketch objects using natural hand movements in mid-air within a virtual environment. By integrating voice inputs, we devise ControlNet to infer realistic images based on the drawn sketches and interpreted text prompts. Users can then review and select their preferred image, which is subsequently reconstructed into a detailed 3D mesh using the Convolutional Reconstruction Model. In particular, our proposed pipeline can generate a high-quality 3D mesh in less than 20 seconds, allowing for immersive visualization and manipulation in run-time XR scenes. We demonstrate the practicability of our pipeline through two use cases in XR settings. By leveraging natural user inputs and cutting-edge generative AI capabilities, our approach can significantly facilitate XR-based creative production and enhance user experiences. Our code and demo will be available at: https://yueqiu0911.github.io/MS2Mesh-XR/

[Arxiv](https://arxiv.org/abs/2412.09008)