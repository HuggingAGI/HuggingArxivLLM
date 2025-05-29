# CAD审查：具备错误检测和修复功能的自动CAD程序审查工具

发布时间：2025年05月28日

`LLM应用` `计算机辅助设计` `三维设计`

> CADReview: Automatically Reviewing CAD Programs with Error Detection and Correction

# 摘要

> 计算机辅助设计（CAD）在构建三维原型时发挥着关键作用，它通过几何指令（即CAD程序）来实现这一目标。在实际设计流程中，设计师常常需要将原型与参考图像进行对比，从而耗费大量时间进行审查和优化。为了解决这一问题，我们提出了CAD审查任务，旨在自动检测并修正潜在错误，确保生成的三维对象与参考图像保持一致。然而，现有的多模态大语言模型在识别多个几何组件和执行空间几何操作时仍显吃力，导致审查结果不够精准。本文中，我们推出了CAD程序修复器（ReCAD）框架，以有效检测程序错误并提供有助于错误修正的反馈。此外，我们创建了一个包含20K多张程序-图像对的CADReview数据集，其中涵盖了多种多样的错误，专为CAD审查任务设计。通过广泛的实验，我们证明了我们的ReCAD显著优于现有的MLLMs，这在设计应用中展现了巨大的潜力。

> Computer-aided design (CAD) is crucial in prototyping 3D objects through geometric instructions (i.e., CAD programs). In practical design workflows, designers often engage in time-consuming reviews and refinements of these prototypes by comparing them with reference images. To bridge this gap, we introduce the CAD review task to automatically detect and correct potential errors, ensuring consistency between the constructed 3D objects and reference images. However, recent advanced multimodal large language models (MLLMs) struggle to recognize multiple geometric components and perform spatial geometric operations within the CAD program, leading to inaccurate reviews. In this paper, we propose the CAD program repairer (ReCAD) framework to effectively detect program errors and provide helpful feedback on error correction. Additionally, we create a dataset, CADReview, consisting of over 20K program-image pairs, with diverse errors for the CAD review task. Extensive experiments demonstrate that our ReCAD significantly outperforms existing MLLMs, which shows great potential in design applications.

[Arxiv](https://arxiv.org/abs/2505.22304)