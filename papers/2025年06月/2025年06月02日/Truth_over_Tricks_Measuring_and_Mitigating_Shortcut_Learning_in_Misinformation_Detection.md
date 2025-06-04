# 真实胜于捷径：虚假信息检测中的捷径学习识别与缓解

发布时间：2025年06月02日

`LLM应用` `信息科学`

> Truth over Tricks: Measuring and Mitigating Shortcut Learning in Misinformation Detection

# 摘要

> 错误信息检测模型常依赖于与训练数据相关的浅层线索（即\emph{捷径}），但这些模型难以推广到现实世界中多样且不断演变的错误信息。这一问题因大型语言模型（LLMs）而加剧，因为它们可以通过简单的提示轻松生成令人信服的错误信息。我们推出TruthOverTricks，一个统一的评估范式，用于衡量错误信息检测中的捷径学习。TruthOverTricks将捷径行为分为内在捷径诱导和外在捷径注入，并在14个流行基准测试中评估了7个检测器，同时引入了两个新数据集NQ-Misinfo和Streaming-Misinfo。实证结果表明，现有检测器在面对自然和对抗性捷径时性能大幅下降。为解决这一问题，我们提出SMF框架，通过改写、事实摘要和情感归一化来减少捷径依赖。SMF在16个基准测试中提升了模型的鲁棒性，推动模型依赖深层语义理解而非捷径。我们已在GitHub公开发布了相关资源，助力错误信息检测技术的发展。

> Misinformation detection models often rely on superficial cues (i.e., \emph{shortcuts}) that correlate with misinformation in training data but fail to generalize to the diverse and evolving nature of real-world misinformation. This issue is exacerbated by large language models (LLMs), which can easily generate convincing misinformation through simple prompts. We introduce TruthOverTricks, a unified evaluation paradigm for measuring shortcut learning in misinformation detection. TruthOverTricks categorizes shortcut behaviors into intrinsic shortcut induction and extrinsic shortcut injection, and evaluates seven representative detectors across 14 popular benchmarks, along with two new factual misinformation datasets, NQ-Misinfo and Streaming-Misinfo. Empirical results reveal that existing detectors suffer severe performance degradation when exposed to both naturally occurring and adversarially crafted shortcuts. To address this, we propose SMF, an LLM-augmented data augmentation framework that mitigates shortcut reliance through paraphrasing, factual summarization, and sentiment normalization. SMF consistently enhances robustness across 16 benchmarks, encouraging models to rely on deeper semantic understanding rather than shortcut cues. To promote the development of misinformation detectors, we have published the resources publicly at https://github.com/whr000001/TruthOverTricks.

[Arxiv](https://arxiv.org/abs/2506.02350)