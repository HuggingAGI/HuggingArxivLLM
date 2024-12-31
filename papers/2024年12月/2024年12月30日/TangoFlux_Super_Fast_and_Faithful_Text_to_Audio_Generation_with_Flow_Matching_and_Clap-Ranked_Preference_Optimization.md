# TangoFlux：借助流匹配与 Clap 排名偏好优化，实现超快速且忠实的文本转音频生成

发布时间：2024年12月30日

`LLM应用` `模型生成`

> TangoFlux: Super Fast and Faithful Text to Audio Generation with Flow Matching and Clap-Ranked Preference Optimization

# 摘要

> 我们推出了 TangoFlux，这是一个拥有 5.15 亿参数的高效文本转音频（TTA）生成模型，在单个 A40 GPU 上仅 3.7 秒就能生成长达 30 秒的 44.1kHz 音频。TTA 模型对齐的关键难题在于难以创建偏好对，因为 TTA 不像大型语言模型（LLMs）那样具备可验证奖励或黄金标准答案之类的结构化机制。为此，我们提出了 CLAP 排名偏好优化（CRPO）这一全新框架，它能迭代生成并优化偏好数据，以强化 TTA 对齐。我们表明，使用 CRPO 生成的音频偏好数据集优于现有的方案。依靠这个框架，TangoFlux 在客观和主观基准方面均达到了顶尖水平。我们将所有代码和模型开源，以助力 TTA 生成的进一步研究。

> We introduce TangoFlux, an efficient Text-to-Audio (TTA) generative model with 515M parameters, capable of generating up to 30 seconds of 44.1kHz audio in just 3.7 seconds on a single A40 GPU. A key challenge in aligning TTA models lies in the difficulty of creating preference pairs, as TTA lacks structured mechanisms like verifiable rewards or gold-standard answers available for Large Language Models (LLMs). To address this, we propose CLAP-Ranked Preference Optimization (CRPO), a novel framework that iteratively generates and optimizes preference data to enhance TTA alignment. We demonstrate that the audio preference dataset generated using CRPO outperforms existing alternatives. With this framework, TangoFlux achieves state-of-the-art performance across both objective and subjective benchmarks. We open source all code and models to support further research in TTA generation.

[Arxiv](https://arxiv.org/abs/2412.21037)