# 多模态大型语言模型助力以自我为中心的视频问答研究

发布时间：2025年04月06日

`LLM应用` `视频处理` `问答系统`

> Advancing Egocentric Video Question Answering with Multimodal Large Language Models

# 摘要

> 第一人称视频问答（QA）要求模型处理长时间跨度的时序推理、第一人称视角以及频繁的摄像头运动等特殊挑战。本文系统性地评估了专有和开源的多模态大型语言模型（MLLMs）在优化后的QaEgo4Dv2数据集上的表现。我们测试了四个流行的MLLMs（GPT-4o、Gemini-1.5-Pro、Video-LLaVa-7B 和 Qwen2-VL-7B-Instruct），分别采用零-shot 和微调方法在OpenQA 和 CloseQA 设置下进行评估。为了减少QaEgo4D中的标注噪声，我们引入了QaEgo4Dv2以实现更可靠的比较。实验结果表明，微调后的Video-LLaVa-7B 和 Qwen2-VL-7B-Instruct 达到了新的最先进性能，相比之前基准分别提升了+2.6%的ROUGE/METEOR（针对OpenQA）和+13%的准确率（针对CloseQA）。通过全面的错误分析，我们发现模型在空间推理和细粒度物体识别方面仍存在困难，这为未来的研究指明了方向。

> Egocentric Video Question Answering (QA) requires models to handle long-horizon temporal reasoning, first-person perspectives, and specialized challenges like frequent camera movement. This paper systematically evaluates both proprietary and open-source Multimodal Large Language Models (MLLMs) on QaEgo4Dv2 - a refined dataset of egocentric videos derived from QaEgo4D. Four popular MLLMs (GPT-4o, Gemini-1.5-Pro, Video-LLaVa-7B and Qwen2-VL-7B-Instruct) are assessed using zero-shot and fine-tuned approaches for both OpenQA and CloseQA settings. We introduce QaEgo4Dv2 to mitigate annotation noise in QaEgo4D, enabling more reliable comparison. Our results show that fine-tuned Video-LLaVa-7B and Qwen2-VL-7B-Instruct achieve new state-of-the-art performance, surpassing previous benchmarks by up to +2.6% ROUGE/METEOR (for OpenQA) and +13% accuracy (for CloseQA). We also present a thorough error analysis, indicating the model's difficulty in spatial reasoning and fine-grained object recognition - key areas for future improvement.

[Arxiv](https://arxiv.org/abs/2504.04550)