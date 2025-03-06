# 从建筑草图到概念表示：利用结构感知的扩散模型生成学校建筑渲染图

发布时间：2025年03月04日

`LLM应用` `建筑设计` `建筑图像生成`

> From Architectural Sketch to Conceptual Representation: Using Structure-Aware Diffusion Model to Generate Renderings of School Buildings

# 摘要

> 生成式人工智能（AI）的快速发展使我们能够从建筑草图生成效果图，显著提升了建筑设计初期阶段的沟通和概念表达效率。然而，生成的图像常常缺乏建筑师草图中的结构细节。虽然草图通常强调整体结构，但门窗等关键组件往往仅用简单的线条表示或完全省略。对于学校建筑而言，控制建筑组件（如窗户的形状和比例）至关重要，因为这些因素直接影响生成图像准确反映建筑师设计意图的能力。为了解决这一问题，我们提出了一种结构感知的扩散模型，用于建筑图像生成，通过检索增强来细化设计意图的表达。我们的框架利用建筑组件来提升生成过程，弥补草图中可能缺乏的细节。这些组件提供了清晰的空间和结构细节，增强了模型对建筑细节的解读和生成能力。经过细化的草图结合文本提示，输入到提出的结构感知扩散模型中，生成详细且逼真的学校建筑图像。实验结果证明了我们的框架在生成建筑设计方面的有效性。

> Generative Artificial Intelligence (AI) has advanced rapidly, enabling the generation of renderings from architectural sketches. This progress has significantly improved the efficiency of communication and conceptual expression during the early stage of architectural design. However, generated images often lack the structural details from architects' sketches. While sketches typically emphasize the overall structure, crucial components such as windows and doors are often represented by simple lines or omitted entirely. For school buildings, it is essential to control architectural components, such as the shape and proportion of windows, as these factors directly influence the accuracy of the generated images in reflecting the architect's design intentions. To address this issue, we propose a structure-aware diffusion model for architectural image generation to refine expressing design intentions through retrieval augmentation. Our framework utilizes architectural components to enhance the generation process, addressing the details that may be lacking in the sketches. These components provide clear spatial and structural details, improving the model's ability to interpret and generate architectural details. The refined sketches, combined with text prompts, are fed into the proposed structure-aware diffusion model to generate detailed and realistic school building images. The experiment results demonstrate the effectiveness of our framework in generating architectural designs.

[Arxiv](https://arxiv.org/abs/2503.03090)