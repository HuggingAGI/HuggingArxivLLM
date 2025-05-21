# 教音频感知型大语言模型听不到的内容：利用合成负样本缓解幻觉现象

发布时间：2025年05月20日

`LLM应用` `问答系统`

> Teaching Audio-Aware Large Language Models What Does Not Hear: Mitigating Hallucinations through Synthesized Negative Samples

# 摘要

> 近期，音频感知大语言模型（ALLMs）的进展使其能够处理和理解音频输入。然而，这些模型常常产生不存在的声音事件，影响了它们在实际应用中的可靠性。为解决这一问题，我们提出了 LISTEN（通过扩展负样本学习识别声音），这是一种对比式训练方法。该方法利用骨干LLM生成的合成数据，增强ALLMs区分声音存在与否的能力。与之前的方法不同，我们的方法无需修改LLM的参数，而是通过轻量级适配器高效整合音频表示。实验结果表明，LISTEN有效减少了幻觉现象，同时在现有音频问答和推理基准测试中保持了出色性能。此外，该方法在数据和计算效率上更具优势。

> Recent advancements in audio-aware large language models (ALLMs) enable them to process and understand audio inputs. However, these models often hallucinate non-existent sound events, reducing their reliability in real-world applications. To address this, we propose LISTEN (Learning to Identify Sounds Through Extended Negative Samples), a contrastive-like training method that enhances ALLMs' ability to distinguish between present and absent sounds using synthesized data from the backbone LLM. Unlike prior approaches, our method requires no modification to LLM parameters and efficiently integrates audio representations via a lightweight adapter. Experiments show that LISTEN effectively mitigates hallucinations while maintaining impressive performance on existing audio question and reasoning benchmarks. At the same time, it is more efficient in both data and computation.

[Arxiv](https://arxiv.org/abs/2505.14518)