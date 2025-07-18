# # AudioJudge：解析大音频模型语音评估中的有效因素

发布时间：2025年07月16日

`LLM应用` `语音技术` `音频技术`

> AudioJudge: Understanding What Works in Large Audio Model Based Speech Evaluation

# 摘要

> 语音评估目前面临两大难题：一是设计专门针对音频特性的系统既需要又困难，二是自动评估方法与人类偏好之间的相关性较差。本研究系统地探讨了将大型音频模型（LAM）作为评判者——AudioJudge，研究它是否能提供一个统一的评估框架，同时解决上述两大挑战。我们系统性地探索了AudioJudge在音频特性检测任务中的应用，包括发音、语速、说话人识别和语音质量，并针对自动基准测试进行了系统级的人类偏好模拟。我们研究了不同的提示工程策略，发现音频拼接结合上下文学习能显著提升音频特性检测和人类偏好模拟任务的性能。我们进一步引入了一个多维度集成的AudioJudge，以实现通用的多维度音频评估。该方法将语音评估分解为专门针对词汇内容、语音质量和副语言特征的评判者，实现了在我们的系统排名基准上与人类偏好高达0.91的斯皮尔曼相关性。鲁棒性分析表明，尽管LAM在噪声环境下仍保持强劲性能，但存在显著的冗长和位置偏见，需要谨慎缓解。


> Current speech evaluation suffers from two critical limitations: the need and difficulty of designing specialized systems targeting individual audio characteristics, and poor correlation between automatic evaluation methods and human preferences. This work presents a systematic study of Large Audio Model (LAM) as a Judge, AudioJudge, investigating whether it can provide a unified evaluation framework that addresses both challenges. We systematically explore AudioJudge across audio characteristic detection tasks, including pronunciation, speaking rate, speaker identification and speech quality, and system-level human preference simulation for automated benchmarking. We investigate different prompt engineering strategies, finding that audio concatenation combined with in-context learning significantly improves performance across both audio characteristic detection and human preference simulation tasks. We further introduce a multi-aspect ensemble AudioJudge to enable general-purpose multi-aspect audio evaluation. This method decomposes speech assessment into specialized judges for lexical content, speech quality, and paralinguistic features, achieving up to 0.91 Spearman correlation with human preferences on our system ranking benchmark. Robustness analysis reveals that while LAMs maintain strong performance under acoustic noise, they exhibit significant verbosity and positional biases that require careful mitigation.

[Arxiv](https://arxiv.org/abs/2507.12705)