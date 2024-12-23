# HoVLE：以整体视觉语言嵌入释放单片视觉语言模型的强大力量

发布时间：2024年12月20日

`LLM应用` `计算机视觉`

> HoVLE: Unleashing the Power of Monolithic Vision-Language Models with Holistic Vision-Language Embedding

# 摘要

> 大型语言模型（LLMs）的迅猛发展推动了视觉语言模型（VLMs）的进步。单片式VLMs避开了特定模态的编码器，为组合式模型提供了颇具前景的替代选择，然而却面临性能欠佳的难题。现有的多数单片式VLMs需要对预训练的LLMs进行调整以获取视觉能力，这或许会削弱其语言能力。为应对这一困境，本文推出了一款名为HoVLE的新型高性能单片式VLM。我们发现，当图像嵌入与文本嵌入相匹配时，LLMs已具备解读图像的能力。当前单片式VLMs的挑战实则在于缺少针对视觉和语言输入的整体性嵌入模块。故而，HoVLE引入了一个整体性嵌入模块，将视觉和文本输入转化至一个共享空间，让LLMs能够像处理文本一样处理图像。此外，还精心规划了一个多阶段训练策略来强化整体性嵌入模块。首先对其进行训练，从预训练的视觉编码器中提取视觉特征，从LLM中提取文本嵌入，从而能够利用未配对的随机图像和文本标记开展大规模训练。整个模型还在多模态数据上进行下一个标记预测，以对齐嵌入。最后，融入了指令调整阶段。我们的实验表明，HoVLE在各类基准测试中的表现接近领先的组合模型，大幅超越以往的单片式模型。模型可在https://huggingface.co/OpenGVLab/HoVLE获取。

> The rapid advance of Large Language Models (LLMs) has catalyzed the development of Vision-Language Models (VLMs). Monolithic VLMs, which avoid modality-specific encoders, offer a promising alternative to the compositional ones but face the challenge of inferior performance. Most existing monolithic VLMs require tuning pre-trained LLMs to acquire vision abilities, which may degrade their language capabilities. To address this dilemma, this paper presents a novel high-performance monolithic VLM named HoVLE. We note that LLMs have been shown capable of interpreting images, when image embeddings are aligned with text embeddings. The challenge for current monolithic VLMs actually lies in the lack of a holistic embedding module for both vision and language inputs. Therefore, HoVLE introduces a holistic embedding module that converts visual and textual inputs into a shared space, allowing LLMs to process images in the same way as texts. Furthermore, a multi-stage training strategy is carefully designed to empower the holistic embedding module. It is first trained to distill visual features from a pre-trained vision encoder and text embeddings from the LLM, enabling large-scale training with unpaired random images and text tokens. The whole model further undergoes next-token prediction on multi-modal data to align the embeddings. Finally, an instruction-tuning stage is incorporated. Our experiments show that HoVLE achieves performance close to leading compositional models on various benchmarks, outperforming previous monolithic models by a large margin. Model available at https://huggingface.co/OpenGVLab/HoVLE.

[Arxiv](https://arxiv.org/abs/2412.16158)