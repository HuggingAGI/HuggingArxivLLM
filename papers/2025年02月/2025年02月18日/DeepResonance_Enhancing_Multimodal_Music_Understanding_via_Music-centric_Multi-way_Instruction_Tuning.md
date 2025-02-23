# DeepResonance：通过以音乐为中心的多路指令微调提升多模态音乐理解能力

发布时间：2025年02月18日

`LLM应用` `多模态`

> DeepResonance: Enhancing Multimodal Music Understanding via Music-centric Multi-way Instruction Tuning

# 摘要

> 近期，音乐大语言模型（LLMs）的进步显著推动了音乐理解任务的发展，特别是在整合音乐与文本输入方面。然而，将图像、视频和文本化音乐特征等额外模态纳入音乐理解的潜力尚未被探索。为填补这一空白，我们提出DeepResonance，这是一个通过多路指令调优，利用多路对齐的音乐、文本、图像和视频数据进行微调的多模态音乐理解大语言模型。为此，我们构建了Music4way-MI2T、Music4way-MV2T和Music4way-Any2T这三个4路训练和评估数据集，旨在使DeepResonance能够整合视觉和文本化的音乐特征内容。我们还引入了多采样ImageBind嵌入和预对齐Transformer，以增强模态融合，使其在输入文本LLMs之前更高效，从而为多路指令调优量身定制DeepResonance。我们的模型在六项音乐理解任务中实现了最先进的性能，凸显了辅助模态的优势以及DeepResonance的结构优越性。我们计划开源这些模型和新构建的数据集。

> Recent advancements in music large language models (LLMs) have significantly improved music understanding tasks, which involve the model's ability to analyze and interpret various musical elements. These improvements primarily focused on integrating both music and text inputs. However, the potential of incorporating additional modalities such as images, videos and textual music features to enhance music understanding remains unexplored. To bridge this gap, we propose DeepResonance, a multimodal music understanding LLM fine-tuned via multi-way instruction tuning with multi-way aligned music, text, image, and video data. To this end, we construct Music4way-MI2T, Music4way-MV2T, and Music4way-Any2T, three 4-way training and evaluation datasets designed to enable DeepResonance to integrate both visual and textual music feature content. We also introduce multi-sampled ImageBind embeddings and a pre-alignment Transformer to enhance modality fusion prior to input into text LLMs, tailoring DeepResonance for multi-way instruction tuning. Our model achieves state-of-the-art performances across six music understanding tasks, highlighting the benefits of the auxiliary modalities and the structural superiority of DeepResonance. We plan to open-source the models and the newly constructed datasets.

[Arxiv](https://arxiv.org/abs/2502.12623)