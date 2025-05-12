# 层次化生成链用于复杂属性文本到3D生成

发布时间：2025年05月07日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLM）来解决复杂三维物体生成的问题。通过提出一种自动化方法，HCoG，该方法利用LLM将长描述分解为不同模块，并通过层级链生成结构连贯的三维对象。这表明LLM在三维建模中的具体应用，属于LLM应用的范畴。` `计算机图形学`

> Apply Hierarchical-Chain-of-Generation to Complex Attributes Text-to-3D Generation

# 摘要

> 尽管近期的文本到3D模型能够生成高质量的三维资产，但在处理具有复杂属性的物体时仍显力不从心。主要障碍在于：(1)现有方法通常将文本到图像模型提升，利用文本编码器提取语义信息，但文本编码器对长描述的理解能力有限，导致跨注意力焦点偏离，进而造成生成结果中属性绑定错误。(2)被遮挡的物体部分需要遵循严格的生成顺序并进行明确的部件解耦。尽管一些研究通过人工干预来缓解上述问题，但其生成质量不稳定且高度依赖人工信息。为解决这些问题，我们提出了一种自动化方法——分层生成链（HCoG）。该方法利用大型语言模型将长描述分解为代表不同物体部件的模块，并根据遮挡情况从内到外进行排序，形成层级链。在每个模块内，我们首先粗略创建组件，然后通过目标区域定位和对应的3D高斯核优化实现精准的属性绑定。在模块之间，我们引入高斯扩展和标签消除机制，通过扩展新的高斯核、重新分配语义标签并消除不必要的核，确保仅添加相关部分而不破坏已优化的部分。实验结果证实，HCoG能够生成结构连贯、属性忠实的复杂三维对象。代码可在https://github.com/Wakals/GASCOL获取。

> Recent text-to-3D models can render high-quality assets, yet they still stumble on objects with complex attributes. The key obstacles are: (1) existing text-to-3D approaches typically lift text-to-image models to extract semantics via text encoders, while the text encoder exhibits limited comprehension ability for long descriptions, leading to deviated cross-attention focus, subsequently wrong attribute binding in generated results. (2) Occluded object parts demand a disciplined generation order and explicit part disentanglement. Though some works introduce manual efforts to alleviate the above issues, their quality is unstable and highly reliant on manual information. To tackle above problems, we propose a automated method Hierarchical-Chain-of-Generation (HCoG). It leverages a large language model to decompose the long description into blocks representing different object parts, and orders them from inside out according to occlusions, forming a hierarchical chain. Within each block we first coarsely create components, then precisely bind attributes via target-region localization and corresponding 3D Gaussian kernel optimization. Between blocks, we introduce Gaussian Extension and Label Elimination to seamlessly generate new parts by extending new Gaussian kernels, re-assigning semantic labels, and eliminating unnecessary kernels, ensuring that only relevant parts are added without disrupting previously optimized parts. Experiments confirm that HCoG yields structurally coherent, attribute-faithful 3D objects with complex attributes. The code is available at https://github.com/Wakals/GASCOL .

[Arxiv](https://arxiv.org/abs/2505.05505)