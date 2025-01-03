# 基于多模态与多阶段分析的视频缩略图自动选择与生成

发布时间：2024年10月18日

`LLM应用

**理由**：该论文主要讨论了如何利用大型语言模型（LLM）和视觉变换器等技术来自动化视频缩略图的选择和生成。虽然论文涉及多种技术，但其核心应用场景是利用LLM来确保语义一致性，并与其他模型结合使用。因此，这篇论文应归类为LLM应用。` `视频处理`

> Automating Video Thumbnails Selection and Generation with Multimodal and Multistage Analysis

# 摘要

> 本论文提出了一种创新的方法，用于自动化传统广播内容的视频缩略图选择。我们的方法为多样化、代表性和美观的缩略图设定了严格标准，考虑了标志放置空间、垂直宽高比、面部身份和情感识别等因素。我们引入了一个复杂的多阶段管道，可以选择候选帧或通过混合视频元素或使用扩散模型生成新图像。该管道结合了多种先进模型，包括下采样、冗余减少、自动裁剪、面部识别、闭眼和情感检测、镜头比例和美学预测、分割、抠图和协调。它还利用大型语言模型和视觉变换器确保语义一致性。一个GUI工具便于快速浏览管道输出。为评估方法，我们进行了全面实验。在69个视频的研究中，53.6%的我们提出的集合包含了专业设计师选择的缩略图，73.9%包含了类似图像。一项对82名参与者的调查显示，45.77%的人更喜欢我们的方法，而37.99%的人喜欢手动选择的缩略图，16.36%的人喜欢另一种方法。专业设计师报告称，与另一种方法相比，有效候选者增加了3.57倍，证实了我们的方法符合既定标准。总之，我们的研究结果证实，所提出的方法在保持高质量标准的同时加速了缩略图的创建，并促进了更大的用户参与度。

> This thesis presents an innovative approach to automate video thumbnail selection for traditional broadcast content. Our methodology establishes stringent criteria for diverse, representative, and aesthetically pleasing thumbnails, considering factors like logo placement space, incorporation of vertical aspect ratios, and accurate recognition of facial identities and emotions. We introduce a sophisticated multistage pipeline that can select candidate frames or generate novel images by blending video elements or using diffusion models. The pipeline incorporates state-of-the-art models for various tasks, including downsampling, redundancy reduction, automated cropping, face recognition, closed-eye and emotion detection, shot scale and aesthetic prediction, segmentation, matting, and harmonization. It also leverages large language models and visual transformers for semantic consistency. A GUI tool facilitates rapid navigation of the pipeline's output. To evaluate our method, we conducted comprehensive experiments. In a study of 69 videos, 53.6% of our proposed sets included thumbnails chosen by professional designers, with 73.9% containing similar images. A survey of 82 participants showed a 45.77% preference for our method, compared to 37.99% for manually chosen thumbnails and 16.36% for an alternative method. Professional designers reported a 3.57-fold increase in valid candidates compared to the alternative method, confirming that our approach meets established criteria. In conclusion, our findings affirm that the proposed method accelerates thumbnail creation while maintaining high-quality standards and fostering greater user engagement.

[Arxiv](https://arxiv.org/abs/2410.19825)