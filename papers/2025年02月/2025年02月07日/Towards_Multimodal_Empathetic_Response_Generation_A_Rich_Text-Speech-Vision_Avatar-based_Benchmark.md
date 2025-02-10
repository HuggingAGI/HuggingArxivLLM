# 探索多模态共情响应生成：基于丰富文本、语音与视觉的虚拟形象基准测试

发布时间：2025年02月07日

`LLM应用

摘要讨论了如何利用多模态大型语言模型（MLLM）来提升情感响应生成的效果，属于将大型语言模型应用于实际任务的范畴。` `情感计算` `人机交互`

> Towards Multimodal Empathetic Response Generation: A Rich Text-Speech-Vision Avatar-based Benchmark

# 摘要

> 情感响应生成 (ERG) 是情感计算领域的重要任务，旨在为用户的查询生成富有同理心且细腻的回复。然而，现有的 ERG 研究大多局限于单一文本模态，这限制了其效果，因为人类情感的表达是多模态的。为了解决这一问题，我们提出了基于虚拟形象的多模态 ERG (MERG) 任务，整合了丰富的文本、语音和面部视觉信息。我们首先推出了一个大规模高质量的数据集——	extbf{AvaMERG}，它在传统文本 ERG 的基础上，加入了真实的人类语音音频和动态虚拟形象视频，覆盖了多样化的虚拟形象配置文件和广泛的现实场景主题。此外，我们开发了一个名为 	extbf{Empatheia} 的系统，专为 MERG 设计。Empatheia 基于一个多模态大型语言模型 (MLLM)，配备了多模态编码器、语音生成器和虚拟形象生成器，能够实现端到端的 MERG，并集成了同理心推理链机制，以提升情感理解和推理能力。最后，我们设计了一系列增强同理心的调整策略，强化了情感准确性和内容质量，以及跨模态的虚拟形象一致性。在 AvaMERG 数据集上的实验结果表明，Empatheia 在文本 ERG 和 MERG 方面均优于基线方法。总体而言，这项工作通过引入一个新颖的基准数据集和一个端到端的模型，将推动多模态情感响应生成研究的发展，为未来的研究奠定坚实基础。

> Empathetic Response Generation (ERG) is one of the key tasks of the affective computing area, which aims to produce emotionally nuanced and compassionate responses to user's queries. However, existing ERG research is predominantly confined to the singleton text modality, limiting its effectiveness since human emotions are inherently conveyed through multiple modalities. To combat this, we introduce an avatar-based Multimodal ERG (MERG) task, entailing rich text, speech, and facial vision information. We first present a large-scale high-quality benchmark dataset, \textbf{AvaMERG}, which extends traditional text ERG by incorporating authentic human speech audio and dynamic talking-face avatar videos, encompassing a diverse range of avatar profiles and broadly covering various topics of real-world scenarios. Further, we deliberately tailor a system, named \textbf{Empatheia}, for MERG. Built upon a Multimodal Large Language Model (MLLM) with multimodal encoder, speech and avatar generators, Empatheia performs end-to-end MERG, with Chain-of-Empathetic reasoning mechanism integrated for enhanced empathy understanding and reasoning. Finally, we devise a list of empathetic-enhanced tuning strategies, strengthening the capabilities of emotional accuracy and content, avatar-profile consistency across modalities. Experimental results on AvaMERG data demonstrate that Empatheia consistently shows superior performance than baseline methods on both textual ERG and MERG. Overall, this work is expected to pioneer the MERG research by introducing a novel benchmark and an end-to-end model, laying a solid foundation for future advancements in multimodal empathetic response generation.

[Arxiv](https://arxiv.org/abs/2502.04976)