# MSE-Adapter：轻量级插件，使大型语言模型（LLMs）具备多模态情感分析与情绪识别能力。

发布时间：2025年02月17日

`LLM应用` `情感计算`

> MSE-Adapter: A Lightweight Plugin Endowing LLMs with the Capability to Perform Multimodal Sentiment Analysis and Emotion Recognition

# 摘要

> 目前基于预训练语言模型的多模态情感分析 (MSA) 和对话情绪识别 (ERC) 方法存在两大主要限制：
1) 针对 MSA 和 ERC 任务训练后，这些模型会失去原有的通用能力。
2) 计算资源需求巨大。随着预训练语言模型规模的扩大，传统方法训练大规模 MSA 模型将导致高昂的计算成本。为解决这一难题，我们提出了轻量级插件 	extbf{M}ultimodal 	extbf{S}entiment Analysis and 	extbf{E}motion Recognition 	extbf{Adapter} (MSE-Adapter)。该插件使大型语言模型 (LLM) 能够以极低计算开销（仅增加约 2.6M 到 2.8M 参数）执行 MSA 或 ERC 任务，同时保留 LLM 的原有能力。MSE-Adapter 中的 Text-Guide-Mixer (TGM) 模块通过 Hadamard 乘积建立非文本与文本模态的显式连接，使非文本模态在特征层面与文本模态更好对齐，从而生成更高质量的伪标记。我们在四个公开中英文数据集上，使用消费级 GPU 和开源 LLM（Qwen-1.8B、ChatGLM3-6B-base 和 LLaMA2-7B）进行了实验，结果验证了该插件的有效性。代码将在匿名评审后发布到 GitHub。

> Current Multimodal Sentiment Analysis (MSA) and Emotion Recognition in Conversations (ERC) methods based on pre-trained language models exhibit two primary limitations:
  1) Once trained for MSA and ERC tasks, these pre-trained language models lose their original generalized capabilities. 2) They demand considerable computational resources. As the size of pre-trained language models continues to grow, training larger multimodal sentiment analysis models using previous approaches could result in unnecessary computational cost. In response to this challenge, we propose \textbf{M}ultimodal \textbf{S}entiment Analysis and \textbf{E}motion Recognition \textbf{Adapter} (MSE-Adapter), a lightweight and adaptable plugin. This plugin enables a large language model (LLM) to carry out MSA or ERC tasks with minimal computational overhead (only introduces approximately 2.6M to 2.8M trainable parameters upon the 6/7B models), while preserving the intrinsic capabilities of the LLM. In the MSE-Adapter, the Text-Guide-Mixer (TGM) module is introduced to establish explicit connections between non-textual and textual modalities through the Hadamard product. This allows non-textual modalities to better align with textual modalities at the feature level, promoting the generation of higher-quality pseudo tokens. Extensive experiments were conducted on four public English and Chinese datasets using consumer-grade GPUs and open-source LLMs (Qwen-1.8B, ChatGLM3-6B-base, and LLaMA2-7B) as the backbone. The results demonstrate the effectiveness of the proposed plugin. The code will be released on GitHub after a blind review.

[Arxiv](https://arxiv.org/abs/2502.12478)