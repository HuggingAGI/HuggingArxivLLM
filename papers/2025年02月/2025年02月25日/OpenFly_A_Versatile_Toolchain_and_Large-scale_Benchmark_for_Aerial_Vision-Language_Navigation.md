# OpenFly：一个灵活的工具链和大规模基准测试，专为航空视觉语言导航设计

发布时间：2025年02月25日

`Agent` `计算机视觉` `导航系统`

> OpenFly: A Versatile Toolchain and Large-scale Benchmark for Aerial Vision-Language Navigation

# 摘要

> 视觉语言导航（VLN）通过结合语言指令和视觉线索，引导智能体在环境中导航，在具身智能领域至关重要。尽管室内VLN研究已较为成熟，但室外空中学导航仍处于探索阶段。这主要是因为室外空中学视角涵盖范围广，数据收集更具挑战性，导致缺乏基准。为解决这一问题，我们提出了OpenFly平台，包含多功能工具链和大规模空中学导航基准。首先，我们开发了一个高度自动化的工具链，支持点云获取、场景分割、轨迹创建和指令生成。其次，基于该工具链，我们构建了一个包含10万条轨迹、覆盖18个场景的大型数据集。数据通过虚幻引擎、GTA V、谷歌地球和3D高斯散射（3D GS）等技术生成，视觉质量高。3D GS支持实拍到模拟渲染，增强了数据集的真实感。第三，我们提出了OpenFly-Agent，一个基于关键帧的VLN模型，直接根据语言指令和观测输出飞行动作。实验结果表明，OpenFly平台和模型具有显著优势。工具链、数据集和代码将开源发布。


> Vision-Language Navigation (VLN) aims to guide agents through an environment by leveraging both language instructions and visual cues, playing a pivotal role in embodied AI. Indoor VLN has been extensively studied, whereas outdoor aerial VLN remains underexplored. The potential reason is that outdoor aerial view encompasses vast areas, making data collection more challenging, which results in a lack of benchmarks. To address this problem, we propose OpenFly, a platform comprising a versatile toolchain and large-scale benchmark for aerial VLN. Firstly, we develop a highly automated toolchain for data collection, enabling automatic point cloud acquisition, scene semantic segmentation, flight trajectory creation, and instruction generation. Secondly, based on the toolchain, we construct a large-scale aerial VLN dataset with 100k trajectories, covering diverse heights and lengths across 18 scenes. The corresponding visual data are generated using various rendering engines and advanced techniques, including Unreal Engine, GTA V, Google Earth, and 3D Gaussian Splatting (3D GS). All data exhibit high visual quality. Particularly, 3D GS supports real-to-sim rendering, further enhancing the realism of the dataset. Thirdly, we propose OpenFly-Agent, a keyframe-aware VLN model, which takes language instructions, current observations, and historical keyframes as input, and outputs flight actions directly. Extensive analyses and experiments are conducted, showcasing the superiority of our OpenFly platform and OpenFly-Agent. The toolchain, dataset, and codes will be open-sourced.

[Arxiv](https://arxiv.org/abs/2502.18041)