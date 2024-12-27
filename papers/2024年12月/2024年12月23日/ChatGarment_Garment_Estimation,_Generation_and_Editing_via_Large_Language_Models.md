# ChatGarment：借助大型语言模型实现服装估计、生成与编辑

发布时间：2024年12月23日

`LLM应用`

> ChatGarment: Garment Estimation, Generation and Editing via Large Language Models

# 摘要

> 我们推出了 ChatGarment 这一创新方法，它借助大型视觉语言模型（VLMs），能够自动依据图像或文本描述来估算、生成和编辑 3D 服装。以往的方法在实际场景中表现欠佳，或缺乏交互编辑功能，而 ChatGarment 能够在交互式对话中，从野外图像或草图估算缝纫模式，依据文本描述生成缝纫模式，并按照用户指令编辑服装。这些缝纫模式能够制成易于动画化和模拟的 3D 服装。这是通过微调 VLM 直接生成包含服装类型和风格的文本描述以及连续数值属性的 JSON 文件来达成的。随后，该 JSON 文件通过编程参数模型用于创建缝纫模式。为此，我们对现有的编程模型 GarmentCode 进行了优化，扩大了服装类型的覆盖范围，简化了结构，以利于 VLM 的高效微调。此外，我们通过自动化数据管道构建了大规模的图像到缝纫模式和文本到缝纫模式的数据集。大量评估显示，ChatGarment 能够从多模态输入中精准地重建、生成和编辑服装，凸显了其在时尚和游戏应用中变革工作流程的潜力。代码和数据可在 https://chatgarment.github.io/ 获取。

> We introduce ChatGarment, a novel approach that leverages large vision-language models (VLMs) to automate the estimation, generation, and editing of 3D garments from images or text descriptions. Unlike previous methods that struggle in real-world scenarios or lack interactive editing capabilities, ChatGarment can estimate sewing patterns from in-the-wild images or sketches, generate them from text descriptions, and edit garments based on user instructions, all within an interactive dialogue. These sewing patterns can then be draped into 3D garments, which are easily animatable and simulatable. This is achieved by finetuning a VLM to directly generate a JSON file that includes both textual descriptions of garment types and styles, as well as continuous numerical attributes. This JSON file is then used to create sewing patterns through a programming parametric model. To support this, we refine the existing programming model, GarmentCode, by expanding its garment type coverage and simplifying its structure for efficient VLM fine-tuning. Additionally, we construct a large-scale dataset of image-to-sewing-pattern and text-to-sewing-pattern pairs through an automated data pipeline. Extensive evaluations demonstrate ChatGarment's ability to accurately reconstruct, generate, and edit garments from multimodal inputs, highlighting its potential to revolutionize workflows in fashion and gaming applications. Code and data will be available at https://chatgarment.github.io/.

[Arxiv](https://arxiv.org/abs/2412.17811)