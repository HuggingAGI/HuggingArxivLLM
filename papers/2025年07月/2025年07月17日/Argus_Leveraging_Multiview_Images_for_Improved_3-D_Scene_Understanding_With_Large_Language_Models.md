# Argus: 利用多视图图像增强大型语言模型的三维场景理解能力

发布时间：2025年07月17日

`LLM应用` `计算机视觉` `3D重建`

> Argus: Leveraging Multiview Images for Improved 3-D Scene Understanding With Large Language Models

# 摘要

> 基础模型的突破性进展为各类下游任务的应用开辟了新可能，尤其在3D场景理解领域，大型语言模型（LLMs）展现出了卓越的扩展潜力。然而，当前基于3D点云的方法存在明显局限：室内场景重建常导致信息缺失，无纹理平面或重复模式易被遗漏，形成空白区域；复杂结构物体因图像与点云错位而造成细节失真。2D多视图图像与3D点云具有一致性，能提供更细致的场景表示，天然弥补上述缺陷。基于此，我们提出Argus——一种创新的3D多模态框架，通过融合多视图图像与LLMs，提升3D场景理解能力。Argus可被视为3D大型多模态基础模型（3D-LMM），它整合文本指令、2D多视图图像和3D点云，扩展LLMs处理3D任务的能力。通过融合多视图图像与相机姿态生成视图特征，并与3D特征交互，Argus构建了全面、细致的3D感知场景嵌入。这种方法不仅弥补了3D点云重建中的信息缺失，还助力LLMs更深入地理解3D世界。实验结果表明，Argus在各类下游任务中显著优于现有3D-LMMs。

> Advancements in foundation models have made it possible to conduct applications in various downstream tasks. Especially, the new era has witnessed a remarkable capability to extend Large Language Models (LLMs) for tackling tasks of 3D scene understanding. Current methods rely heavily on 3D point clouds, but the 3D point cloud reconstruction of an indoor scene often results in information loss. Some textureless planes or repetitive patterns are prone to omission and manifest as voids within the reconstructed 3D point clouds. Besides, objects with complex structures tend to introduce distortion of details caused by misalignments between the captured images and the dense reconstructed point clouds. 2D multi-view images present visual consistency with 3D point clouds and provide more detailed representations of scene components, which can naturally compensate for these deficiencies. Based on these insights, we propose Argus, a novel 3D multimodal framework that leverages multi-view images for enhanced 3D scene understanding with LLMs. In general, Argus can be treated as a 3D Large Multimodal Foundation Model (3D-LMM) since it takes various modalities as input(text instructions, 2D multi-view images, and 3D point clouds) and expands the capability of LLMs to tackle 3D tasks. Argus involves fusing and integrating multi-view images and camera poses into view-as-scene features, which interact with the 3D features to create comprehensive and detailed 3D-aware scene embeddings. Our approach compensates for the information loss while reconstructing 3D point clouds and helps LLMs better understand the 3D world. Extensive experiments demonstrate that our method outperforms existing 3D-LMMs in various downstream tasks.

[Arxiv](https://arxiv.org/abs/2507.12916)