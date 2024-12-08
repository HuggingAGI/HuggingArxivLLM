# MoTe：用于多个生成任务的运动-文本扩散模型学习

发布时间：2024年11月29日

`LLM应用` `运动分析` `多模态模型`

> MoTe: Learning Motion-Text Diffusion Model for Multiple Generation Tasks

# 摘要

> 最近，得益于去噪扩散模型和大型语言模型等出色的生成模型，人类运动分析取得了显著进步。但现有的方法多聚焦于依据文本描述生成运动，却忽视了相互的任务。在本文中，我们推出了【MoTe】，这一统一的多模态模型能通过同步学习运动与文本的边缘、条件和联合分布来处理各类任务。MoTe 让我们只需修改输入上下文，就能处理成对的文本-运动生成、运动字幕和文本驱动的运动生成。具体而言，MoTe 由三个部分构成：运动编码器-解码器（MED）、文本编码器-解码器（TED）和运动-文本扩散模型（MTDM）。特别地，MED 和 TED 分别用于提取潜在嵌入，并从提取的嵌入中重建运动序列和文本描述。而 MTDM 则对输入上下文进行迭代去噪处理各类任务。在基准数据集上的实验结果显示，我们提出的方法在文本到运动生成方面表现卓越，在运动字幕方面也颇具竞争力。

> Recently, human motion analysis has experienced great improvement due to inspiring generative models such as the denoising diffusion model and large language model. While the existing approaches mainly focus on generating motions with textual descriptions and overlook the reciprocal task. In this paper, we present~\textbf{MoTe}, a unified multi-modal model that could handle diverse tasks by learning the marginal, conditional, and joint distributions of motion and text simultaneously. MoTe enables us to handle the paired text-motion generation, motion captioning, and text-driven motion generation by simply modifying the input context. Specifically, MoTe is composed of three components: Motion Encoder-Decoder (MED), Text Encoder-Decoder (TED), and Moti-on-Text Diffusion Model (MTDM). In particular, MED and TED are trained for extracting latent embeddings, and subsequently reconstructing the motion sequences and textual descriptions from the extracted embeddings, respectively. MTDM, on the other hand, performs an iterative denoising process on the input context to handle diverse tasks. Experimental results on the benchmark datasets demonstrate the superior performance of our proposed method on text-to-motion generation and competitive performance on motion captioning.

[Arxiv](https://arxiv.org/abs/2411.19786)