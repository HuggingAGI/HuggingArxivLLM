# AudioTrust: 评估音频大语言模型的多维度可信性

发布时间：2025年05月22日

`LLM应用` `语音交互`

> AudioTrust: Benchmarking the Multifaceted Trustworthiness of Audio Large Language Models

# 摘要

> 音频大型语言模型 (ALLMs) 的快速发展及其广泛应用，要求我们深入理解其可信度。然而，关于评估这些模型，特别是与音频模态特有的风险相关的系统性研究，仍然 largely unexplored。现有框架主要关注文本模态或有限安全维度，未能充分考虑音频模态的特性和应用场景。我们推出 AudioTrust——首个专为 ALLMs 设计的多维度可信度评估框架和基准。AudioTrust 覆盖六个关键维度：公平性、幻觉、安全性、隐私性、稳健性和认证性。通过 18 种实验设置，AudioTrust 采用了一个包含 4,420 个音频/文本样本的数据集，样本来自日常对话、紧急呼叫和语音助手交互等真实场景，专门设计用于评估 ALLMs 的可信度。我们设计了 9 个音频特定指标，并利用自动化管道对模型输出进行客观评分。实验结果显示，当前开源和闭源 ALLMs 在高风险音频场景下的可信度边界，为未来音频模型的安全部署提供了重要参考。我们的平台和基准可在 https://github.com/JusperLee/AudioTrust 获取。


> The rapid advancement and expanding applications of Audio Large Language Models (ALLMs) demand a rigorous understanding of their trustworthiness. However, systematic research on evaluating these models, particularly concerning risks unique to the audio modality, remains largely unexplored. Existing evaluation frameworks primarily focus on the text modality or address only a restricted set of safety dimensions, failing to adequately account for the unique characteristics and application scenarios inherent to the audio modality. We introduce AudioTrust-the first multifaceted trustworthiness evaluation framework and benchmark specifically designed for ALLMs. AudioTrust facilitates assessments across six key dimensions: fairness, hallucination, safety, privacy, robustness, and authentication. To comprehensively evaluate these dimensions, AudioTrust is structured around 18 distinct experimental setups. Its core is a meticulously constructed dataset of over 4,420 audio/text samples, drawn from real-world scenarios (e.g., daily conversations, emergency calls, voice assistant interactions), specifically designed to probe the multifaceted trustworthiness of ALLMs. For assessment, the benchmark carefully designs 9 audio-specific evaluation metrics, and we employ a large-scale automated pipeline for objective and scalable scoring of model outputs. Experimental results reveal the trustworthiness boundaries and limitations of current state-of-the-art open-source and closed-source ALLMs when confronted with various high-risk audio scenarios, offering valuable insights for the secure and trustworthy deployment of future audio models. Our platform and benchmark are available at https://github.com/JusperLee/AudioTrust.

[Arxiv](https://arxiv.org/abs/2505.16211)