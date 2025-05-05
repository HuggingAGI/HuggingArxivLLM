# 基于指令的细粒度对象属性编辑——InstructAttribute方法

发布时间：2025年04月30日

`LLM应用` `图像生成` `图像编辑`

> InstructAttribute: Fine-grained Object Attributes editing with Instruction

# 摘要

> 文本到图像（T2I）扩散模型以其卓越的生成能力在图像编辑领域得到了广泛应用，但实现对精细属性的精准控制仍具挑战。现有方法要么无法修改物体属性，要么难以保持结构一致。为此，我们提出了无需训练的结构保留与属性增强（SPAA）方法，通过编辑自注意力图和交叉注意力值，实现了对物体颜色和材质的精准控制。我们还构建了涵盖各类物体颜色与材质的属性数据集，并整合多模态大型语言模型（MLLM）开发了自动化数据处理与标注管道。基于此数据集，我们推出了基于指令的InstructAttribute模型，专注于精细的颜色与材质编辑。实验结果表明，我们的方法在物体级别颜色和材质编辑上超越了现有基于指令的方法，展现了显著优势。

> Text-to-image (T2I) diffusion models, renowned for their advanced generative abilities, are extensively utilized in image editing applications, demonstrating remarkable effectiveness. However, achieving precise control over fine-grained attributes still presents considerable challenges. Existing image editing techniques either fail to modify the attributes of an object or struggle to preserve its structure and maintain consistency in other areas of the image. To address these challenges, we propose the Structure-Preserving and Attribute Amplification (SPAA), a training-free method which enables precise control over the color and material transformations of objects by editing the self-attention maps and cross-attention values. Furthermore, we constructed the Attribute Dataset, which encompasses nearly all colors and materials associated with various objects, by integrating multimodal large language models (MLLM) to develop an automated pipeline for data filtering and instruction labeling. Training on this dataset, we present our InstructAttribute, an instruction-based model designed to facilitate fine-grained editing of color and material attributes. Extensive experiments demonstrate that our method achieves superior performance in object-level color and material editing, outperforming existing instruction-based image editing approaches.

[Arxiv](https://arxiv.org/abs/2505.00751)