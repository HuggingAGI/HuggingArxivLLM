# 为多语言语音识别设计的选择性调用方法：基于语音识别难度的成本效益策略

发布时间：2025年05月21日

`LLM应用

理由：这篇论文探讨了如何应用语音大型语言模型（SLLM）来优化多语言自动语音识别（ASR）系统。通过提出SIMA方法，作者展示了SLLM在选择性调用ASR模型方面的实际应用，从而减少了错误率和调用成本。这属于LLM在实际任务中的应用，因此归类为LLM应用。` `语音识别` `多语言`

> Selective Invocation for Multilingual ASR: A Cost-effective Approach Adapting to Speech Recognition Difficulty

# 摘要

> 多语言自动语音识别 (ASR) 虽然进步显著，但语言差异和数据失衡仍影响性能。语言识别 (LID) 模型虽能分路语音，却面临高成本和误分类问题。为此，我们提出 SIMA，一种基于语音难度的多语言 ASR 选择性调用方法。SIMA 基于语音大型语言模型 (SLLM)，判断语音是直接转录还是需调用最优 ASR 模型。相比 SLLM，词错误率降低 18.7%，调用成本减半。三个数据集的测试显示，SIMA 是一个多语言 ASR 的高效解决方案。

> Although multilingual automatic speech recognition (ASR) systems have significantly advanced, enabling a single model to handle multiple languages, inherent linguistic differences and data imbalances challenge SOTA performance across all languages. While language identification (LID) models can route speech to the appropriate ASR model, they incur high costs from invoking SOTA commercial models and suffer from inaccuracies due to misclassification. To overcome these, we propose SIMA, a selective invocation for multilingual ASR that adapts to the difficulty level of the input speech. Built on a spoken large language model (SLLM), SIMA evaluates whether the input is simple enough for direct transcription or requires the invocation of a SOTA ASR model. Our approach reduces word error rates by 18.7% compared to the SLLM and halves invocation costs compared to LID-based methods. Tests on three datasets show that SIMA is a scalable, cost-effective solution for multilingual ASR applications.

[Arxiv](https://arxiv.org/abs/2505.16168)