# CLIP-SLA: 一种用于连续手语识别的参数高效 CLIP 适配方法

发布时间：2025年04月02日

`LLM应用` `手语识别` `计算机视觉`

> CLIP-SLA: Parameter-Efficient CLIP Adaptation for Continuous Sign Language Recognition

# 摘要

> # 连续手语识别研究
连续手语识别（CSLR）专注于从视频中解读并转录手语手势序列。我们提出了一种全新的CSLR框架——CLIP-SLA（CLIP手语适应），该框架通过参数高效微调（PEFT）将CLIP模型的强大视觉编码器应用于手语任务。我们设计了两种变体SLA-Adapter和SLA-LoRA，通过在CLIP视觉编码器中嵌入PEFT模块，实现了仅需少量可训练参数的高效微调。

在Phoenix2014、Phoenix2014-T、CSL-Daily和Isharah-500四个数据集上的实验结果表明，CLIP-SLA的两种变体均以更少的可训练参数超越了多个当前最优模型。通过广泛的消融实验，我们进一步验证了所提方法在不同视觉-语言模型中的有效性和灵活性。这些研究成果凸显了大规模预训练模型在可扩展和高效CSLR中的巨大潜力，为未来手语理解技术的发展奠定了坚实基础。


> Continuous sign language recognition (CSLR) focuses on interpreting and transcribing sequences of sign language gestures in videos. In this work, we propose CLIP sign language adaptation (CLIP-SLA), a novel CSLR framework that leverages the powerful pre-trained visual encoder from the CLIP model to sign language tasks through parameter-efficient fine-tuning (PEFT). We introduce two variants, SLA-Adapter and SLA-LoRA, which integrate PEFT modules into the CLIP visual encoder, enabling fine-tuning with minimal trainable parameters. The effectiveness of the proposed frameworks is validated on four datasets: Phoenix2014, Phoenix2014-T, CSL-Daily, and Isharah-500, where both CLIP-SLA variants outperformed several SOTA models with fewer trainable parameters. Extensive ablation studies emphasize the effectiveness and flexibility of the proposed methods with different vision-language models for CSLR. These findings showcase the potential of adapting large-scale pre-trained models for scalable and efficient CSLR, which pave the way for future advancements in sign language understanding.

[Arxiv](https://arxiv.org/abs/2504.01666)