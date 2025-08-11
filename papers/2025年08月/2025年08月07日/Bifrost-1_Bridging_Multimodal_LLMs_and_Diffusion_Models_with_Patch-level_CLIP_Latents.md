# Bifrost-1: 通过补丁级别CLIP潜空间连接多模态大语言模型与扩散模型

发布时间：2025年08月07日

`LLM应用` `计算机视觉` `图像生成`

> Bifrost-1: Bridging Multimodal LLMs and Diffusion Models with Patch-level CLIP Latents

# 摘要

> 将高保真视觉合成能力与大型语言模型（LLMs）相结合，同时保持其强大的推理能力，正成为研究热点。现有方法直接训练LLMs或连接LLMs与扩散模型，通常面临高昂的训练成本，因为预训练的LLMs在预训练过程中未见过图像表示。为此，我们提出了Bifrost-1，一个连接预训练多模态LLMs（MLLMs）与扩散模型的统一框架。该框架采用与MLLMs的CLIP视觉编码器原生对齐的基于patch的CLIP图像嵌入作为潜在变量，并通过对其ControlNet进行轻量化适配，将其整合到扩散模型中。为保留MLLMs的多模态推理能力，我们在预测基于patch的图像嵌入时，为MLLM配备了由原始参数初始化的视觉生成分支。通过基于patch的CLIP潜在变量，Bifrost-1实现了预训练MLLMs与扩散模型的无缝整合，不仅实现了高保真可控图像生成，还显著提升了训练效率。实验结果显示，Bifrost-1在视觉保真度和多模态理解方面优于现有方法，且训练计算成本大幅降低。我们还通过全面的消融研究，验证了设计选择的有效性。


> There is growing interest in integrating high-fidelity visual synthesis capabilities into large language models (LLMs) without compromising their strong reasoning capabilities. Existing methods that directly train LLMs or bridge LLMs and diffusion models usually suffer from costly training since the backbone LLMs have not seen image representations during pretraining. We present Bifrost-1, a unified framework that bridges pretrained multimodal LLMs (MLLMs) and diffusion models using patch-level CLIP image embeddings as latent variables, which are natively aligned with the MLLM's CLIP visual encoder. These patch-level image embeddings are integrated into the diffusion model with a lightweight adaptation of its ControlNet. To retain the original multimodal reasoning capabilities of MLLMs, we equip the MLLM with a visual generation branch initialized from the original MLLM parameters when predicting the patch-level image embeddings. By seamlessly integrating pretrained MLLMs and diffusion models with patch-level CLIP latents, our framework enables high-fidelity controllable image generation with significant training efficiency. Our experiments demonstrate that Bifrost-1 achieves comparable or better performance than previous methods in terms of visual fidelity and multimodal understanding, with substantially lower compute during training. We also provide comprehensive ablation studies showing the effectiveness of our design choices.

[Arxiv](https://arxiv.org/abs/2508.05954)