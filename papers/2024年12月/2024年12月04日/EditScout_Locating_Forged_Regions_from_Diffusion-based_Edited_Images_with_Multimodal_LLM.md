# EditScout：借助多模态 LLM 从基于扩散的编辑图像里找出伪造区域

发布时间：2024年12月04日

`LLM应用` `图像编辑` `数字取证`

> EditScout: Locating Forged Regions from Diffusion-based Edited Images with Multimodal LLM

# 摘要

> 图像编辑技术是用于对图像进行转换、调整、删除或其他改动的工具。近期的研究大幅提升了图像编辑工具的性能，能够创造出逼真且富含语义信息的伪造区域，几乎与真实图像无异，这给数字取证和媒体可信度带来全新挑战。当前的图像取证技术虽能精准定位传统图像操作方法生成的伪造区域，但对于基于扩散技术生成的区域却难以定位。为了填补这一空缺，我们推出了一个创新框架，它融合了多模态大型语言模型（LLM）来增强推理能力，以定位由基于扩散模型的编辑方法所产生的图像篡改区域。借助LLM的上下文和语义优势，我们的框架在MagicBrush、AutoSplice和PerfBrush（新颖的基于扩散的数据集）等数据集上收获了令人期待的成果，在mIoU和F1分数等指标上超越了以往的方法。特别要指出的是，我们的方法在PerfBrush数据集上表现卓越，这是一个自行构建的测试集，包含了前所未见的编辑类型。在此，传统方法往往表现欠佳，得分极低，而我们的方法却展现出了良好的性能。

> Image editing technologies are tools used to transform, adjust, remove, or otherwise alter images. Recent research has significantly improved the capabilities of image editing tools, enabling the creation of photorealistic and semantically informed forged regions that are nearly indistinguishable from authentic imagery, presenting new challenges in digital forensics and media credibility. While current image forensic techniques are adept at localizing forged regions produced by traditional image manipulation methods, current capabilities struggle to localize regions created by diffusion-based techniques. To bridge this gap, we present a novel framework that integrates a multimodal Large Language Model (LLM) for enhanced reasoning capabilities to localize tampered regions in images produced by diffusion model-based editing methods. By leveraging the contextual and semantic strengths of LLMs, our framework achieves promising results on MagicBrush, AutoSplice, and PerfBrush (novel diffusion-based dataset) datasets, outperforming previous approaches in mIoU and F1-score metrics. Notably, our method excels on the PerfBrush dataset, a self-constructed test set featuring previously unseen types of edits. Here, where traditional methods typically falter, achieving markedly low scores, our approach demonstrates promising performance.

[Arxiv](https://arxiv.org/abs/2412.03809)