# SceneCraft——专为生成Blender代码而设计的3D场景构建LLM智能体

发布时间：2024年03月02日

`Agent`

> SceneCraft: An LLM Agent for Synthesizing 3D Scene as Blender Code

# 摘要

> 本文推出的SceneCraft是一种强大的LLM代理，能将文字描绘转化为能在Blender中执行的Python脚本，轻松构建含有上百个3D元素的复杂场景，这要求精细的空间布局和规划。我们巧妙融合高级抽象技术、策略性规划设计与库学习方法来解决这些难题。SceneCraft首先以蓝图形式构建场景图，详尽展示场景内各元素的空间关联。接着，它根据此图谱编写Python脚本，将关系逻辑转化为具体的三维布局约束条件。进一步地，SceneCraft运用如GPT-V之类的视觉-语言基础模型的强大感知能力，对渲染出的图像进行分析，并循环优化场景效果。值得一提的是，SceneCraft还内置了一个库学习机制，能够将常用的脚本功能整合为可复用的代码库，助力系统在无需高昂代价调整LLM参数的情况下不断自我提升。实验证明，SceneCraft在构建复杂场景方面的表现超越了现有同类LLM代理，不仅严格满足各种限制条件，还在人工评价中获得高度好评。同时，我们通过应用SceneCraft成功重现了电影Sintel中的细致3D场景，并将其产生的场景作为中介控制信号指导视频生成模型运作，以此展现SceneCraft广阔的应用前景。

> This paper introduces SceneCraft, a Large Language Model (LLM) Agent converting text descriptions into Blender-executable Python scripts which render complex scenes with up to a hundred 3D assets. This process requires complex spatial planning and arrangement. We tackle these challenges through a combination of advanced abstraction, strategic planning, and library learning. SceneCraft first models a scene graph as a blueprint, detailing the spatial relationships among assets in the scene. SceneCraft then writes Python scripts based on this graph, translating relationships into numerical constraints for asset layout. Next, SceneCraft leverages the perceptual strengths of vision-language foundation models like GPT-V to analyze rendered images and iteratively refine the scene. On top of this process, SceneCraft features a library learning mechanism that compiles common script functions into a reusable library, facilitating continuous self-improvement without expensive LLM parameter tuning. Our evaluation demonstrates that SceneCraft surpasses existing LLM-based agents in rendering complex scenes, as shown by its adherence to constraints and favorable human assessments. We also showcase the broader application potential of SceneCraft by reconstructing detailed 3D scenes from the Sintel movie and guiding a video generative model with generated scenes as intermediary control signal.

[Arxiv](https://arxiv.org/abs/2403.01248)