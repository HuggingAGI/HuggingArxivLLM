# GraPE：一种用于组合式 T2I 合成的生成-规划-编辑框架

发布时间：2024年12月08日

`LLM应用` `图像生成` `文本处理`

> GraPE: A Generate-Plan-Edit Framework for Compositional T2I Synthesis

# 摘要

> 文本到图像（T2I）生成借助扩散模型取得了显著进步，能够依据文本提示生成逼真的图像。然而，现有方法在遵循复杂文本提示，尤其是那些需要组合和多步推理的提示时，仍面临挑战。面对如此复杂的指令，最先进的模型在如实建模对象属性及它们之间的关系时常常出错。在本项工作中，我们为 T2I 合成提出了一种替代模式，将复杂的多步生成任务分解为三步：（a）生成：首先利用现有的扩散模型生成图像；（b）规划：借助多模态大型语言模型（MLLMs）识别生成图像中关于单个对象及其属性的错误，并以编辑计划的形式生成所需的一系列纠正步骤；（c）编辑：利用现有的文本引导图像编辑模型，在生成的图像上依次执行编辑计划，从而获得符合原始指令的所需图像。我们的方法优势在于其本质上是模块化的、无需训练，且能应用于任何图像生成和编辑模型的组合。作为额外贡献，我们还开发了一种能够进行组合编辑的模型，进一步提升了所提方法的整体准确性。我们的方法灵活地在组合文本提示的性能和推理时间计算之间进行权衡。我们在 3 个基准和 10 个 T2I 模型（包括 DALLE-3 和最新的 -- SD-3.5-Large）上开展了广泛的实验评估。我们的方法不仅将最先进模型的性能提升了多达 3 个点，还缩小了较弱和较强模型之间的性能差距。$\href{https://dair-iitd.github.io/GraPE/}{https://dair-iitd.github.io/GraPE/}$

> Text-to-image (T2I) generation has seen significant progress with diffusion models, enabling generation of photo-realistic images from text prompts. Despite this progress, existing methods still face challenges in following complex text prompts, especially those requiring compositional and multi-step reasoning. Given such complex instructions, SOTA models often make mistakes in faithfully modeling object attributes, and relationships among them. In this work, we present an alternate paradigm for T2I synthesis, decomposing the task of complex multi-step generation into three steps, (a) Generate: we first generate an image using existing diffusion models (b) Plan: we make use of Multi-Modal LLMs (MLLMs) to identify the mistakes in the generated image expressed in terms of individual objects and their properties, and produce a sequence of corrective steps required in the form of an edit-plan. (c) Edit: we make use of an existing text-guided image editing models to sequentially execute our edit-plan over the generated image to get the desired image which is faithful to the original instruction. Our approach derives its strength from the fact that it is modular in nature, is training free, and can be applied over any combination of image generation and editing models. As an added contribution, we also develop a model capable of compositional editing, which further helps improve the overall accuracy of our proposed approach. Our method flexibly trades inference time compute with performance on compositional text prompts. We perform extensive experimental evaluation across 3 benchmarks and 10 T2I models including DALLE-3 and the latest -- SD-3.5-Large. Our approach not only improves the performance of the SOTA models, by upto 3 points, it also reduces the performance gap between weaker and stronger models. $\href{https://dair-iitd.github.io/GraPE/}{https://dair-iitd.github.io/GraPE/}$

[Arxiv](https://arxiv.org/abs/2412.06089)