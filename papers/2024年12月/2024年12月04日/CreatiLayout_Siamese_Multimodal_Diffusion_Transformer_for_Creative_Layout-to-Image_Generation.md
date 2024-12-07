# CreatiLayout：用于实现创意布局到图像生成的连体多模态扩散变压器

发布时间：2024年12月04日

`LLM应用` `图像生成` `多模态`

> CreatiLayout: Siamese Multimodal Diffusion Transformer for Creative Layout-to-Image Generation

# 摘要

> 扩散模型因能生成视觉迷人且艺术品质高的图像而备受认可。于是，布局到图像（L2I）生成应运而生，旨在借助特定区域的位置和描述，实现更精准、可控的生成。然而，过往方法多聚焦于基于 UNet 的模型（如 SD1.5 和 SDXL），对具备强大图像生成能力的多模态扩散变压器（MM-DiTs）探索有限。让 MM-DiT 用于布局到图像生成看似容易，实则因布局引入、整合及在多模态间平衡的复杂性而颇具挑战。为此，我们探索了多种网络变体，以将布局引导有效融入 MM-DiT，最终推出 SiamLayout。为承袭 MM-DiT 的优势，我们使用单独一组网络权重处理布局，将其与图像和文本模态同等看待。同时，为缓解模态间的竞争，我们把图像 - 布局交互解耦到与图像 - 文本并列的连体分支中，后期再进行融合。此外，我们贡献了一个大规模布局数据集，名为 LayoutSAM，包含 270 万对图像 - 文本和 1070 万个实体。每个实体都配有一个边界框和详细描述。我们还构建了 LayoutSAM-Eval 基准，作为评估 L2I 生成质量的综合工具。最后，我们引入了布局设计师，挖掘了大型语言模型在布局规划方面的潜力，使其成为布局生成与优化的专家。我们的代码、模型和数据集可在 https://creatilayout.github.io 获取。

> Diffusion models have been recognized for their ability to generate images that are not only visually appealing but also of high artistic quality. As a result, Layout-to-Image (L2I) generation has been proposed to leverage region-specific positions and descriptions to enable more precise and controllable generation. However, previous methods primarily focus on UNet-based models (e.g., SD1.5 and SDXL), and limited effort has explored Multimodal Diffusion Transformers (MM-DiTs), which have demonstrated powerful image generation capabilities. Enabling MM-DiT for layout-to-image generation seems straightforward but is challenging due to the complexity of how layout is introduced, integrated, and balanced among multiple modalities. To this end, we explore various network variants to efficiently incorporate layout guidance into MM-DiT, and ultimately present SiamLayout. To Inherit the advantages of MM-DiT, we use a separate set of network weights to process the layout, treating it as equally important as the image and text modalities. Meanwhile, to alleviate the competition among modalities, we decouple the image-layout interaction into a siamese branch alongside the image-text one and fuse them in the later stage. Moreover, we contribute a large-scale layout dataset, named LayoutSAM, which includes 2.7 million image-text pairs and 10.7 million entities. Each entity is annotated with a bounding box and a detailed description. We further construct the LayoutSAM-Eval benchmark as a comprehensive tool for evaluating the L2I generation quality. Finally, we introduce the Layout Designer, which taps into the potential of large language models in layout planning, transforming them into experts in layout generation and optimization. Our code, model, and dataset will be available at https://creatilayout.github.io.

[Arxiv](https://arxiv.org/abs/2412.03859)