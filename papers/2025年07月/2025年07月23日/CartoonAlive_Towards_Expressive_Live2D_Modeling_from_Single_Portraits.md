# CartoonAlive: 从单幅肖像迈向生动的 Live2D 模型构建

发布时间：2025年07月23日

`其他` `数字人`

> CartoonAlive: Towards Expressive Live2D Modeling from Single Portraits

# 摘要

> # 数字人技术的突破与CartoonAlive方法

随着大型基础模型、AIGC、云渲染和实时动作捕捉技术的快速发展，数字人技术迎来了质的飞跃。如今，数字人不仅能实现面部表情与身体动作的精准同步，还能通过自然语言进行智能对话，甚至快速生成个性化的虚拟形象。然而，在目前主流的数字人方法中，3D模型和2D视频表示占据了主导地位，而交互式2D卡通风格数字人却鲜少被提及。

与传统3D数字人相比，2D卡通风格的Live2D模型具有显著优势。无需复杂的3D建模流程，Live2D通过分层分割技术模拟3D般的动作效果，实现了动态和实时的操作。这不仅降低了制作成本，还提升了数字人的灵活性和交互性。

在本技术报告中，我们推出了CartoonAlive——一种从单张输入人像图像生成高质量Live2D数字人的创新方法。CartoonAlive采用了三维人脸建模中常用的形状基底概念，构建出适用于Live2D的面部混合形状。通过分析输入图像中的面部关键点，系统能够快速推断出对应的混合形状权重。这一流程在不到半分钟的时间内，即可生成一个高度表达且视觉上准确的Live2D模型，使其与输入人像高度相似。

CartoonAlive不仅为交互式2D卡通角色的创建提供了一种实用且可扩展的解决方案，更为数字内容创作和虚拟角色动画开辟了新的可能性。欢迎访问我们的项目主页，了解更多详情：https://human3daigc.github.io/CartoonAlive_webpage/。


> With the rapid advancement of large foundation models, AIGC, cloud rendering, and real-time motion capture technologies, digital humans are now capable of achieving synchronized facial expressions and body movements, engaging in intelligent dialogues driven by natural language, and enabling the fast creation of personalized avatars. While current mainstream approaches to digital humans primarily focus on 3D models and 2D video-based representations, interactive 2D cartoon-style digital humans have received relatively less attention. Compared to 3D digital humans that require complex modeling and high rendering costs, and 2D video-based solutions that lack flexibility and real-time interactivity, 2D cartoon-style Live2D models offer a more efficient and expressive alternative. By simulating 3D-like motion through layered segmentation without the need for traditional 3D modeling, Live2D enables dynamic and real-time manipulation. In this technical report, we present CartoonAlive, an innovative method for generating high-quality Live2D digital humans from a single input portrait image. CartoonAlive leverages the shape basis concept commonly used in 3D face modeling to construct facial blendshapes suitable for Live2D. It then infers the corresponding blendshape weights based on facial keypoints detected from the input image. This approach allows for the rapid generation of a highly expressive and visually accurate Live2D model that closely resembles the input portrait, within less than half a minute. Our work provides a practical and scalable solution for creating interactive 2D cartoon characters, opening new possibilities in digital content creation and virtual character animation. The project homepage is https://human3daigc.github.io/CartoonAlive_webpage/.

[Arxiv](https://arxiv.org/abs/2507.17327)