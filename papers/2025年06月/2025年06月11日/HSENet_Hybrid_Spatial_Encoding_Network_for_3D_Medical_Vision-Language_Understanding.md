# HSENet: 三维医学视觉-语言理解的混合空间编码网络

发布时间：2025年06月11日

`LLM应用` `医学影像`

> HSENet: Hybrid Spatial Encoding Network for 3D Medical Vision-Language Understanding

# 摘要

> 自动化3D CT诊断使临床医生能够及时做出基于证据的决策，同时提升诊断准确性和工作流程效率。尽管多模态大型语言模型（MLLMs）在视觉-语言理解方面表现优异，但现有方法主要针对2D医学图像，这从根本上限制了它们捕捉复杂3D解剖结构的能力。这种局限性常常导致对细微病理的误判，进而引发诊断幻觉。本文提出了一种名为Hybrid Spatial Encoding Network（HSENet）的框架，通过有效利用增强的3D医学视觉线索，实现准确且稳健的视觉-语言理解。HSENet采用双3D视觉编码器，能够同时感知全局体积上下文和精细的解剖细节，这些编码器通过与诊断报告的双阶段对齐进行预训练。此外，我们提出了Spatial Packer，一个高效的多模态投影器，它通过基于质心的压缩，将高分辨率的3D空间区域压缩成一组信息丰富的视觉令牌。通过将Spatial Packer与双3D视觉编码器结合，HSENet能够无缝感知并传递混合视觉表示到大型语言模型的语义空间，从而实现精准的诊断文本生成。实验结果表明，我们的方法在3D语言-视觉检索（R@100达到39.85%，提升5.96%）、3D医学报告生成（BLEU-4达到24.01%，提升8.01%）和3D视觉问答（主要类别准确率达到73.60%，提升1.99%）方面均达到了当前最优性能，充分证明了其有效性。代码已开源，地址为https://github.com/YanzhaoShi/HSENet。


> Automated 3D CT diagnosis empowers clinicians to make timely, evidence-based decisions by enhancing diagnostic accuracy and workflow efficiency. While multimodal large language models (MLLMs) exhibit promising performance in visual-language understanding, existing methods mainly focus on 2D medical images, which fundamentally limits their ability to capture complex 3D anatomical structures. This limitation often leads to misinterpretation of subtle pathologies and causes diagnostic hallucinations. In this paper, we present Hybrid Spatial Encoding Network (HSENet), a framework that exploits enriched 3D medical visual cues by effective visual perception and projection for accurate and robust vision-language understanding. Specifically, HSENet employs dual-3D vision encoders to perceive both global volumetric contexts and fine-grained anatomical details, which are pre-trained by dual-stage alignment with diagnostic reports. Furthermore, we propose Spatial Packer, an efficient multimodal projector that condenses high-resolution 3D spatial regions into a compact set of informative visual tokens via centroid-based compression. By assigning spatial packers with dual-3D vision encoders, HSENet can seamlessly perceive and transfer hybrid visual representations to LLM's semantic space, facilitating accurate diagnostic text generation. Experimental results demonstrate that our method achieves state-of-the-art performance in 3D language-visual retrieval (39.85% of R@100, +5.96% gain), 3D medical report generation (24.01% of BLEU-4, +8.01% gain), and 3D visual question answering (73.60% of Major Class Accuracy, +1.99% gain), confirming its effectiveness. Our code is available at https://github.com/YanzhaoShi/HSENet.

[Arxiv](https://arxiv.org/abs/2506.09634)