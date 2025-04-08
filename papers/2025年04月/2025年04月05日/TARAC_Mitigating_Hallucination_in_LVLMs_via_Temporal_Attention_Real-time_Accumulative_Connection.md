# TARAC：借助时间注意力实时累积连接，有效缓解大语言模型中的幻觉现象

发布时间：2025年04月05日

`LLM应用` `计算机视觉` `多模态处理`

> TARAC: Mitigating Hallucination in LVLMs via Temporal Attention Real-time Accumulative Connection

# 摘要

> 大型视觉语言模型在各类任务中表现卓越，但幻觉问题却限制了其实际应用。幻觉问题源于多个因素：语言模型的固有幻觉倾向、视觉编码器的感知局限性，以及多模态数据带来的偏见。为应对这一挑战，研究者们提出了多种解决方案。例如，OPERA通过避免模型过度关注“锚点标记”来减少幻觉，而VCD则利用对比解码方法来缓解幻觉。本研究聚焦于图像标记注意力衰减与幻觉发生之间的关联。基于这一发现，我们提出了一种无需训练的创新方法——时间注意力实时累积连接（TARAC）。该方法能够在生成过程中动态累积和更新模型对图像标记的注意力。通过强化模型对图像标记的关注，TARAC有效缓解了因注意力衰减引发的幻觉问题。我们在多个模型和数据集上验证了TARAC的效能，结果表明该方法显著降低了幻觉的发生。具体而言，在CHAIR基准测试中，与VCD相比，TARAC将$C_S$降低了25.2，将$C_I$降低了8.7。


> Large Vision-Language Models have demonstrated remarkable performance across various tasks; however, the challenge of hallucinations constrains their practical applications. The hallucination problem arises from multiple factors, including the inherent hallucinations in language models, the limitations of visual encoders in perception, and biases introduced by multimodal data. Extensive research has explored ways to mitigate hallucinations. For instance, OPERA prevents the model from overly focusing on "anchor tokens", thereby reducing hallucinations, whereas VCD mitigates hallucinations by employing a contrastive decoding approach. In this paper, we investigate the correlation between the decay of attention to image tokens and the occurrence of hallucinations. Based on this finding, we propose Temporal Attention Real-time Accumulative Connection (TARAC), a novel training-free method that dynamically accumulates and updates LVLMs' attention on image tokens during generation. By enhancing the model's attention to image tokens, TARAC mitigates hallucinations caused by the decay of attention on image tokens. We validate the effectiveness of TARAC across multiple models and datasets, demonstrating that our approach substantially mitigates hallucinations. In particular, TARAC reduces $C_S$ by 25.2 and $C_I$ by 8.7 compared to VCD on the CHAIR benchmark.

[Arxiv](https://arxiv.org/abs/2504.04099)