# # MathCoder-VL：连接视觉与代码，提升多模态数学推理能力
MathCoder-VL：架起视觉与代码的桥梁，助力多模态数学推理能力的提升。

发布时间：2025年05月15日

`LLM应用` `多模态`

> MathCoder-VL: Bridging Vision and Code for Enhanced Multimodal Mathematical Reasoning

# 摘要

> 目前，用于训练大型多模态模型的自然语言图像描述数据集主要关注自然场景，忽视了对解决问题至关重要的数学图形细节，这限制了当前LMMs在多模态数学推理方面的提升。为此，我们提出利用代码作为跨模态对齐的监督方法，因为代码天然包含了生成对应图形所需的所有信息，从而在图像和代码之间建立了精确的关联。具体而言，我们采用模型在环的方法，共同开发了图像到代码的模型FigCodifier和ImgCode-8.6M数据集，这是迄今为止最大的图像-代码数据集。此外，我们利用FigCodifier生成新的数学图形，并构建了高质量的多模态数学指令微调数据集MM-MathInstruct-3M。最终，我们推出了MathCoder-VL，它基于ImgCode-8.6M进行跨模态对齐，并在MM-MathInstruct-3M上进行微调以解决多模态数学问题。我们的模型在所有六个指标上都达到了新的开源最优性能。值得注意的是，在MathVista的几何问题解决子集上，它分别比GPT-4o和Claude 3.5 Sonnet提升了8.9%和9.2%。数据集和模型将在https://github.com/mathllm/MathCoder上发布。

> Natural language image-caption datasets, widely used for training Large Multimodal Models, mainly focus on natural scenarios and overlook the intricate details of mathematical figures that are critical for problem-solving, hindering the advancement of current LMMs in multimodal mathematical reasoning. To this end, we propose leveraging code as supervision for cross-modal alignment, since code inherently encodes all information needed to generate corresponding figures, establishing a precise connection between the two modalities. Specifically, we co-develop our image-to-code model and dataset with model-in-the-loop approach, resulting in an image-to-code model, FigCodifier and ImgCode-8.6M dataset, the largest image-code dataset to date. Furthermore, we utilize FigCodifier to synthesize novel mathematical figures and then construct MM-MathInstruct-3M, a high-quality multimodal math instruction fine-tuning dataset. Finally, we present MathCoder-VL, trained with ImgCode-8.6M for cross-modal alignment and subsequently fine-tuned on MM-MathInstruct-3M for multimodal math problem solving. Our model achieves a new open-source SOTA across all six metrics. Notably, it surpasses GPT-4o and Claude 3.5 Sonnet in the geometry problem-solving subset of MathVista, achieving improvements of 8.9% and 9.2%. The dataset and models will be released at https://github.com/mathllm/MathCoder.

[Arxiv](https://arxiv.org/abs/2505.10557)