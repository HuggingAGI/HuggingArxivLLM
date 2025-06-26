# 可编程房间：由大型语言模型助力实现的交互式纹理三维房间网格生成

发布时间：2025年06月21日

`LLM应用` `三维建模` `计算机图形学`

> Programmable-Room: Interactive Textured 3D Room Meshes Generation Empowered by Large Language Models

# 摘要

> 我们提出了一种名为Programmable-Room的框架，它能根据自然语言指令交互式地生成和编辑三维房间网格。为了实现对房间各属性的精准控制，我们将这一复杂任务分解为多个更简单的步骤，包括为房间网格创建合理的三维坐标、为纹理生成全景图像、通过整合坐标和全景纹理图像构建三维网格，以及布置家具。为了在统一框架内支持这些分解后的任务，我们引入了视觉编程（VP）。VP是一种利用大型语言模型（LLM）编写类似Python的程序的方法，该程序是针对各种自然语言任务所需的必要模块的有序列表。我们开发了其中大部分模块。特别地，在纹理生成模块中，我们使用预训练的大规模扩散模型，同时基于文本和视觉提示（即布局、深度和语义图）生成全景图像。具体而言，我们通过优化训练目标，利用双向LSTM获得的全景场景的一维表示，提升了全景图像的生成质量。我们展示了Programmable-Room在生成和编辑三维房间网格方面的灵活性，并通过定量和定性分析证明了我们的框架优于现有模型。项目页面可在 https://jihyun0510.github.io/Programmable_Room_Page/ 访问。

> We present Programmable-Room, a framework which interactively generates and edits a 3D room mesh, given natural language instructions. For precise control of a room's each attribute, we decompose the challenging task into simpler steps such as creating plausible 3D coordinates for room meshes, generating panorama images for the texture, constructing 3D meshes by integrating the coordinates and panorama texture images, and arranging furniture. To support the various decomposed tasks with a unified framework, we incorporate visual programming (VP). VP is a method that utilizes a large language model (LLM) to write a Python-like program which is an ordered list of necessary modules for the various tasks given in natural language. We develop most of the modules. Especially, for the texture generating module, we utilize a pretrained large-scale diffusion model to generate panorama images conditioned on text and visual prompts (i.e., layout, depth, and semantic map) simultaneously. Specifically, we enhance the panorama image generation quality by optimizing the training objective with a 1D representation of a panorama scene obtained from bidirectional LSTM. We demonstrate Programmable-Room's flexibility in generating and editing 3D room meshes, and prove our framework's superiority to an existing model quantitatively and qualitatively. Project page is available in https://jihyun0510.github.io/Programmable_Room_Page/.

[Arxiv](https://arxiv.org/abs/2506.17707)