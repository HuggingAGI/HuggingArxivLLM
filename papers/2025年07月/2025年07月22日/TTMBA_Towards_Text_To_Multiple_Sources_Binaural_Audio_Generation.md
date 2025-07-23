# TTMBA：探索基于多源文本的双耳音频生成方法

发布时间：2025年07月22日

`LLM应用` `音频生成` `语言模型`

> TTMBA: Towards Text To Multiple Sources Binaural Audio Generation

# 摘要

> 现有文本到音频（TTA）生成方法多为单声道输出，忽视了沉浸式听觉体验所需的关键空间信息。针对此问题，我们提出了一种具备时域与空域双重控制能力的文本到多源双耳音频生成（TTMBA）级联方法。该方法首先利用预训练大型语言模型（LLM）将文本分割为结构化格式，为每个声音事件标注时间及空间细节。随后，预训练单声道音频生成网络为每个事件生成多个不同时长的单声道音频。接着，通过基于LLM空间数据的双耳渲染神经网络将这些单声道音频转换为双耳音频。最后，按音频起始时间排列双耳音频，生成多源双耳音频。实验结果表明，与现有方法相比，本方法在音频生成质量及空间感知准确性方面均表现更优。


> Most existing text-to-audio (TTA) generation methods produce mono outputs, neglecting essential spatial information for immersive auditory experiences. To address this issue, we propose a cascaded method for text-to-multisource binaural audio generation (TTMBA) with both temporal and spatial control. First, a pretrained large language model (LLM) segments the text into a structured format with time and spatial details for each sound event. Next, a pretrained mono audio generation network creates multiple mono audios with varying durations for each event. These mono audios are transformed into binaural audios using a binaural rendering neural network based on spatial data from the LLM. Finally, the binaural audios are arranged by their start times, resulting in multisource binaural audio. Experimental results demonstrate the superiority of the proposed method in terms of both audio generation quality and spatial perceptual accuracy.

[Arxiv](https://arxiv.org/abs/2507.16564)