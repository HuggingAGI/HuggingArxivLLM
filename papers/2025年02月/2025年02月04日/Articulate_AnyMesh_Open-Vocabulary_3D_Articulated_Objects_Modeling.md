# Articulate AnyMesh: 开放词汇的3D关节物体建模

发布时间：2025年02月04日

`LLM应用

理由：这篇论文主要讨论了如何利用先进的视觉-语言模型和视觉提示技术来实现3D关节物体的建模。虽然论文的核心是3D建模，但其关键技术依赖于视觉-语言模型（一种大型语言模型的应用），并且这些模型被用于提取语义信息，从而实现物体部件的分割和功能关节的构建。因此，这篇论文可以被归类为LLM应用。` `计算机图形学` `机器人`

> Articulate AnyMesh: Open-Vocabulary 3D Articulated Objects Modeling

# 摘要

> # 3D 关节物体建模
3D 关节物体建模一直是个难题，因为它既要精确捕捉表面几何形状，又要确保结构、部件和关节的语义和空间准确性。现有方法主要依赖有限的手工制作关节物体类别（如橱柜和抽屉）的训练数据，限制了其在开放词汇背景下建模多样关节物体的能力。为此，我们提出了 Articulate Anymesh，一个自动化框架，能够以开放词汇方式将任何刚性 3D 网格转换为关节物体。给定一个 3D 网格，该框架利用先进的视觉-语言模型和视觉提示技术提取语义信息，实现物体部件的分割和功能关节的构建。实验表明，Articulate Anymesh 能生成大规模、高质量的 3D 关节物体，包括工具、玩具、机械设备和车辆，大幅扩展了现有 3D 关节物体数据集的覆盖范围。此外，这些生成的资产还能帮助在模拟中获取新的关节物体操作技能，并迁移到真实机器人系统中。我们的 Github 网站是 https://articulate-anymesh.github.io。

> 3D articulated objects modeling has long been a challenging problem, since it requires to capture both accurate surface geometries and semantically meaningful and spatially precise structures, parts, and joints. Existing methods heavily depend on training data from a limited set of handcrafted articulated object categories (e.g., cabinets and drawers), which restricts their ability to model a wide range of articulated objects in an open-vocabulary context. To address these limitations, we propose Articulate Anymesh, an automated framework that is able to convert any rigid 3D mesh into its articulated counterpart in an open-vocabulary manner. Given a 3D mesh, our framework utilizes advanced Vision-Language Models and visual prompting techniques to extract semantic information, allowing for both the segmentation of object parts and the construction of functional joints. Our experiments show that Articulate Anymesh can generate large-scale, high-quality 3D articulated objects, including tools, toys, mechanical devices, and vehicles, significantly expanding the coverage of existing 3D articulated object datasets. Additionally, we show that these generated assets can facilitate the acquisition of new articulated object manipulation skills in simulation, which can then be transferred to a real robotic system. Our Github website is https://articulate-anymesh.github.io.

[Arxiv](https://arxiv.org/abs/2502.02590)