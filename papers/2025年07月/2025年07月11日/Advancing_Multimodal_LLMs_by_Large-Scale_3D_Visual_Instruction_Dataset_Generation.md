# 大规模3D视觉指令数据集生成助力多模态LLMs发展

发布时间：2025年07月11日

`LLM应用` `计算机视觉` `数据科学`

> Advancing Multimodal LLMs by Large-Scale 3D Visual Instruction Dataset Generation

# 摘要

> 多模态大型语言模型（MLLMs）在捕捉摄像头与物体关系时面临挑战，尤其在物体朝向、视角和镜头拍摄上表现不足。这主要是因为现有MLLMs的训练数据中，摄像头-物体关系的多样性有限，且缺乏对应的详细文本描述。为解决这一问题，我们提出了一种合成生成流水线，用于创建大规模3D视觉指令数据集。我们的框架通过3D资产生成数据，并结合渲染和扩散模型，生产保留精确摄像头-物体关系的逼真图像。同时，我们还利用大型语言模型生成文本提示，用于指导视觉指令微调和图像生成。我们构建了包含24万VQA样本的Ultimate3D数据集，每个样本都配有精确的摄像头-物体标注，并提供了基准测试。在该数据集上微调的MLLMs性能显著提升，在摄像头-物体关系识别任务中平均准确率提高了33.4%。我们的代码、数据集和基准测试将为MLLM的广泛应用提供支持。

> Multimodal Large Language Models (MLLMs) struggle with accurately capturing camera-object relations, especially for object orientation, camera viewpoint, and camera shots. This stems from the fact that existing MLLMs are trained on images with limited diverse camera-object relations and corresponding textual descriptions. To address this, we propose a synthetic generation pipeline to create large-scale 3D visual instruction datasets. Our framework takes 3D assets as input and uses rendering and diffusion-based image generation models to create photorealistic images preserving precise camera-object relations. Additionally, large language models (LLMs) are used to generate text prompts for guiding visual instruction tuning and controlling image generation. We create Ultimate3D, a dataset of 240K VQAs with precise camera-object annotations, and corresponding benchmark. MLLMs fine-tuned on our proposed dataset outperform commercial models by a large margin, achieving an average accuracy improvement of 33.4% on camera-object relation recognition tasks. Our code, dataset, and benchmark will contribute to broad MLLM applications.

[Arxiv](https://arxiv.org/abs/2507.08513)