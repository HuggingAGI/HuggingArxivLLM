# GeneMAN：基于多源人类数据实现通用的单图像 3D 人体重建

发布时间：2024年11月27日

`其他` `计算机视觉` `3D 重建`

> GeneMAN: Generalizable Single-Image 3D Human Reconstruction from Multi-Source Human Data

# 摘要

> 摘要：给定一张野外单人照，重建高保真 3D 人体模型是个艰巨任务。现有方法面临不少难题，比如：a）野外人体图像所捕捉的身体比例各异；b）拍摄范围内个人物品繁杂；c）人体姿势模糊、人体纹理不一致。而且，高质量人体数据的稀缺让挑战加剧。为应对这些问题，我们提出一个通用的图像到 3D 人体重建框架，名为 GeneMAN，它基于包括 3D 扫描、多视角视频、单张照片以及我们生成的合成人体数据等高质量人体数据的综合多源集合。GeneMAN 涵盖三个关键模块。1）不依赖参数化人体模型（如 SMPL），GeneMAN 首先训练一个针对人体的文本到图像扩散模型和一个视图条件扩散模型，分别作为 GeneMAN 的 2D 人体先验和 3D 人体先验用于重建。2）借助预训练的人体先验模型，利用几何初始化与雕刻管道，从单张图像中恢复高质量的 3D 人体几何形状。3）为达成高保真的 3D 人体纹理，GeneMAN 采用多空间纹理细化管道，在潜在空间和像素空间中持续细化纹理。大量实验结果表明，GeneMAN 能从单张图像输入生成高质量 3D 人体模型，超越先前的最先进方法。值得一提的是，GeneMAN 在处理野外图像时通用性更强，不管输入图像中的身体比例怎样，通常都能生成自然姿势且带有常见物品的高质量 3D 人体模型。

> 
Abstract:Given a single in-the-wild human photo, it remains a challenging task to reconstruct a high-fidelity 3D human model. Existing methods face difficulties including a) the varying body proportions captured by in-the-wild human images; b) diverse personal belongings within the shot; and c) ambiguities in human postures and inconsistency in human textures. In addition, the scarcity of high-quality human data intensifies the challenge. To address these problems, we propose a Generalizable image-to-3D huMAN reconstruction framework, dubbed GeneMAN, building upon a comprehensive multi-source collection of high-quality human data, including 3D scans, multi-view videos, single photos, and our generated synthetic human data. GeneMAN encompasses three key modules. 1) Without relying on parametric human models (e.g., SMPL), GeneMAN first trains a human-specific text-to-image diffusion model and a view-conditioned diffusion model, serving as GeneMAN 2D human prior and 3D human prior for reconstruction, respectively. 2) With the help of the pretrained human prior models, the Geometry Initialization-&-Sculpting pipeline is leveraged to recover high-quality 3D human geometry given a single image. 3) To achieve high-fidelity 3D human textures, GeneMAN employs the Multi-Space Texture Refinement pipeline, consecutively refining textures in the latent and the pixel spaces. Extensive experimental results demonstrate that GeneMAN could generate high-quality 3D human models from a single image input, outperforming prior state-of-the-art methods. Notably, GeneMAN could reveal much better generalizability in dealing with in-the-wild images, often yielding high-quality 3D human models in natural poses with common items, regardless of the body proportions in the input images.
    

[Arxiv](https://arxiv.org/pdf/2411.18624)