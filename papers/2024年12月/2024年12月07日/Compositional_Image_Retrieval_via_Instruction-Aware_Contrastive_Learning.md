# 借助指令感知对比学习实现组合图像检索

发布时间：2024年12月07日

`LLM应用` `图像检索` `多模态`

> Compositional Image Retrieval via Instruction-Aware Contrastive Learning

# 摘要

> 组合图像检索（CIR）指的是依据由图像与指明对视觉参考进行修改或变动的文本所组成的查询来检索目标图像。CIR 本质上属于指令遵循任务，因为模型得解读并将修改应用于图像。实际上，鉴于下游任务中带注释的数据稀缺，零样本组合图像检索（ZS-CIR）是人们所期望的。虽然基于 CLIP 的现有 ZS-CIR 模型已呈现出不错的成果，但其解读和遵循修改指令的能力依然有限。一些研究尝试通过融入大型语言模型（LLMs）来解决此问题。然而，这些方法在有效整合多模态信息和指令理解方面仍面临挑战。为应对上述挑战，我们提出一种新颖的嵌入方法，借助经指令调整的多模态大型语言模型（MLLM）生成组合表示，显著增强了图像与指令全面整合的指令遵循能力。但直接应用 MLLM 带来了新难题，因为 MLLM 主要是为文本生成设计的，而非 CIR 所需的嵌入提取。为解决这一问题，我们引入了两阶段训练策略，以高效学习联合多模态嵌入空间，并通过在类似 CIR 格式的三元组数据集中调整模型，进一步提升遵循修改指令的能力。在 FashionIQ、CIRR、GeneCIS 和 CIRCO 这四个公共数据集上开展的大量实验表明，我们的模型性能卓越，大幅优于最先进的基线。代码可在 GitHub 仓库获取。

> Composed Image Retrieval (CIR) involves retrieving a target image based on a composed query of an image paired with text that specifies modifications or changes to the visual reference. CIR is inherently an instruction-following task, as the model needs to interpret and apply modifications to the image. In practice, due to the scarcity of annotated data in downstream tasks, Zero-Shot CIR (ZS-CIR) is desirable. While existing ZS-CIR models based on CLIP have shown promising results, their capability in interpreting and following modification instructions remains limited. Some research attempts to address this by incorporating Large Language Models (LLMs). However, these approaches still face challenges in effectively integrating multimodal information and instruction understanding. To tackle above challenges, we propose a novel embedding method utilizing an instruction-tuned Multimodal LLM (MLLM) to generate composed representation, which significantly enhance the instruction following capability for a comprehensive integration between images and instructions. Nevertheless, directly applying MLLMs introduces a new challenge since MLLMs are primarily designed for text generation rather than embedding extraction as required in CIR. To address this, we introduce a two-stage training strategy to efficiently learn a joint multimodal embedding space and further refining the ability to follow modification instructions by tuning the model in a triplet dataset similar to the CIR format. Extensive experiments on four public datasets: FashionIQ, CIRR, GeneCIS, and CIRCO demonstrates the superior performance of our model, outperforming state-of-the-art baselines by a significant margin. Codes are available at the GitHub repository.

[Arxiv](https://arxiv.org/abs/2412.05756)